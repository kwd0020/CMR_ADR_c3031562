# Selection of the Frontend Framework

## Context and Problem Statement
Designing and developing a multi-tenant Complaint Mangement System followng a layered monolithic approach for the codebase in which the frontend must follow accessibility standards (WCAG Level 2), while ensuring 24/7 opertion with responsive design and real-time ticket status. The performance and scalability of the considered technologies will significantly impact the decision. The architecural decision involves selecting possible frameworks that can be used to develop a layered monolith.

## Guarenteed Technologies
* CSS
* HTML
* 

## Considered Frontend Technologies

* React -  reausable components for ease of use, with fast performance.
* PHP with Laravel.
* Next.js - supports servide-side rendering meaning it provides a high degree of performance and scalability.

## Decision Outcome
PHP with Laravel.

### Consequences

* Good, Provides server-side processing meaning an increase in load times if handled correctly. Integration of real-time ticket status updates is also possible with this technology through the use of WebSockets. Furthermore, a Multi-Tenant approach is also supported which can be used to satisfy non-functional requirements. Finally, I am most familiar with this technology which will improve the development time during sprints.
* Bad,
