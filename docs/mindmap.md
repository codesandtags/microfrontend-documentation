---
title: Micro Frontends
markmap:
  colorFreezeLevel: 2
---

# Micro Frontends

## Timeline

- 2010s: Early Beginnings
- 2013 - 2015: Initial Concepts
- 2016: Formal Introduction
- 2017 - 2018: Growth and Adoption
- 2019 - 2020: Maturity and Best Practices
- 2021 - 2022: Standardization and Community Growth
- 2023 - 2024: Advanced Techniques and Future Directions

## Goals

- Enable autonommous teams
- Break down monoloitic applications
- Enable integration of multiple web technologies
- Increase scalability and maintenability

## Trade-offs

- Benefits

  - Increase teams autonomy
  - Independent deployments
  - Simple and decoupled codebases
  - Incremental updates
  - Faster Time To Market (Business)
  - Failures only concern a single service
  - Teams have more freedom to tech stack
  - Customer focus

- Drawbacks
  - Redundancy: Payload size because of duplication
  - Environment differences
  - Additional integration complexity
  - Not suitable for small projects/teams
  - Coordination between teams (versioning, consistent user experience)

## Frameworks, Libraries, Technologies

- [Single SPA (Framework)](https://single-spa.js.org/)
- [Webpack Module Federation](https://webpack.js.org/concepts/module-federation/)
- [Bit](https://bit.dev/)
- [Piral](https://piral.io/)
- [Luigi](https://luigi-project.io/)
- [Mashroom Server](https://www.mashroom-server.com/)
- [Open Components](https://opencomponents.github.io/)

## Challenges

- Communication between Micro Frontends
- Routing
- Composition
- Shared resources

## Techniques

- Vertical Split
- Horizontal Split

## Use Cases

- IKEA (e-commerce)
- DAZN (streaming)
- Spotify (streaming)
- Upwork (freelancing)
- Zalando (e-commerce)
- Hello Fresh (food)

## Books

- Micro Frontends in Action, Michael Geers
- Building Micro Frontends, Luca Mezzarila
- The Art of Micro Frontends, Florian Rappl

## Examples

- [Tractor Store](https://micro-frontends.org/1-composition-client-only/)
