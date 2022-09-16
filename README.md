# Headless UI

```
npm start
```

## Description
- Headless UI is an interface methodology. It's objective is to separate the state/behavior from the implementation of the consumer.

## Methodology
- What is a methodology?
  - What makes a methodology a good one?
  - How do we compare one to another?
  - How do we know we chose the right one?

## Principles of Software Engineering
- Separation of Concerns  
  - is a recognition of the need for human beings to work within a limited context
  - "the human mind is limited to dealing with approximately seven units of data at a time"
  - Examples
    - Internet Protocol Suite
    - Web Apps
    - Aspect-Oriented Programming
    - Memoize
- Anticipation of Change
  - High cohesion
  - Low coupling
- Modularity
  - Responsibility-driven design
- Abstraction
  - "separating the behavior of software components from their implementation"; 
  "what it does, and how it does it."
- Generality
  - "designing software that is free from unnatural restrictions and limitations"
  - Example: two digit numbers for years
- Consistency
  - "idioms for dealing with common programming problems"
  - styling convention
  - testing convention

## Brinqa Components
- The Monolithic Component
  - What is our methodology for our components currently?
    - Host listeners, 
  - Non-modular, non-general, no consistency, high coupling, no separation of concerns

## Headless UI Approach
- Separate the behavior from structure/html.
- Example
  - angular's reactive forms
- Usage of structural directives
    - drag directive
    - scrolling directive
