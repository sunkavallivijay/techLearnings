### Microservices definition:
- An architectural style
- Small: A suite of small services each running in its own process (micro + services)
- Autonomous: Change to one service doesn't affect consuming services
- Communication: Service communicating with lightweight mechanisms, often HTTP Resource api

### Benefits of Microservices:
- Respond to business changes faster with easy & faster development of focused services
- Technology heterogeneity
- Resilience
- Scaling
- Ease of deployment
- Organizational alignment
- Composability (AKA Composing software for reuse across organization)
- Optimizing for replacability (AKA writting code which is small and can be replaced with newer faster technologies; no legacy code)

### SOA & Microservices:
 Microservices are a specific approach for SOA; Same way as Scrum being a specific approach for Agile
 
### Packages Vs Shared Libraries Vs Modules:
- Packages help seperation of code with in the application
- Share libraries (libs) help share a reusable code
- Modules are similar to Shared Libs but difference is, modules can be deployed as seperate *process*. E.g. are OSGI is one approach that was introduced starting Java 9

### Strategic goals, Arechitecture principles, Practices:
- Strategic goals: are business goals of the organization. For e.g. Expanding business to another country Or Get Software products to market faster
- Arechitecture principles: are a set of Software architecture principles/guidelines to achieve the strategic goals for E.g. Build modular systems to enable deployment in another country Or Use distributed systems to scale to new users from new country, Use of agile methodology to achieve Faster market delivery of products
- Practices: talk exactly how principles will be applied. For e.g. Build modular systems using Spring framework and Restful architecture, Deliver product faster using Scrum methodology

### Responsibilities of an architect:
- Vision: Have a clearly communicated technical vision
- Empathy: Understand the impact of your decision on your customer and colleagues
- Collaboration: Work with other teams and team members to defina and execute vision
- Adapt: Change your set vision with the changing needs for your organization
- Autonomy: Find right balance between standards and enabling autonomy to the teams
- Governance: Set tangible goals/objectives against which progress on technical vision can be measured

### General points:
- Role of Architect in IT should be like a town planner, predicting future possibilities, constantly adapting to the changing landscape and people needs. It should not be like a building architect, which doesn't change with time.
- Zoning in town planning is similar to Service boundaries in IT Applications

- Seperation of concerns: Modularity and Encapsulation
- Scalability: Horizontal scalaing and work load distribution

### Scaling approaches:
- Horizontal scaling: means that you scale by adding more machines into your pool of resources whereas,
- Vertical scaling means that you scale by adding more power (CPU, RAM) to an existing machine


Microservices Spring boot example: 
https://www.youtube.com/watch?v=rlS9eH5tEnY&pbjreload=10