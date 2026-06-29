# 01 - Start Here (Year 9 Friendly)

## Goal

Build a robot that can:

- Find and track a ball
- Find the goal
- Stay in the play area
- Avoid or identify other robots
- Communicate with team robots
- Drive with a 3-wheel Kiwi drive and stay stable using PID control

<hr>

## What to learn first

### 1. OpenMV basics and first script

> [!WARNING]
> **Skip the default script in Quickstart 1.3.**
> Running the default script can result in connection issues due to heap exhaustion.

- Quickstart: https://docs.openmv.io/openmvcam/tutorial/quickstart.html
- Python basics for OpenMV: https://docs.openmv.io/openmvcam/tutorial/python/index.html


### 2. Camera and vision basics

- Vision fundamentals: https://docs.openmv.io/openmvcam/tutorial/vision/index.html
- Image processing tutorial: https://docs.openmv.io/openmvcam/tutorial/image/index.html
- OpenMV image API reference: https://docs.openmv.io/library/omv.image.html
- OpenMV sensor API reference: https://docs.openmv.io/library/omv.sensor.html

### 3. Hardware and board quick reference

- Camera quick reference pages: https://docs.openmv.io/openmvcam/quickref.html

## How to work (simple team workflow)

1. Pick one subsystem.
2. Build a tiny test script for only that subsystem.
3. Record what worked and what failed.
4. Merge into the main robot code only after the test passes.

## Suggested subsystem order

1. Ball tracking
2. 3-wheel Kiwi drive motor output control
3. Goal finding
4. Field boundary handling
5. Robot identification
6. Robot-to-robot communication
7. Full game behavior and tuning
