# Week 0 — Billing and Architecture
Iron Triabgle: cost (cheap), time (fast), scope (good)
## Good Architecture
Requirements - Risks - Assumptions - Constraints

### Reqirements
Something the project must achieve, can be technical or business oriented. Requirements should be monitorable, verifiable, tracable, feasible. Ex: meests ISO standards, 80% uptime.

### Risks
Prevents a requirement fomr begin successful. SinglePointofFailues (SPoF), User Commitment, Late Delivery. 

### Assumptions
Factors held as true for the planning & implementation phases. Sufficient network bandwidth, budget is approved.

### Constraints
Policy or technical limitations for the project. Time, budget, vendor selection. 

## Design Types
### Conceptual - Napkin Design
created by stakeholders and architects. Organizes and defines concepts and rules. 

### Logical - Blueprint Design
Defines how the system should be implemented. Environment w/o names or sizes. Ex: API gateway, something for DNS name resolution

### Physical - House
Actual plans to be built. Ex: IP address of EC2 instance, ARN of API gateway, ARN of security gateways. 

## Build a Vernacular
Develop a common dictionary that can be used during the project. 
- Ask dumb questions 