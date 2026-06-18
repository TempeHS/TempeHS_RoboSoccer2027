# 03 - Delivery Checklist

Use this checklist as your definition of done.

## A. Core technical checks

- 3-wheel Kiwi drive can move forward, strafe, and rotate on command
- Ball tracking works in bright and dim lighting
- Goal finding works with your selected marker strategy
- Field boundary logic prevents leaving play area
- Robot identification works for at least two robots
- Robot-to-robot communication sends and receives correctly
- PID control keeps movement stable and smooth
- LCD debug screen shows key robot state and vision values

## B. Evidence to submit

- Short video: ball tracking demo
- Short video: goal finding demo
- Short video: communication between two robots
- Short video: full gameplay behavior
- Short video: Kiwi drive movement test (all directions)
- Screenshot or video of LCD debug screen in action
- Tuning table: P, I, D values and what changed
- Diagram of your state machine (search, chase, align, shoot, recover)

## C. Code quality checks

- Each subsystem has its own test script
- Main script has clear functions and comments
- No hard-coded magic numbers without explanation
- Basic error handling is present

## D. Team process checks

- Every team member can explain one subsystem
- Commits are regular and have meaningful messages
- Failures and fixes are recorded in a short engineering log

## E. Stretch goals (optional)

- Predict ball movement (simple velocity estimate)
- Better communication protocol with acknowledgements
- Dynamic role switching between attacker and defender
