# Test Scenario

A Scenario groups existing test cases by conditional flow, so a full
business journey — not just one case — can be represented and run as a
single unit.

## Building a scenario

1. Create a new Scenario node under a Region
2. Import the test cases that make up the flow, following the same strict
   import logic used across Design
3. Set per-flag controls on each imported case to define how it should
   behave inside the scenario (skip, required, conditional)
4. Save and deploy the same way as a standalone test case
