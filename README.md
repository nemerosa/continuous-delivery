Continuous delivery
===============

## Check-list

### Requirements

- how requirements are collected?
- how requirements are presented to the dev team?
- are testers (or other teams) participating in the requirement collection phase?

### Ticketing

- what ticketing system is used?
- are tickets linked to requirements?
- how are the tickets scoped for development?
- are life-cycle of component/projects linked to the actual releases?

### Source control

- which SCM is used?
- who controls the accesses?
- what is the access policy?
- what is the branching policy?
- what controls are made at commit/push times?
- is the code linked to tickets? Is that enforced?

### Development environment

- how much time does it take for a developer to have a correct environment set-up?
- how is this environment close to the production target?

### Continuous integration

- what CI is used?
- who manages it?
- how is the feedback of the CI made available to the developers?
- how is the versioning managed?

### Code quality control

- is the code base scanned for defaults?
- static and dynamic analysis?
- is it fully automatic?
- who takes care of the output of the analysis? How is it handled?

### Acceptance tests

- how is set-up the acceptance test environment?
- is it static or dynamically created?
- can we have several environments at once?
- how is this environment close to the production target?
- is there a test plan?
- are the test cases linked to requirements or issues?
- are some tests automated?
- are automated tests linked to the requirements and/or tickets and/or test cases?
- how is the coverage of automated tests monitored?
- who is responsible for the outcome of the automated tests?
- what kind of feedback is returned to the testers & developers?
- are successed and failures tracked?

### Delivery

- what are the artifacts produced by the CI?
- are they deployment ready?
- are they environment agnostic? If not, explain why?
- if not, what do they miss?
- where are the artifacts stored?
- what is the storage policy (max age, etc.)
- is the promotion of artifacts tracked in any way?
- how is the change log managed?

### Deployment

- how the artifacts are deployed?
- is the deployment mechanism the same in all environments?
- is the deployment tracked?
- are rollbacks taken into account?
