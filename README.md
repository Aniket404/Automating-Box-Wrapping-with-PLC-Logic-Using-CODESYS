# Automating-Box-Wrapping-with-PLC-Logic-Using-CODESYS
Box Wrapper Automation System: A ladder logic program written in CODESYS for automating box wrapping. Features motor control, position monitoring, and overload safety with real-time feedback. Solved gateway communication issues and synchronized motors for industrial packaging efficiency. Optimized for safety and reliability.
This repository contains a ladder logic program for automating a Box Wrapper System, written in CODESYS. The project demonstrates industrial automation techniques for managing motor control, safety mechanisms, and operational monitoring commonly used in the packaging industry.

Features
Motor Control:

Control logic for rotational and sliding motors using Boolean inputs and frequency control.
Overload protection with timers (TON) and counters (CTU).
Position Monitoring and Safety:

Integrated High-Level Switch (HLSW) and Low-Level Switch (LLSW) for slider position monitoring.
Emergency stop (EMGC) and motor overload safety mechanisms.
Real-Time Feedback:

Visual progress tracking through slider and rotational motor counters using animation variables.
Dynamic Control:

Factor-based adjustments for speed and load handling with RotationFactor and SliderFactor.
Challenges Solved
Gateway Communication Issue:
Resolved a communication problem between the PLC and programming environment by optimizing network settings and addressing gateway service dependencies, using insights from the CODESYS Forum.

Synchronization and Safety:
Ensured precise synchronization of rotational and sliding motors while handling edge cases like overloads and positional inconsistencies.

Industrial Relevance
This program is designed for real-world applications in packaging and material handling systems, focusing on:

Increased efficiency through automation.
Reduced manual errors.
Enhanced safety with robust emergency protocols.
Repository Contents
Main Program (BoxWrapperMain): Core logic for motor control, safety, and monitoring.
Documentation: Details of implementation and troubleshooting.
Simulation Files: Test cases and scenarios to verify the logic.
How to Use
Import the program into CODESYS.
Simulate or deploy the ladder logic on a supported PLC device.
Monitor motor states, safety mechanisms, and counters in real-time.
Feel free to fork, modify, or contribute to this project. For any questions or collaboration opportunities, reach out to me!

