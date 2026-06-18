# 02 - Topic Links

This page gives direct links to official docs and tutorials for each required project part.

## 3-Wheel Kiwi Drive control

Official links:

- PWM API: https://docs.openmv.io/library/machine.PWM.html
- Timer API: https://docs.openmv.io/library/machine.Timer.html
- Time module (for control loop timing): https://docs.openmv.io/library/time.html
- Math module (for wheel-mix calculations): https://docs.openmv.io/library/math.html
- Full machine module: https://docs.openmv.io/library/machine.html
- Hardware quick references: https://docs.openmv.io/openmvcam/quickref.html

What students should deliver:

- A script that converts vx, vy, and w into 3 wheel speeds
- Smooth movement in all directions with no shaking
- A working test for each movement direction (forward, sideways, rotate)

Kiwi drive control notes (Year 9 version):

- Think of robot speed as three values: vx (left-right), vy (forward-back), and w (turn)
- Compute three wheel commands from that speed target
- Clamp wheel outputs so motor values stay safe
- Use PID per wheel or per motion axis, then tune one thing at a time

If your build uses the OpenMV Servo Shield for output hardware:

- Servo Shield docs: https://docs.openmv.io/openmvcam/shields/servo-shield.html

## Ball tracking

Official links:

- Image tutorial index: https://docs.openmv.io/openmvcam/tutorial/image/index.html
- Blob finding: https://docs.openmv.io/openmvcam/tutorial/image/finding/blobs.html
- Circles and rectangles: https://docs.openmv.io/openmvcam/tutorial/image/finding/circles-and-rectangles.html
- Thresholding: https://docs.openmv.io/openmvcam/tutorial/image/thresholding/binary-method.html
- Image API reference: https://docs.openmv.io/library/omv.image.html

What students should deliver:

- Reliable ball detection at different distances
- Ball center x,y output each frame
- Confidence checks (ignore tiny or noisy detections)

## Goal finding

Official links:

- Lines and segments: https://docs.openmv.io/openmvcam/tutorial/image/finding/lines-and-segments.html
- Regression and similarity: https://docs.openmv.io/openmvcam/tutorial/image/analysis/regression-and-similarity.html
- QR and AprilTag decoding: https://docs.openmv.io/openmvcam/tutorial/image/decoding/qr-apriltag.html
- Barcodes and DataMatrix: https://docs.openmv.io/openmvcam/tutorial/image/decoding/barcodes-and-datamatrix.html

What students should deliver:

- Detect goal area marker or line system used in your game rules
- Return heading error from robot center to target goal

## Communication between robots

Official links:

- Protocol tutorial: https://docs.openmv.io/openmvcam/tutorial/protocol/index.html
- Networking tutorial: https://docs.openmv.io/openmvcam/tutorial/networking/index.html
- Bluetooth tutorial: https://docs.openmv.io/openmvcam/tutorial/bluetooth/index.html
- UART API: https://docs.openmv.io/library/machine.UART.html
- I2C API: https://docs.openmv.io/library/machine.I2C.html
- SPI API: https://docs.openmv.io/library/machine.SPI.html

What students should deliver:

- One simple message protocol (example: role, ball_seen, x, y, timestamp)
- Retry and timeout behavior
- A demo with two robots exchanging data

## Game play area (field awareness)

Official links:

- Camera calibration: https://docs.openmv.io/openmvcam/tutorial/vision/sensor/calibration.html
- Perspective correction: https://docs.openmv.io/openmvcam/tutorial/image/transforms/perspective-correction.html
- Lens and perspective: https://docs.openmv.io/openmvcam/tutorial/image/transforms/lens-and-perspective.html
- Pixel formats: https://docs.openmv.io/openmvcam/tutorial/image/foundations/pixel-formats.html
- Regions and masks: https://docs.openmv.io/openmvcam/tutorial/image/foundations/regions-and-masks.html

What students should deliver:

- A field mask or boundary system
- Robot behavior when near out-of-bounds

## Identifying other robots

Official links:

- QR and AprilTag decoding: https://docs.openmv.io/openmvcam/tutorial/image/decoding/qr-apriltag.html
- Template and similarity matching: https://docs.openmv.io/openmvcam/tutorial/image/matching/template-and-similarity.html
- Displacement and keypoints: https://docs.openmv.io/openmvcam/tutorial/image/matching/displacement-and-keypoints.html

What students should deliver:

- Robot ID method chosen and explained
- At least one test where two robot IDs are correctly separated

## PID control

Use the same PID style students already know from:

- https://github.com/TempeHS/RP2040_Competition_Robot

Helpful official links:

- Time module for dt timing: https://docs.openmv.io/library/time.html
- Math module: https://docs.openmv.io/library/math.html
- MicroPython memory and performance: https://docs.openmv.io/openmvcam/tutorial/python/micropython/memory-and-gc.html

What students should deliver:

- Reused or adapted PID class
- Separate tuning values for vx, vy, and turn (w)
- Tuning logs (P, I, D values and results)
- Completed worksheet: [04 - Kiwi Drive Tuning Worksheet](04-kiwi-drive-tuning-worksheet.md)

## LCD Shield debugging (OpenMV)

Official links:

- Touch LCD Shield docs: https://docs.openmv.io/openmvcam/shields/touch-lcd-shield.html
- FrameBuffer API (drawing text and debug info): https://docs.openmv.io/library/framebuf.html
- OpenMV image API (for drawing overlays): https://docs.openmv.io/library/omv.image.html

What students should deliver:

- A simple debug screen that shows mode, fps, and key values
- On-screen values for ball x,y and goal heading error
- A color warning on screen when no ball or no goal is detected

## Extra topics often missed (important)

Official links:

- Debugging in MicroPython: https://docs.openmv.io/openmvcam/tutorial/python/micropython/debugging.html
- Error handling: https://docs.openmv.io/openmvcam/tutorial/python/errors/handling-errors.html
- OpenMV tools tutorial: https://docs.openmv.io/openmvcam/tutorial/tools/index.html
- Production and reliability tutorial: https://docs.openmv.io/openmvcam/tutorial/production/index.html

What students should deliver:

- A startup self-check (camera ok, comms ok, control output ok)
- Failsafe behavior if ball or goal is lost
- One-page test report with evidence videos
