# Building Micro frontends

There are several approaches to build Micro frontends, here I list the most popular ones.

## Single SPA

"A javascript router for front-end microservices". Single-spa is a JavaScript library that allows for the creation of micro frontends within a single web application.

### How it works?

It works by creating a “shell” application that loads and manages different micro frontends as they are needed. This allows for a more modular and decoupled architecture, similar to module federation.

### Benefits

- It allows a more flexible architecture.
- Because each micro frontend is a standalone application, teams can use different frameworks and libraries within the same application
- It allows a better performance by only loading the micro frontends that are needed at a given time.


## Webpack Module Federation

Multiple separate builds should form a single application. These separate builds act like containers and can expose and consume code among themselves, creating a single, unified application. This is often known as Micro-Frontends, but is not limited to that.

### How it works?

It works by creating a central “entry” point for each module, which can then be imported and used by other modules. Each module can be deployed in a different server, allowing teams to deploy independently.


### Benefits

- It allows a more modular and decoupled architecture
- Each module can be developed and tested independently of the others
- It allows better code reuse

### Drawbacks

- Each module must be built using the same framework (Angular, React, Vue)


## Differences between techniques

- Module federation uses a central “entry” point for each module, while single-spa uses a “shell” application to load and manage different micro frontends.
- Module federation requires that all modules be built using the same framework, while single-spa allows for the use of different frameworks within the same application.
- Module federation can be more efficient when sharing code across modules, while single-spa can be more efficient when loading and managing micro frontends.
- When using module federation with Angular, React, or Vue JS frameworks, it is important to note that each module must be built using the same framework, while single-spa allows for the use of different frameworks within the same application.
