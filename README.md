# Collision Detector

## High-level Description

The Collision Detector project utilizes an STM32 microcontroller to control the direction of a motor (clockwise or counterclockwise) based on input from an ultrasonic sensor. The system is designed to detect obstacles using the ultrasonic sensor and rotate the motor in the opposite direction to avoid collision.

## Functional Block Diagram

![Screenshot 2024-04-26 at 1 38 40 PM](https://github.com/mhhajj/ECE-5780-Project/assets/122409757/8fbd9b8b-c2d7-4d23-986e-864fbec2f554)


## Outcome Motivation

This project aims to showcase the versatility of the STM32 microcontroller by integrating sensor-based obstacle avoidance functionality with motor control. By utilizing an ultrasonic sensor, we aim to create a practical solution for obstacle detection and avoidance, applicable in various fields such as robotics, automated guided vehicles (AGVs), and drones. Through this project, users can gain hands-on experience in sensor integration, motor control, and system responsiveness.

## Milestones

1. **System Initialization and Sensor Integration (Milestone 1):**
   - Initialize the STM32 microcontroller and interface it with the ultrasonic sensor.
   - Verify successful data acquisition from the sensor and ensure accurate distance measurements.

2. **Motor Control Implementation (Milestone 2):**
   - Develop firmware to interpret sensor data and translate it into motor control commands.
   - Implement algorithms to determine the direction of motor rotation based on obstacle proximity.

3. **Integration and Testing (Milestone 3):**
   - Integrate the motor control system with the STM32 microcontroller, ensuring seamless communication and functionality.
   - Conduct extensive testing to validate the system's ability to detect obstacles and perform effective avoidance maneuvers.

4. **Documentation and Final Presentation:**
   - Prepare comprehensive documentation covering hardware and software aspects of the project.
   - Compile results, observations, and insights gained throughout the development process.
   - Deliver a final presentation showcasing the project's functionality, challenges faced, and future enhancements.

## Discussion of Risks

- **Hardware Compatibility:** Ensure compatibility between the STM32 microcontroller and the chosen motor, as well as any other peripherals used such as the ultrasonic sensor.
- **Software Stability:** Rigorous testing and error handling mechanisms will be implemented to ensure the stability and reliability of the firmware.
- **Integration Challenges:** Potential challenges may arise during the integration of hardware and software components. Regular communication and collaborative problem-solving within the team will mitigate these risks.

By following these milestones and addressing potential risks, we aim to deliver a successful project that demonstrates our laboratory skills, creativity, and ability to overcome technical challenges.
