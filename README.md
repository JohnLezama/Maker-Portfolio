# Maker Portfolio

## About

I’m John Lezama, an incoming Electrical and Computer Engineering student at The University of Texas at Austin and a member of the Robotics Honors and Engineering Honors programs.

I enjoy taking projects through the complete engineering process. From research, simulation, and CAD to PCB design, fabrication, programming, and physical testing. I’m looking forward to collaborating with ambitious individuals and developing technology with measurable real-world impact.

---

## Key Projects

### 4-Channel EMG Wearable Forearm Brace

**Objective:** Develop a low-cost wearable brace capable of reading four EMG channels from the forearm with reduced noise for future grip classification.

**Role:** Independent project — sole designer and builder

**Skills:** PCB design, circuit simulation, KiCad, soldering, CAD, 3D printing, sEMG electrodes, filtering and noise reduction, C++, ESP32

#### Key Contributions

- Designed, simulated, and fabricated custom PCBs that amplified differential EMG signals while filtering noise through an instrumentation amplifier, low-pass filter, and high-pass filter.
- Designed, simulated, and fabricated a driven-right-leg circuit to reduce common-mode noise.
- Designed and 3D-printed a wearable forearm brace that housed the electronics and maintained skin contact for nine electrodes.
- Integrated the completed hardware with an ESP32 to acquire and display all four EMG channels in real time.

**Outcome:** Produced a functional wearable prototype that acquires and displays four simultaneous EMG channels with observable responses to hand and finger movements.

https://github.com/user-attachments/assets/b025411b-7611-4da0-8478-ce82f77846c4

[View Project Repository](PROJECT_URL)

---

### Low-Cost Full-Arm Prosthesis

**Objective:** Design a low-cost, hand-to-shoulder prosthetic arm capable of approximating human range of motion while carrying functional payloads.

**Role:** Independent project — sole designer and builder

**Skills:** CAD, 3D printing, assembly, cable management, cycloidal drive design, EMG sensing

#### Key Contributions

- Designed and fabricated approximately 50 custom parts for the hand, wrist, elbow, shoulder, and support structure.
- Developed a humanoid hand capable of grasping and holding objects through servo-driven curling mechanisms.
- Implemented EMG control that activated the arm’s mechanisms when activity was detected in major muscle groups.
- Incorporated cycloidal drives and managed the mechanical, electrical, and cable-routing requirements across the full arm.

**Outcome:** Completed a 6.11-pound prototype for $373.97. The prosthesis incorporated five arm degrees of freedom and five independently articulated fingers. The hand could hold a 7.5-pound dumbbell, while the arm could perform a 4-pound bicep curl and a 4-pound lateral raise.

<img width="320" height="600" alt="ProstheticArm" src="https://github.com/user-attachments/assets/a1e0ff1e-4427-426a-b407-3298f779a4cb" />
 ![Demo](https://github.com/JohnLezama/Maker-Portfolio/blob/main/Assets/ForearmTestProstheticArm.gif)


[View Project Repository](PROJECT_URL)

---

### Discovering Optimal Zeolites for Post-Combustion Carbon Capture

**Objective:** Evaluate whether theoretical zeolite structures could outperform current industry standards by combining Monte Carlo simulations, geometry optimization, and an automated Java and Bash pipeline.

**Role:** Independent research project — sole researcher and developer

**Skills:** Grand Canonical Monte Carlo simulation, Avogadro, Java, Bash, computational chemistry, force-field modeling, research, data analysis

#### Key Contributions

- Programmed an automated simulation pipeline using Java and Bash scripts to prepare, run, and process simulations.
- Researched force fields and tested multiple simulation configurations to improve the accuracy and consistency of the results.
- Generated 81 zeolite configurations across nine frameworks and nine silicon-to-aluminum ratios.
- Analyzed adsorption capacity, CO₂/N₂ selectivity, working capacity, and heat of adsorption to identify the strongest candidates.

**Outcome:** Among the frameworks tested, Na-RWY and Na-JSR zeolites with Si/Al ratios of 1.0 outperformed industry-standard zeolites. Na-RWY achieved the highest adsorption and working capacities at 6.97 mmol/g and 5.54 mmol/g, respectively. Na-JSR also performed strongly, reaching 5.48 mmol/g and 2.90 mmol/g.

The study was published in the *National High School Journal of Science* and has received more than 1,000 article views.

<!-- Add: Results figure or cropped results section -->

[Read the Published Study](PUBLICATION_URL) · [View Project Repository](PROJECT_URL)

---

### Pencil Printer

**Objective:** Build a CNC drawing machine that converts digital images into physical pencil drawings using Python image processing and motor control.

**Role:** Independent project — sole designer and builder

**Skills:** Python, C++, image processing, CAD, Arduino, 3D printing, mechanical assembly

#### Key Contributions

- Designed, 3D-printed, and assembled a three-axis CNC machine using stepper motors and a servo-controlled pencil mechanism.
- Programmed a Python and C++ workflow to detect image edges, map coordinates, and calculate motor instructions for the pencil.
- Created a custom G-code-style format and integrated a microSD card to transfer instructions from a laptop to the machine.

**Outcome:** Successfully converted digital images into physical pencil drawings. The complete workflow was demonstrated using an Iron Man mask image, progressing from the original image and processed edge map to the machine drawing the final result.

<!-- Add: Original image → processed edge map → drawing timelapse → finished drawing -->

[View Project Repository](PROJECT_URL)

---

### ReConnected — A Medication Adherence System

**Objective:** Develop a physical pill dispenser and companion web application designed to encourage medication adherence through positive reinforcement.

**Role:** Hardware lead — responsible for the physical dispenser and electronics; project partner responsible for the web application

**Skills:** CAD, 3D printing, Arduino, electronics, Bluetooth integration, mechanical design, assembly, collaboration

#### Key Contributions

- Designed, fabricated, and assembled the motorized pill dispenser.
- Wired the dispenser and designed the electronics required to interface it with the companion web application.

**Outcome:** Completed the physical dispenser and a companion web-application prototype. The application was designed to create medication schedules, issue dispenser commands, and incorporate positive-reinforcement features. The project did not include end-to-end or user testing, so no conclusions were made about its effect on medication adherence.

<!-- Add: Video of the dispensing mechanism -->

[View Project Details](PROJECT_URL)

---

## Other Projects

### Trash-Collecting Boat

**Objective:** Design a remote-controlled boat capable of removing plastic waste from my local pond.

**Skills:** CAD, 3D printing, wireless communication, Arduino

**Result:** Produced a functional prototype that could navigate through water and scoop floating plastic bottles.

<!-- Add: GIF or video of the boat moving and collecting bottles -->

[View Project Details](PROJECT_URL)

---

### Life-Sized Car

**Objective:** Build a full-scale wooden vehicle capable of driving under remote control.

**Skills:** Woodworking, CAD, mechanical assembly, power systems

**Result:** Completed a functional full-scale prototype capable of driving under its own power and remote control. The prototype was not capable of carrying a person.

<!-- Add: GIF or video of the car driving -->

[View Project Details](PROJECT_URL)

---

### Automated Package-Handling System

**Objective:** Design a vending-machine-style mechanism to automate package-delivery drop-offs.

**Skills:** Woodworking, CAD, mechanical assembly, Arduino

**Result:** Built a roughly 2 × 3-foot machine that translated an electromagnet along the X, Y, and Z axes to retrieve packages and place them into designated slots.

<!-- Add: GIF or video of the machine operating -->

[View Project Details](PROJECT_URL)

---

## Experience

### FIRST Robotics — Mechanical Lead

**September 2024 – May 2025**

- Contributed to the prototyping and mechanical assembly of the competition robot.
- Developed and presented mechanical training lessons for new team members.
- Led more than 30 students in constructing full-scale field elements.

**Skills:** Leadership, machining, assembly, prototyping

<!-- Add: GIF or video of the competition robot -->

---

### Learn@STEM — Founder

**October 2024 – May 2025**

- Founded a high school club that developed and presented STEM activities for local middle school students.
- Traveled to a local middle school after school to teach lessons in person.
- Introduced students to CAD, programming, 3D printing, electronics, and Arduino.

**Skills:** Leadership, presentation, instruction, Onshape, 3D printing, electronics

<!-- Add: Images from Learn@STEM activities -->

---

### BlueSKY — Engineering Intern

**June 2025 – August 2025**

- Conducted airflow experiments on industrial filtration equipment.
- Wired production machines during periods of increased demand.
- Created customer-facing CAD drawings using Alibre.
- Gained experience with industrial pneumatics, production work, and engineering collaboration.

**Skills:** Active listening, CAD with Alibre, electronics, prototyping

<!-- Add: Images from the internship -->

---

## Reflection

I enjoy building systems at the intersection of hardware and software, particularly in assistive technology, robotics, and scientific research. These projects have taught me how to move from research and simulation through CAD, fabrication, testing, and iteration. I am excited to bring that experience to ambitious interdisciplinary teams and continue developing technology with measurable real-world impact.


