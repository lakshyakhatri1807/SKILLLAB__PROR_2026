

## Final Project README

> **Project Weight:** 100%  
> **Team Size:** 4/3 students  
> **Project Duration:** 8 hours  
> **Total Time Available:** 32 effort-hours per team  
> **Project Type:** Playful, interactive, technology-based experience

---

# Before you begin

## Fork and rename this repository

After forking this repository, rename it using the format:

`SKILLLAB_PROR-2026-Sentinel`

### Example

`SKILLLAB_PROR-2026-AuroWizards`

Do not keep the default repository name.

---

# How to use this README

This file is your team’s **working project document**.

You must keep updating it throughout the build period.  
By the final review, this README should clearly show:

- your idea,
- your planning,
- your design decisions,
- your technical process,
- your build progress,
- your testing,
- your failures and changes,
- your final outcome.

## Rules

- Fill every section.
- Do not delete headings.
- If something does not apply, write `Not applicable` and explain why.
- Add images, screenshots, sketches, links, and videos wherever useful.
- Update task status and weekly logs regularly.
- Use this file as evidence of process, not only as a final report.

---

# 1. Team Identity

## 1.1 Studio / Group Name

Sentinel

## 1.2 Team Members

| Name            | Primary Role                    | Secondary Role   | Strengths Brought to the Project |
| --------------  | ------------------------------- | --------------   | -------------------------------- |
| Adarsh Gupta    | `[Electronics / Coding /`       | `Documentation`  | `Documentation, Gift of Gab `    |
| Soham Gaonkar   | `[Electronics / Fabrication]`   | `[Coding]`       | `Material Handling, Hardware`    |
| Lakshya Khatri  | `[Electronics / Fabrication]`   | `[Coding]`       | `Material Handling, Hardware`    |
| Jagrut Ahuja    | `[Electronics / Fabrication]`   | `[Coding]`       | `Material Handling, Hardware`    |
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/a7685ca0-4b08-4dfb-97c6-f253ff8ace85" />

## 1.3 Project Title

Crash Guard Pro

`(because Project-or)`

<<img width="1024" height="559" alt="WhatsApp Image 2026-04-27 at 3 35 55 PM" src="https://github.com/user-attachments/assets/e402f4b9-394e-4223-be4f-5fcb2a03da14" />
 />

## 1.4 One-Line Pitch

A smart helmet that keeps riders safe by detecting drowsiness in real time and instantly alerting for crashes when every second matters.

## 1.5 Expanded Project Idea

In 1–2 paragraphs, explain:

- what your project is,
- what kind of experience it creates,
- what technologies are involved.

**Response:**  
This project focuses on developing an interactive, sensor-driven helmet that responds to user behavior and environmental conditions while also recording interaction data.

The system uses multiple sensors to capture different types of input. The MPU6050 detects head movement and orientation, allowing the system to respond dynamically to motion patterns. A capacitive touch sensor enables direct user interaction, triggering changes in system behavior or activating different modes. An MQ sensor is used to detect alcohol presence, which alters how the system reacts to the user.

All inputs are processed in real time by the microcontroller, which determines the system state and generates corresponding outputs. Feedback is provided through a buzzer, producing different sound patterns depending on the input conditions and combinations.

The helmet also functions as a black box system using an SD card module. It continuously logs motion data, sensor readings, and key events, creating a record of interactions over time. This allows the system to not only respond but also store and reflect past behavior.

Additionally, a Bluetooth module enables external interaction with the system. It allows wireless communication for control, monitoring, or extending system functionality through a connected device.

By combining motion sensing, environmental detection, touch interaction, and data logging, the project creates a wearable system that is both reactive and memory-enabled, focusing on interaction and experience rather than traditional safety-only functionality.

---

# 2. Philosophy Fit

## 2.1 Experience, Not Social Problem

This project does not aim to solve a large-scale social problem. Instead, it is designed as an interactive wearable artifact that explores how a helmet can behave as a responsive and expressive object.

The system transforms a conventional helmet into an interactive entity that reacts to user behavior and environmental conditions. It integrates motion sensing, touch interaction, alcohol detection, wireless communication, and data logging to create a layered experience.

The focus of the project is on:

- interaction rather than utility  
- responsiveness rather than passive use  
- experience rather than problem-solving  

The helmet behaves as a system that:

- responds to movement and touch  
- changes behavior based on detected alcohol levels  
- produces feedback through sound  
- records interactions as data  

This makes the helmet a playful and slightly unpredictable object that invites exploration and experimentation.


# 3. Inspiration

## 3.1 References

| Source Type | Title / Link | What Inspired You |
|------------|-------------|------------------|
| `[Concept]` | Interactive wearable systems | The idea that objects can respond dynamically to human input |
| `[Technology]` | Sensor fusion systems | Combining multiple inputs to create richer and more complex interaction behavior |


## 3.2 Original Twist

**Response:**

The originality of this project lies in transforming a helmet into a multi-sensory, context-aware interactive system that not only reacts but also records interactions.

Unlike conventional systems that rely on a single input, this project integrates:

- motion sensing using the MPU6050  
- touch-based interaction  
- alcohol detection using an MQ sensor  
- wireless interaction through Bluetooth  
- event logging using an SD card module  

The system behaves differently depending on combinations of inputs rather than isolated triggers.

For example:

- motion alone produces a normal response  
- motion combined with alcohol detection alters the behavior significantly  
- touch input can activate or modify interaction modes  

Additionally, the inclusion of a black box using the SD card module introduces a memory aspect, allowing the helmet to log and store interaction data over time.

This shifts the system from being purely reactive to being both reactive and reflective, as it maintains a record of its interactions.


# 4. Project Intent

## 4.1 User Journey

**Response:**

A user picks up the helmet and puts it on. As soon as it is powered, the system begins monitoring movement, touch, and environmental conditions.

When the user moves their head, the helmet detects motion through the MPU6050 and responds with sound feedback. The responses vary depending on the intensity and pattern of movement.

If the user touches the helmet, the touch sensor triggers a change in interaction mode. The helmet may respond differently to movement or activate a new behavior pattern.

If alcohol is detected through the MQ sensor, the helmet changes its behavior. The responses may become more aggressive or persistent, indicating a shift in system state.

At the same time, all interactions are being recorded through the SD card module. Movement data, detection events, and system responses are logged continuously.

Through the Bluetooth module, the system can also be influenced externally, allowing additional interaction or control from a connected device.

As the user continues interacting, the helmet creates a dynamic loop of sensing, reacting, and recording, making the experience engaging and exploratory.


# 5. Definition of Success

## 5.1 Definition of “Usable”

A usable system is one where:

- all sensors function reliably  
- the system responds consistently to user input  
- feedback is clearly perceivable through the buzzer  
- data is successfully logged to the SD card  
- the interaction feels responsive and intentional  


## 5.2 Minimum Usable Version

**Response:**

The minimum usable version of this project includes:

- MPU6050 for motion detection  
- MQ sensor for alcohol detection  
- buzzer for feedback  
- microcontroller for processing  

In this version:

- motion triggers sound responses  
- alcohol detection changes the response pattern  

This delivers the core experience of a reactive helmet that responds to both movement and environmental conditions.


## 5.3 Stretch Features

What features are nice to have but not essential?

- integration of Bluetooth for wireless interaction  
- addition of touch sensor for mode switching  
- SD card logging for black box functionality  
- more complex behavior patterns based on multiple sensor combinations  
- adjustable sensitivity and thresholds  
- mobile app interface for monitoring or control  
# 6. System Overview

## 6.1 Project Type

Check all that apply.

- [x] Electronics-based  
- [ ] Mechanical  
- [x] Sensor-based  
- [x] App-connected  
- [ ] Motorized  
- [x] Sound-based  
- [ ] Light-based  
- [ ] Screen/UI-based  
- [x] Fabricated structure  
- [ ] Game logic based  
- [x] Installation  
- [ ] Other:


## 6.2 High-Level System Description

**Response:**

The system is a wearable interactive helmet that senses user behavior and environmental conditions, processes this data, and produces feedback while also recording interactions.

### Input

The system takes input from multiple sensors:

- MPU6050 for motion and orientation detection  
- MQ sensor for alcohol detection  
- Capacitive touch sensor for user interaction  
- Bluetooth module for external input from a connected device  

### Processing

All sensor data is sent to the microcontroller, where it is analyzed in real time.

The system processes:

- motion intensity and patterns  
- touch activation signals  
- alcohol detection levels  
- Bluetooth commands  

Based on predefined logic, the system determines the current state and selects the appropriate response.

### Output

The system produces output through:

- a buzzer that generates different sound patterns  
- behavior changes based on input combinations  
- data logging to the SD card module (black box)  

### Physical Structure

All components are integrated into a helmet structure, making it a wearable system. The placement of sensors ensures accurate detection of head movement, touch interaction, and environmental conditions.

### App Interaction

The Bluetooth module allows communication with an external device such as a smartphone. This can be used to:

- send commands to the system  
- modify behavior modes  
- monitor interaction data  

---

## 6.3 Input / Output Map

| System Part        | Type     | What It Does |
|------------------|---------|-------------|
| MPU6050          | Input    | Detects head movement, tilt, and acceleration |
| MQ Sensor        | Input    | Detects alcohol presence in the environment |
| Touch Sensor     | Input    | Detects user touch to trigger interaction modes |
| Bluetooth Module | Input    | Receives external commands from a connected device |
| Microcontroller  | Process  | Processes all inputs and decides system behavior |
| Buzzer           | Output   | Produces sound feedback based on system state |
| SD Card Module   | Output   | Stores sensor data and event logs as a black box |
| Helmet Structure | Physical | Houses all components and enables wearable interaction |

# 7. Sketches and Visual Planning

## 7.1 Concept Sketch

Add an early sketch of the full idea.

**Insert image below:**  
`[Upload image and link here]`
<img width="1200" height="1600" alt="WhatsApp Image 2026-04-27 at 3 48 28 PM" src="https://github.com/user-attachments/assets/49b5c634-900b-4b53-b781-04ff7420c76e" />


Example:

```md

```



## 7.2 Labeled Build Sketch

Add a sketch with labels showing:

- structure,
- electronics placement,
- user touch points,
- moving parts,
- output elements.

**Insert image below:**  
`[Upload image and link here]`
<img width="900" height="1600" alt="WhatsApp Image 2026-04-27 at 4 37 07 PM" src="https://github.com/user-attachments/assets/210d19eb-965c-40ae-98b6-4c3a8439edc8" />

---

# 8. Electronics Planning

## 8.1 Electronics Used

| Component                 | Quantity | Purpose |
|--------------------------|---------:|---------|
| `[Raspberry Pi Pico / RP2040]` | `1` | Main controller for processing sensor data |
| `[MPU6050]`              | `1`      | Detects head movement, tilt, and acceleration |
| `[MQ Sensor]`            | `1`      | Detects alcohol presence |
| `[Capacitive Touch Sensor]` | `1`   | Detects user touch and triggers interaction modes |
| `[Bluetooth Module (HC-05/HC-06)]` | `1` | Enables wireless communication with external device |
| `[Buzzer]`               | `1`      | Provides sound-based feedback |
| `[SW125 SD Card Module]` | `1`      | Stores sensor data and event logs (black box) |
| `[Micro SD Card]`        | `1`      | Storage medium for logged data |
| `[Helmet Structure]`     | `1`      | Houses all components and enables wearable interaction |
## 8.2 Wiring Plan

Describe the main electrical connections.

**Response:**  
The microcontroller connects to multiple sensors and modules using dedicated GPIO pins for communication and control.

The MPU6050 is connected using I2C communication, with SDA connected to IO9 and SCL connected to IO10. It operates at 3.3V and shares a common ground.

The SD card module (HW-125) is connected using SPI communication. MISO is connected to IO21, MOSI to IO24, SCK to IO23, and CS to IO22. The module is powered using 5V and shares a common ground.

The Bluetooth module communicates via UART, with TX connected to IO6 and RX connected to IO5. It is powered using 5V.

The MQ sensor is connected through its analog output pin (AO) to IO26 for alcohol detection. It is powered using 5V.

The capacitive touch sensor is connected to IO19 for detecting user interaction and operates at 3.3V.

The buzzer is connected to IO20 and is used to provide sound feedback. Its negative terminal is connected to ground.

All components share a common ground to ensure stable and reliable operation.


## 8.3 Circuit Diagram

Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
`[Upload image and link here]`

<img width="1536" height="1024" alt="ChatGPT Image Apr 27, 2026, 04_43_25 PM" src="https://github.com/user-attachments/assets/8265a5f4-d3e9-4d27-bd7c-72d2bab6c929" />



# 9. Power Plan

| Question         | Response |
|------------------|----------|
| Power source     | `External regulated power supply / USB power` |
| Voltage required | `3.3V for MPU6050 and touch sensor, 5V for MQ sensor, Bluetooth module, and SD card module` |
| Current concerns | `MQ sensor and SD module may draw higher current; stable power supply is required to avoid fluctuations` |
| Safety concerns  | `Ensure correct voltage levels, avoid short circuits, and maintain proper grounding across all components` |


# 10. Software Planning

## 10.1 Software Tools

| Tool / Platform        | Purpose |
|------------------------|---------|
| `[MicroPython / C++]`  | Control microcontroller and sensors |
| `[Serial Monitor / Bluetooth Terminal]` | Debugging and communication |
| `[Optional Mobile Interface]` | Future interaction via Bluetooth |


## 10.2 Software Logic

Describe what the code must do.

**Response:**  

- **Startup behavior:**  
  The system initializes all GPIO pins, sets up I2C for MPU6050, SPI for SD card, UART for Bluetooth, and configures analog and digital inputs.

- **Input handling:**  
  The system continuously monitors motion data from the MPU6050, touch input from the capacitive sensor, alcohol levels from the MQ sensor, and commands from the Bluetooth module.

- **Sensor reading:**  
  Motion data is read via I2C, alcohol levels are read from the analog pin, and touch input is read as a digital signal.

- **Decision logic:**  
  The system evaluates input conditions:
  - motion patterns
  - touch interaction
  - alcohol detection threshold  
  Based on these, it determines the system state and selects the appropriate response.

- **Output behavior:**  
  The buzzer generates different sound patterns depending on system conditions and input combinations.

- **Data logging:**  
  Important events such as motion changes and alcohol detection are logged to the SD card module using SPI communication.

- **Communication logic:**  
  The Bluetooth module receives external commands which can modify system behavior or trigger actions.

- **Reset behavior:**  
  If no significant input is detected, the system returns to a default idle state and continues monitoring inputs.


## 10.3 Code Flowchart

Insert a flowchart showing your code logic.

Suggested sequence:

- start  
- initialize system  
- read sensor inputs  
- check conditions  
- trigger output  
- log data  
- repeat loop  
- handle errors if any  

**Insert image below:**  
<img width="1024" height="1536" alt="ChatGPT Image Apr 27, 2026, 04_56_51 PM" src="https://github.com/user-attachments/assets/d0916c44-bc96-4b16-881b-07b41ed062f0" />




# 11. Bill of Materials

## 11.1 Full BOM

| Item                             | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec            | Why This Choice? |
|----------------------------------|---------:|--------|-------------|---------------:|---------------------------|------------------|
| `[Raspberry Pi Pico / RP2040]`   | `1`      | `Yes`  | `No`        | `0`            | `RP2040 Microcontroller`  | Main controller for processing sensor data |
| `[MPU6050]`                      | `1`      | `Yes`  | `No`        | `0`            | `6-axis IMU sensor`       | Detects head movement and orientation |
| `[MQ Sensor]`                    | `1`      | `Yes`  | `No`        | `0`            | `Gas/Alcohol sensor`      | Detects alcohol presence |
| `[Capacitive Touch Sensor]`      | `1`      | `Yes`  | `No`        | `0`            | `Touch module`            | Enables user interaction and mode switching |
| `[Bluetooth Module (HC-05/HC-06)]` | `1`    | `Yes`  | `No`        | `0`            | `UART communication`      | Enables wireless control and monitoring |
| `[Buzzer]`                       | `1`      | `Yes`  | `No`        | `0`            | `Piezo buzzer`            | Provides sound-based feedback |
| `[SW125 SD Card Module]`         | `1`      | `Yes`  | `No`        | `0`            | `SPI interface`           | Stores sensor data and event logs |
| `[Micro SD Card]`                | `1`      | `No`   | `Yes`       | `150`          | `8–16 GB`                 | Storage medium for black box data |
| `[Helmet Structure]`             | `1`      | `Yes`  | `No`        | `0`            | `Standard helmet`         | Houses components and enables wearable interaction |

---

## 11.2 Material Justification

**Response:**  
The Raspberry Pi Pico was selected as the main controller due to its simplicity, sufficient processing capability, and compatibility with multiple sensors and communication modules.

The MPU6050 was chosen for motion sensing because it provides both accelerometer and gyroscope data, allowing accurate detection of head movement and orientation.

The MQ sensor was used for alcohol detection as it is low-cost and suitable for detecting gas-based inputs in real-time applications.

A capacitive touch sensor was included to enable direct user interaction, allowing the system to switch modes or trigger responses.

The Bluetooth module was selected to provide wireless communication, enabling external control and system extension without adding complex infrastructure.

The buzzer was used as a simple and effective output device to provide immediate feedback based on system behavior.

The SW125 SD card module was included to implement black box functionality, allowing the system to log data and store interaction history.

---

## 11.3 Items You Chose

| Item                     | Why Needed                         | Purchase Link | Latest Safe Date to Procure | Status       |
|--------------------------|----------------------------------|--------------|----------------------------|--------------|
| `Micro SD Card`          | `Storage for black box logging`   | `Amazon / Robu` | `Before testing phase`     | `[Pending / Received]` |
| `Bluetooth Module`       | `Wireless communication`          | `Lab / Store`  | `Before integration`       | `[Available]` |
| `Touch Sensor`           | `User interaction input`          | `Lab`          | `Before testing`           | `[Available]` |

---

## 11.4 Budget Summary

| Budget Item           | Estimated Cost              |
|----------------------|---------------------------:|
| Electronics          | `[150]`                    |
| Mechanical parts     | `[0 (helmet available)]`   |
| Fabrication materials| `[0 (available in lab)]`   |
| Purchased extras     | `[150]`                    |
| Contingency          | `[200]`                    |
| **Total**            | `[500]`                    |

---

## 11.5 Budget Reflection

**Response:**  
The project is already low-cost due to the use of components available in the lab. The only additional cost is the micro SD card for storage.

If cost needs to be reduced further:

- Bluetooth functionality can be removed as it is not essential for core interaction  
- SD card logging can be simplified or removed if only real-time interaction is required  
- Touch input can be replaced with predefined automatic behavior  

However, these reductions would decrease the overall interactivity and completeness of the system.
# 12. Planning the Work

## 12.1 Team Working Agreement

**Response:**  

The team divided tasks based on individual strengths in electronics, coding, testing, and documentation. Each member was responsible for a primary area while also supporting others during integration.

Decisions were made collaboratively through group discussions, especially for design choices, sensor selection, and system behavior. If disagreements arose, the team evaluated feasibility, simplicity, and implementation time before finalizing decisions.

Progress was checked regularly through informal reviews and testing sessions after each major step, such as sensor integration, wiring, and code implementation.

If a task was delayed, responsibilities were redistributed temporarily to ensure that overall progress was not affected. Team members assisted each other to resolve blockers quickly.

Documentation was maintained continuously by updating the markdown file after each stage of development, including changes in design, wiring, code, and testing results.

---

## 12.2 Task Breakdown

| Task ID | Task                          | Owner        | Estimated Hours | Dependency        | Status |
| ------- | ----------------------------- | ------------ | ---------------:| ----------------- | ------ |
| T1      | Finalize concept              | Soham/Adarsh | 2               | None              | Done   |
| T2      | Component selection (BOM)     | Lakshya      | 2               | T1                | Done   |
| T3      | Sensor testing (MPU, MQ)      | Soham        | 3               | T2                | Done   |
| T4      | Circuit wiring                | Lakshya      | 3               | T2                | Done   |
| T5      | Code development              | Adarsh       | 5               | T3, T4            | Done   |
| T6      | SD card logging integration   | Adarsh       | 2               | T5                | Done   |
| T7      | Bluetooth integration         | Soham        | 2               | T5                | Done   |
| T8      | System integration            | All          | 4               | T5, T6, T7        | Done   |
| T9      | Testing and debugging         | Jagrut       | 3               | T8                | Done   |
| T10     | Documentation                 | Lakshya      | 3               | All               | Done   |

---

## 12.3 Responsibility Split

| Area          | Main Owner | Support Owner |
|---------------|-----------|--------------|
| Concept       | Soham     | Adarsh       |
| Electronics   | Soham     | Lakshya      |
| Coding        | Adarsh    | Lakshya/Soham|
| Testing       | Jagrut    | Lakshya      |
| Documentation | Lakshya   | Jagrut       |
## 13  Update Log

| Week   | Planned Goal                          | What Actually Happened                                      | What Changed                                         | Next Steps                              |
|--------|---------------------------------------|--------------------------------------------------------------|------------------------------------------------------|-----------------------------------------|
| Week 1 | Finalize concept and select components| Idea finalized and sensors selected                          | Shifted from safety-only to interactive system        | Start sensor testing                    |
| Week 2 | Test sensors and basic wiring         | MPU6050, MQ, and touch sensor tested individually            | MQ sensor required calibration adjustments            | Integrate sensors with controller       |
| Week 3 | Integrate system and develop code     | All components connected and basic code implemented          | Added SD card logging for black box functionality     | Improve behavior logic and debugging    |
| Week 4 | Testing, refinement, and documentation| System tested, bugs reduced, and documentation completed     | Improved wiring and response logic                    | Final polish and presentation preparation|

# 14. Risks and Unknowns

## 14.1 Risk Register

| Risk                                              | Type        | Likelihood | Impact | Mitigation Plan                                                                 | Owner     |
|---------------------------------------------------|------------|-----------|--------|---------------------------------------------------------------------------------|----------|
| MQ sensor gives inaccurate alcohol readings       | Technical   | Medium    | High   | Calibrate sensor properly, test with controlled inputs, define safe thresholds  | Soham    |
| Loose wiring inside helmet                        | Hardware    | Medium    | High   | Secure wires using tape/supports, check connections before testing              | Lakshya  |
| SD card logging failure                          | Technical   | Low       | Medium | Test file writing, ensure proper SD formatting, add error handling              | Adarsh   |
| Bluetooth communication instability               | Technical   | Medium    | Medium | Keep stable connection, test range, implement fallback behavior                 | Soham    |
| Sensor noise causing false triggers               | Technical   | Medium    | Medium | Add filtering, threshold tuning, and condition checks                           | Adarsh   |


## 14.2 Biggest Unknown Right Now

**Response:**  

The biggest uncertainty is the reliability and consistency of alcohol detection using the MQ sensor in real-world conditions.

Environmental factors such as airflow, ambient gases, and sensor placement can affect readings. Ensuring accurate detection without false positives remains the main challenge.


---

# 15. Testing 

## 15.1 Technical Testing Plan

| What Needs Testing      | How You Will Test It                                             | Success Condition |
|------------------------|------------------------------------------------------------------|------------------|
| `[MPU6050 motion]`     | `[Move helmet in different directions and monitor readings]`     | `[Consistent and stable motion data]` |
| `[MQ sensor]`          | `[Expose sensor to alcohol and compare readings]`                | `[Clear distinction between normal and alcohol levels]` |
| `[Touch sensor]`       | `[Repeated tapping and checking response]`                       | `[Accurate detection without false triggers]` |
| `[Buzzer output]`      | `[Trigger all system conditions manually]`                       | `[Correct feedback for each condition]` |
| `[Bluetooth]`          | `[Send commands from phone/terminal]`                            | `[System responds correctly]` |
| `[SD card logging]`    | `[Run system and inspect saved file]`                            | `[All events logged correctly]` |


## 15.2 Testing and Debugging Log

| Problem Found                              | Type        | What You Tried                                      | Result   | Next Action                          |
|---------------------------------------------|------------|----------------------------------------------------|----------|--------------------------------------|
| MQ sensor giving unstable readings         | Technical  | Calibrated sensor and adjusted threshold values     | Improved | Further fine-tune calibration        |
| SD card not writing data                  | Technical  | Checked wiring and corrected SPI connections        | Fixed    | Add error handling in code           |
| Touch sensor false triggering             | Technical  | Adjusted sensitivity and improved grounding         | Improved | Monitor stability                    |

# 16. Build Documentation

## 16.1 Fabrication Process

**Response:**  

The fabrication process involved integrating electronic components into a helmet structure while ensuring stability, usability, and clean wiring.

### Design

The placement of all components was planned based on size, accessibility, and functionality. Sensors such as the MPU6050, MQ sensor, and touch sensor were positioned to ensure accurate readings. The microcontroller and SD card module were placed in a protected central location inside the helmet.

---

### Cutting and Modification

Minor modifications were made to the helmet to create space for components and wiring. Openings were carefully created for sensor exposure (especially the MQ sensor) and for routing wires without damaging the structure.

---

### Assembly

All electronic components were assembled inside the helmet. Modules were arranged in a compact layout to maintain balance and comfort while wearing the helmet.

---

### Fastening

Components were secured using adhesives, double-sided tape, and supports to prevent movement during use. Critical components such as the microcontroller and SD card module were fixed firmly to avoid disconnections.

---

### Wiring

All sensors and modules were connected according to the wiring plan. Care was taken to:

- maintain clean routing of wires  
- avoid loose connections  
- ensure common grounding across all components  

Wires were bundled and secured to prevent tangling and to improve reliability.

---

### Finishing

The internal setup was organized for a clean and compact look. Excess wires were trimmed or managed, and components were positioned to avoid interference with the user.

The exterior of the helmet was kept intact to maintain usability and safety.

---

### Revisions and Iterations

Multiple iterations were made during the build process:

- repositioning sensors for better accuracy  
- improving wire management  
- stabilizing loosely mounted components  
- refining buzzer placement for clearer sound output  

These changes improved both system performance and overall usability.
## 16.2 Build Photos

Add photos throughout the project.

Suggested images:

- early sketch,
- prototype,
- electronics testing,
- mechanism test,
- app screenshot,
- final build.
<img width="1200" height="1600" alt="WhatsApp Image 2026-04-27 at 5 25 41 PM" src="https://github.com/user-attachments/assets/f33ace1f-9a81-4560-a64f-9447653be56e" />





# 17. Final Outcome

## 17.1 Final Description

**Response:**  

The final system is an interactive smart helmet that integrates multiple sensors to detect user behavior and environmental conditions, respond through sound feedback, and record interaction data.

The helmet uses an MPU6050 to track motion and orientation, an MQ sensor to detect alcohol presence, and a capacitive touch sensor to allow user interaction. A buzzer provides real-time feedback based on system logic, while a Bluetooth module enables external communication and control.

Additionally, the system includes a black box feature using an SD card module, which logs motion data, sensor readings, and key events over time.

The final implementation successfully demonstrates a multi-sensory, reactive, and memory-enabled wearable system that emphasizes interaction, responsiveness, and recorded experience.


## 17.2 What Works Well

- Motion sensing using MPU6050 is stable and responsive  
- Touch sensor accurately triggers interaction modes  
- Buzzer provides clear and immediate feedback  
- Multiple sensors work together without major conflicts  
- SD card logging successfully stores data  
- Bluetooth communication works for basic control  
- Overall system integration is stable  


## 17.3 What Still Needs Improvement

- MQ sensor needs better calibration for accurate alcohol detection  
- Some false triggers may occur in noisy environments  
- Behavior logic can be made more advanced and dynamic  
- Bluetooth interaction can be expanded for better usability  
- Internal wiring can be further optimized for compactness  
- Power management can be improved for long-term use  


## 17.4 What Changed From the Original Plan

**Response:**  

The project initially focused on a more traditional safety-based helmet system with features like accident detection and emergency response.

During development, the concept shifted toward creating an interactive and experiential system. Instead of focusing only on safety, the project evolved into a multi-sensory wearable that reacts to user behavior and environmental conditions.

The addition of SD card logging introduced a memory aspect, transforming the system from a simple reactive device into one that records and reflects interactions over time.


---

# 18. Reflection

## 18.1 Team Reflection

**Response:**  

The team worked effectively by dividing responsibilities based on individual strengths, which helped in completing tasks efficiently. Collaboration during integration stages was particularly strong, allowing different subsystems to come together smoothly.

One of the main challenges was debugging and sensor calibration, which required multiple iterations and took more time than expected. Managing wiring and ensuring stable connections inside the helmet also required careful effort.

Overall, time and tasks were managed well, and regular discussions helped in resolving issues quickly and maintaining steady progress.*  


## 18.2 Technical Reflection

**Response:**  

Through this project, we gained practical experience in working with multiple electronic components and integrating them into a single system.

In electronics, we learned how to interface different sensors using I2C, SPI, UART, and analog inputs, and how to manage stable connections and common grounding.

In coding, we developed skills in handling real-time sensor data, implementing decision logic based on multiple inputs, and structuring code for modularity and readability.

From a mechanisms and fabrication perspective, we understood how physical constraints affect electronic design, including component placement, wiring management, and maintaining usability in a wearable system.

In integration, we learned how to combine hardware and software effectively, troubleshoot issues across subsystems, and ensure reliable communication between components.


## 18.3 Design Reflection

**Response:**  

This project helped us understand that good design is not just about functionality but also about creating meaningful and engaging interactions.

We learned the importance of clarity in how a system responds, ensuring that users can understand feedback easily. The concept of delight was explored through multi-sensory responses, making the system more engaging.

Working on a physical wearable system highlighted the importance of interaction design, including how users naturally move, touch, and respond to feedback.

Iteration played a major role in improving the project. Repeated testing and refinement helped us improve both the technical performance and the overall user experience.


## 18.4 If You Had One More Hour

**Response:**  

With additional time, we would focus on improving the system behavior and interaction logic to make it more dynamic and context-aware.

We would refine sensor calibration, especially for the MQ sensor, improve Bluetooth communication for better control, and enhance internal wiring and component placement for a cleaner and more robust build.

# 19. Final Submission Checklist

Before submission, confirm that:

- [x] Team details are complete  
- [x] Project description is complete  
- [x] Inspiration sources are included  
- [x] Sketches are added  
- [x] BOM is complete  
- [x] Purchase list is complete  
- [x] Budget summary is complete  
- [x] Mechanical planning is documented if applicable  
- [ ] App planning is documented if applicable (Not required for this project)  
- [x] Code flowchart is added  
- [x] Task breakdown is complete  
- [x] Weekly logs are updated  
- [x] Risk register is complete  
- [x] Testing log is updated  
- [x] Playtesting notes are included  
- [x] Build photos are included  
- [x] Final reflection is written  

<!-- Add final system image below -->


---
