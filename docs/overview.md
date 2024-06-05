# Overview

## Trade-offs

## Benefits / Pros

- **Increase teams autonomy**: With micro frontends, teams can work independently on different parts of the application, which improves their autonomy and reduces inter-team dependencies.
- **Independent deployments**: Micro frontends allow teams to deploy their services independently, which reduces the risk of deployment failures and allows for faster time-to-market.
- **Simple and decoupled codebases**: Micro frontends enable teams to build and maintain smaller, more focused codebases, which are easier to understand, test, and maintain.
- **Incremental updates**: Micro frontends allow teams to make incremental updates to their services without affecting other parts of the application, which reduces the risk of introducing bugs and improves the overall stability of the system.
- **Faster Time To Market (Business)**: Having independent teams working on different parts of the application with independent deployments, allows for faster development and deployment cycles, which can help businesses bring new features to market more quickly.
- **Failures only concern a single service**: If a micro frontend fails, it only affects that specific service, not the entire application. This can help reduce the impact of failures and improve the overall reliability of the system.
- **Teams have more freedom to tech stack**: Different teams can use different technologies and frameworks to build their micro frontends, which allows them to choose the best tools for the job and work with technologies they are comfortable with (like React, Angular, Vue.js, etc).
- **Customer focus**: Micro frontends allow teams to focus on specific customer needs and deliver features that are tailored to those needs, which can improve the overall user experience and customer satisfaction.

## Drawbacks / Cons

- **Redundancy: Payload size because of duplication**: Micro frontends can lead to code duplication and increased payload size, as each micro frontend may include its own copy of shared libraries and dependencies. When not managed properly, this can lead to performance issues and slower loading times.
- **Environment differences**: Different micro frontends may have different dependencies, configurations, and environments, which can make it challenging to ensure consistency across the application. This can lead to integration issues and compatibility problems between micro frontends.
- **Additional integration complexity**: Micro frontends require additional integration work to combine the different services into a cohesive user experience. This can introduce complexity and overhead, especially when dealing with cross-cutting concerns like routing, state management, and data sharing.
- **Not suitable for small projects/teams**: Micro frontends are best suited for large, complex applications with multiple teams working on different parts of the application. For small projects or teams, the overhead of managing multiple services and deployments may outweigh the benefits of micro frontends.
- **Coordination between teams (versioning, consistent user experience)**: Coordinating between multiple teams working on different micro frontends can be challenging, especially when it comes to versioning, ensuring a consistent user experience, and managing dependencies between services.
- **Performance issues (loading times, memory consumption)**: Micro frontends can introduce performance issues, such as slower loading times and increased memory consumption, especially when not optimized properly. Managing multiple services and dependencies can lead to additional overhead and complexity that can impact the overall performance of the application.

## Conclusions

- Micro frontends is an alternative approach to traditional software development, dividing an application into vertical slices, each managed by a dedicated team.
- This approach allows for feature development to be optimized, with teams including all necessary skills and reducing coordination between frontend and backend teams.
- Each team is responsible for their complete stack, from frontend to database, allowing for easier frontend upgrades and increased customer focus.
- The micro frontends approach is based on autonomous teams and systems, each with its own data store, reducing reliance on synchronous calls to other systems.
- Teams should be cross-functional, with members working together on a specific customer need, rather than being grouped by skills or technologies.
- This approach allows for the creation of interdisciplinary teams, which can come up with more creative and effective solutions for their specific area of expertise.
