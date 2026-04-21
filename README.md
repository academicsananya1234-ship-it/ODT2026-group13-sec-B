# Open Design and Technology  
## Final Project README

> **Project Weight:** 70%  
> **Team Size:** 2 students  
> **Project Duration:** 4 weeks  
> **Class Time Available:** 6 hours per class  
> **Total Time Available:** 48 effort-hours per team  
> **Project Type:** Playful, interactive, technology-based experience

---

# Before you begin

## Fork and rename this repository
After forking this repository, rename it using the format:

`ODT-2026-Team13_Ananya_and_Zoya`

### Example
`ODT-2026-PixelWizards`

Do not keep the default repository name.

---

# How to use this README

This file is your team’s **working project document**.

You must keep updating it throughout the 4-week build period.  
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
`[Group 13]`

## 1.2 Team Members

| Name | Primary Role | Secondary Role | Strengths Brought to the Project |
|---|---|---|---|
| Ananya | Electronics & Wiring | Code Troubleshooting | Strong debugging skills, quickly identified and fixed issues in wiring and code, handled failures under pressure, and ensured reliable system integration |
| `[Zoya]` | `[Coding / App / Fabrication / Mechanics]` | `[Electronics ]` | `[Sequencing Logic,Integration,Systems Thinking]` |

## 1.3 Project Title
'Psychedelicacy`

## 1.4 One-Line Pitch
`Card-operated dispenser that detects card swipe via IR sensor, flashes pink loading lights, then swings servo flap open with green confirmation to dispense candy.`

## 1.5 Expanded Project Idea
In 1–2 paragraphs, explain:
- what your project is,
- what kind of playful experience it creates,
- what makes it fun, curious, engaging, strange, satisfying, competitive, or delightful,
- what technologies are involved.

**Response:**
`Psychedelicacy is a playful card-activated dispenser that lights up and swings open to release a surprise treat when you swipe a card past an IR sensor.It captures that exciting "did it work?" moment as the pink lights chase around,building anticipation before green floods in and the flap swings open to drop your treat creating a simple, responsive, and surprisingly addictive moment.
What makes it fun is the playful rhythm: the quick sensor ping, the glowing buildup, and that satisfying servo whirr delivering instant payoff.Each swipe feels like a mini game with reliable magic, sparking curiosity for "one more go." It's powered by an IR sensor for detection,NeoPixel LEDs for vibrant feedback and a servo for smooth delivery of the treat.`

---

# 2. Philosophy Fit

## 2.1 Experience, Not Social Problem
This module does **not** require your project to solve a large social problem.

You are allowed to build:
- toys,
- games,
- interactive objects,
- playful machines,
- kinetic artifacts,
- humorous devices,
- strange but delightful experiences,
- things that are entertaining to use or watch.

## 2.2 What kind of experience are you creating?
Answer the following:
- What is the experience?
- What do you want the player or participant to feel?
- Why would someone want to try it again?

**Response:**  
`The experience is a small, tactile exchange where a person takes a simple action and receives a small treat as a response.It is designed as a playful, hands-on moment rather than just a machine transaction, so the experience feels more like an interaction than a purchase.
The participant should feel curious, amused and rewarded. The goal is to create a light sense of anticipation before the treat arrives, followed by a small burst of satisfaction when it does.
Someone would want to try it again because the experience is quick, easy, and pleasantly repetitive.The combination of curiosity, control and instant reward makes it feel enjoyable each time, almost like a tiny game they can return to.
`

## 2.3 Design Persona
Complete the sentence below:

> We are designing this project as if we are a small creative studio making a **[toy / game / playable object / interactive experience]** for **[children / teens / adults / classmates / exhibition visitors / mixed audience]**.

**Response:**  
`We are designing this project as if we are a small creative studio making a playable object for mixed audience.`

---

# 3. Inspiration

## 3.1 References
List what inspired the project.

| Source Type | Title / Link | What Inspired You |
|---|---|---|
| `Object` | `Vending machine card reader` | `Simple swipe detection creating  "contactless" activation` |
| `Toy` | `Gumball machines	` | `Variable timing builds emotional investment while linear file advances automatically into rotating scoop; copied this for candies naturally sliding into quarter-circle "trap" on servo return which is based on gravity.` |
| `Toy` | `Pez dispensers` | `Head rotates 90° to capture candy from vertical stack, then back releases exactly one; taught how a  quarter-circle depth positioning naturally meters single candies` |

## 3.2 Original Twist
What makes your project original?

**Response:**  
`The dispensing mechanism draws from the PEZ dispenser's single-file candy stacking and the revolver cylinder's rotary chamber logic, but reimagines both in a new way,a quarter-circle servo-driven cavity that uses gravity and hole depth to release exactly one candy per trigger, without springs or complex mechanical parts.Combined with an IR-based card swipe replacing a traditional coin slot, the entire system achieves touchless, one-at-a-time dispensing using just a servo and a sensor , making it simpler, cheaper and more hygienic than any existing consumer dispenser design.`

---

# 4. Project Intent

## 4.1 Core Interaction Loop
Describe the main loop of interaction.

Examples:
- press → launch → score → reset
- connect → control → observe → repeat
- turn → trigger → react → repeat
- move object → sensor detects → sound/light response → player reacts

**Response:**  
`swipe card → IR detects → pink lights animation → green flash + servo dispenses/rotates → servo flap resets + lights off → repeat`

## 4.2 Intended Player / Audience

| Question | Response |
|---|---|
| Who is this for? | `Anyone craving a quick hit of playful delight from everyday spaces-Impulse-driven kids in malls,arcade enthusiasts` |
| Age range | `Age-inclusive - 4 - 60` |
| Solo or multiplayer | `Solo` |
| Expected duration of one round | `4–5 seconds `|
| What should the player feel? | `Enchanting "just one more" compulsion` |
| Is explanation required before use? | `No,intuitive "swipe = reward" can be discovered with the help of card slot placement at the front` |

## 4.3 Player Journey
Describe exactly how a player will use the project.

1. **Approach:** `Notices glowing NeoPixels and queued candies in a desk-sized dispenser`
2. **Start:** `Spots IR sensor slot labeled "Swipe card here →"`
3. **First Action:** `Swipes the card - kept there`
4. **Main Interaction:** `Watches pink "loading" lights chase around ring during 1-second anticipation build`
5. **System Response:** `Green flood lights and servo whirr as quarter-circle pocket rotates 90°, dropping exactly one candy through hole`
6. **Win / Lose / End Condition:** `Not applicable - Candy falls out always`
7. **Reset:** `Flap smoothly returns to 0°, lights turn off, sensor immediately ready for new cycle`

## 4.4 Rules of Play
If your project is a game, list the rules clearly.

- `Not applicable`
- `Not applicable`
- `Not applicable`
- `Not applicable`

---

# 5. Definition of Success

## 5.1 Definition of “Playable”
Your project will be considered complete only if these conditions are met.

- [1] `Card swipe reliably triggers-any card past IR sensor consistently detects within 2cm`
- [1] `Exactly one candy per activation-quarter-circle servo pocket releases single candy every time`
- [1] `Full light show executes-pink loading animation (1s) → green dispense → lights off, all NeoPixels respond instantly without flicker`
- [1] `Smooth mechanical reset-servo returns to 0° position after every dispense, ready for next swipe within 4 seconds total cycle`
- [1] `Runs continuous cycles without sensor false triggers, motor stall or LED failure`

## 5.2 Minimum Viable Version
What is the smallest version of this project that still delivers the core experience?

**Response:**  
`IR sensor detecting motion → single LED blinks → servo rotates 90° to drop one candy → returns to load next`

## 5.3 Stretch Features
What features are nice to have but not essential?

- `Sound effects-  buzzers play jingle or  chime during pink lights, "ka-ching" on dispense`
- `Candy counter display- small screen shows "Candies left: 23" to build urgency as hopper empties`
- `Wireless tally- Bluetooth to phone app tracks swipes or phone motion is used to dispense candy`

---

# 6. System Overview

## 6.1 Project Type
Check all that apply.

- [1] Electronics-based
- [1] Mechanical
- [1] Sensor-based
- [ ] App-connected
- [1] Motorized
- [ ] Sound-based
- [1] Light-based
- [ ] Screen/UI-based
- [1] Fabricated structure
- [ ] Game logic based
- [1] Installation / tabletop experience
- [ ] Other: `[Write here]`

## 6.2 High-Level System Description
Explain how the system works in simple terms.

Include:
- input,
- processing,
- output,
- physical structure,
- app interaction if any.

**Response:**  
`Input: Card swipes break the IR sensor beam (Pin 34 detects proximity/motion).
Processing: ESP32 microcontroller confirms detection with 50ms debounce, then triggers light sequence and servo motion.
Output:
NeoPixel ring (16 LEDs, Pin 2): Pink chasing animation (1s loading) → green flood (dispensing)
Servo motor (Pin 5): Quarter-circle pocket rotates 0°→90°→0° to release exactly one candy
Physical structure: Linear candy queue feeds into deep quarter-circle servo pocket—gravity naturally loads next candy when flap returns to home position.`

## 6.3 Input / Output Map

| System Part | Type | What It Does |
|---|---|---|
| ` Sensor` | Input | `IR sensor detects card swipe by beam interruption` |
| `[ESP32 ` | Processing | `Reads sensor → double-checks signal → runs light sequence → controls servo timing → loops for next activation` |
| `[LED / Servo ` | Output | `Neopixel-Pink chasing animation (loading feedback) → green flood (dispensing confirmation) → off (ready state)/Rotates quarter-circle pocket 0°→90°→0° to scoop and release exactly one candy from queue` |
| `Quarter-circle Candy Pocket` | Physical Action | `Deep pocket traps single candy by geometry; gravity auto-refills from linear queue on return to 0°` |

---

# 7. Sketches and Visual Planning

## 7.1 Concept Sketch
Add an early sketch of the full idea.

**Insert image below:**  
`https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/zoya---branch/images/concept-sketch.jpg`

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
`https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/zoya---branch/images/labelled_build_sketch.jpg`

## 7.3 Approximate Dimensions

| Dimension | Value |
|---|---|
| Length | `35cm` |
| Width | `35cm` |
| Height | `32cm` |
| Estimated weight | `850g` |

---

# 8. Mechanical Planning

## 8.1 Mechanical Features
Check all that apply.

- [1] Gears
- [ ] Pulleys
- [ ] Belt drives
- [ ] Linkages
- [1] Hinges
- [1] Shafts
- [ ] Springs
- [ ] Bearings
- [ ] Wheels
- [1] Sliders
- [ ] Levers
- [ ] Not applicable

## 8.2 Mechanical Description
Describe the mechanism and what it is meant to do.

**Response:**  
`Gear shaft on servo drives quarter-circle pocket as single-index metering chamber-linear candy queue gravity-feeds into deep pocket arc. Servo rotates exactly 90° via hinge mount, sliding card guide aligns pocket hole with exit chute to release trapped candy. Return to 0° naturally scoops next candy from queue via pocket depth geometry + slider mechanism. Pure rotational scoop and gravity reload for reliable single-dispensing.`

## 8.3 Motion Planning
If something moves, explain:
- what moves,
- what causes the movement,
- how far it moves,
- how fast it moves,
- what could go wrong.

**Response:**  
`What moves: Quarter-circle candy pocket attached to servo horn
What causes movement: ESP32 triggers PWM signal to servo motor (Pin 5, 50Hz) after IR sensor confirms card swipe
How far it moves:0° (home, candy loading) → 90° (dispense, hole aligned with chute) → 0° (reset)
Total: 180° per cycle (90° out + 90° back)
How fast it moves:
settle_ms=300ms at 0° (gentle start)
settle_ms=800ms at 90° (allows candy fall)
settle_ms=500ms return to 0° (quick reset)
Total cycle: ~2.1 seconds motion
What could go wrong:
Servo stall/jam—candy too big for pocket depth 
Incomplete return—pocket stays partial-open, double-dispensing 
Backlash—loose servo horn causes sloppy 90° alignment 
Gravity hang-up—next candy doesn't load (solution: slight pocket tilt + vibration from settle delay)`

## 8.4 Simulation / CAD / Animation Before Making
If your project includes mechanical motion, document the digital planning before fabrication.

| Tool Used | File / Link | What Was Tested |
|---|---|---|
| `FIGMA` | `https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/ANANYA-new-branch/images/MECHANICAL%20SERVO%20MOVEMENT.png` | `whether the movement of the servo would be smooth enough to dispense the candy` |

## 8.5 Changes After Digital Testing
What changed after the CAD, animation, or simulation stage?

**Response:**  
`We adjusted the size of the axis accordingly to facilitate the movement of the servo motor`

---
# 9. Electronics Planning

## 9.1 Electronics Used

| Component | Quantity | Purpose |
|---|---:|---|
| ESP32 | 1 | Main controller |
| IR Sensor Module | 1 | Detects CARD insertion |
| NeoPixel Ring (16 LEDs) | 1 | Visual feedback (loading + dispensing) |
| Servo Motor (SG90 or similar) | 1 | Opens and closes dispensing flap |
| External 5V Power Supply | 1 | Powers servo, NeoPixel, and IR sensor |
| Jumper Wires | Multiple | Electrical connections |

---

## 9.2 Wiring Plan

**Response:**  
The ESP32 acts as the central controller. The IR sensor output pin is connected to GPIO 34 (input-only pin) to detect coin insertion. The NeoPixel ring data input (DIN) is connected to GPIO 2 to control LED animations. The servo motor signal wire is connected to GPIO 5 for controlling flap movement.

All components (servo motor, NeoPixel ring, and IR sensor) are powered using an external 5V supply to ensure stable operation and avoid overloading the ESP32. A common ground is maintained by connecting the ground of the power supply to the ESP32 ground and all components.

---

## 9.3 Circuit Diagram

**Insert image below:**  

https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/ANANYA-new-branch/images/CIRCUIT%20DIAGRAM.png


---

## 9.4 Power Plan

| Question | Response |
|---|---|
| Power source | External 5V adapter |
| Voltage required | 5V |
| Current concerns | Servo motor and NeoPixel can draw high current, so external power is required instead of ESP32 5V pin |
| Safety concerns | Ensure correct polarity, avoid short circuits, and maintain common ground between ESP32 and power supply |

---

# 10. Software Planning

## 10.1 Software Tools

| Tool / Platform | Purpose |
|---|---|
| `MicroPython` | `Main firmware on ESP32 for IR sensor reading, NeoPixel control, servo PWM timing, and main interaction loop` |
| `MIT App Inventor` | `Backup block-based prototyping for coin/card detection logic and servo control testing during development` |

## 10.2 Software Logic
Describe what the code must do.

Include:
- startup behavior,
- input handling,
- sensor reading,
- decision logic,
- output behavior,
- communication logic,
- reset behavior.

**Response:**  
`To create a card-operated dispensing mechanism using an IR sensor, servo motor, and NeoPixel LEDs-  It detects a card, shows visual feedback, and actuates a flap to dispense an item.
Startup Behavior
Positions the servo flap to 0° and turns off NeoPixels. Flashes the first NeoPixel pink then green twice, then prints "Ready. Waiting for coin..." to the console.
Input Handling
Monitors the IR sensor continuously in the main loop with a 50ms wait time.
Sensor Reading
The card_detected() function reads Pin 34 (IR sensor). It confirms detection with a 50ms debounce if the value is 0.
Decision Logic
Triggers dispensing only on confirmed card detection. There isnt multiple card handling—single detection per cycle.
Output Behavior
NeoPixels : Pink chasing animation during 1-second "loading," green fill during servo action, then off.
Servo : Moves 0° → 90° → 0° to open/close flap, using PWM at 50Hz with auto-deinit to stop vibration.
Prints "Coin detected!" and "Done. Ready for next coin." to console after each cycle.
Communication Logic
Console-only via print() statements for status.
Reset Behavior
After dispensing, waits 1 second, turns off lights, and loops back to sensor waiting for the next card swipe. Servo always returns to 0° post-dispense.`

## 10.3 Code Flowchart
Insert a flowchart showing your code logic.

Suggested sequence:
- start,
- initialize,
- wait for input,
- read input,
- decision,
- trigger output,
- repeat or reset,
- error handling.

**Insert image below:**  
`https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/zoya---branch/images/code_flowchart.jpg <img width="1367" height="3700" alt="code_flowchart" src="https://github.com/user-attachments/assets/a967f372-5711-43b3-983b-c127b7237159" />
`

## 10.4 Pseudocode

```text
STARTUP:
    servo_move(0°)          // Position pocket to load candy
    flash NeoPixel pink+green 2x  // Welcome animation
    PRINT "Ready for card swipe"

MAIN LOOP FOREVER:
    READ IR sensor (Pin 34)
    
    IF sensor == LOW:
        WAIT 50ms                 // Debounce delay
        IF sensor STILL LOW:
            PRINT "Card detected!"
            
            // PROCESSING PHASE
            pink_loading_animation(1000ms)   // Pink chase effect
            
            // DISPENSE PHASE  
            green_fill_neopixels()         // Success lights
            servo_move(0°, 300ms)          // Settle home
            servo_move(90°, 800ms)         // Dump candy
            servo_move(0°, 500ms)          // Reload next candy
            
            neopixel_off()
            PRINT "Candy dispensed!"
            WAIT 1000ms                   // Brief pause
    
    WAIT 50ms                     
```

---

# 11. MIT App Inventor Plan

## 11.1 Is an app part of this project?
- [1] Yes
- [ ] No

If yes, complete this section.

## 11.2 Why is the app needed?
Explain what the app adds to the experience.

Examples:
- remote control,
- score tracking,
- mode selection,
- personalization,
- triggering effects,
- displaying data.

**Response:**  
`The app acts as a backup payment and control system when the physical card/coin mechanism is unavailable or fails. It adds convenience by allowing users to add digital credit, reset balance, and send commands directly from their phone, making the candy dispenser more accessible, reliable, and interactive.`

## 11.3 App Features

| Feature | Purpose |
|---|---|
| `Bluetooth connect button` | `Connects the mobile app to the ESP32 dispenser wirelessly for communication and control.` |
| `Credit / Score display` | `Shows the current balance or available credits added by the user.` |
| `Add Credit button/ Reset button/Send button` | `Increases digital credit balance for candy dispensing./Clears the current credit and sets the balance back to zero./Sends the updated credit value or command to the dispenser system.` |

## 11.4 UI Mockup
Insert a sketch or screenshot of the app interface.

**Insert image below:**  
`https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/zoya---branch/images/credit-app_screen.png`

## 11.5 App Screen Flow

1. `Open the app and tap the Bluetooth Connect button to pair with the ESP32 candy dispenser.`
2. `Check current credit balance.`
3. `Tap Add Credit (₹1 / ₹2 buttons) or Reset to manage balance.`
4. `Press Send to transfer the credit value to the dispenser and activate candy dispensing.`

---

# 12. Bill of Materials

## 12.1 Full BOM

| Item | Quantity | In Kit? | Need to Buy? | Estimated Cost (₹) | Material / Spec | Why This Choice? |
|---|---:|---|---|---:|---|---|
| ESP32 | 1 | Yes | No | 0 | WiFi + Bluetooth MCU | Compact, powerful, supports MicroPython |
| ESP32 (Replacement) | 1 | No | Yes | 510 | Same as above | Backup after original board failed |
| IR Sensor Module | 1 | Yes | No | 0 | Infrared obstacle sensor | Simple, fast coin detection |
| NeoPixel Ring (16 LEDs) | 1 | No | Yes | 250 | WS2812B LEDs | Programmable lighting feedback |
| Servo Motor (SG90) | 1 | Yes | No | 0 | 180° micro servo | Precise flap control |
| External 5V Power Supply | 1 | No | Yes | 200 | 5V 2A adapter | Stable power for servo + LEDs |
| Jumper Wires | ~20 | Yes | No | 0 | Male-Female wires | Easy prototyping |
| Breadboard | 1 | Yes | No | 0 | Standard | Circuit setup |
| Foam Board | 1 | Yes (college) | No | 0 | Lightweight board | Structure building |
| Tape & Glue | - | No | Yes | 100 | Adhesives | Assembly support |
| Candy | - | No | Yes | 100 | Consumable | Final output (dispensing item) |

---

## 12.2 Material Justification

**Response:**  
The ESP32 was selected due to its compact size, strong processing capability, and compatibility with MicroPython, making it ideal for rapid prototyping. An IR sensor is used instead of a physical switch for coin detection because it allows contactless sensing and faster response.

A servo motor is chosen over a DC motor because it provides precise angle control, which is essential for reliably opening and closing the dispensing flap. The NeoPixel ring is preferred over standard LEDs as it allows individually addressable lighting effects, enhancing user interaction and visual feedback.

An external 5V power supply is used instead of powering directly from the ESP32 to prevent voltage instability, especially since the servo motor and LEDs require higher current.

Foam board was used for the structure as it is lightweight, easy to cut, and readily available. Adhesives like tape and glue help in quick assembly without requiring complex tools.

---

## 12.3 Items to Purchase Separately

| Item | Why Needed | Purchase Link | Latest Safe Date to Procure | Status |
|---|---|---|---|---|
| Foam Board | Used for building outer structure (taken from college) | N/A | Already acquired | Received |
| ESP32 (Replacement) | First ESP32 got damaged, needed backup | Local electronics store | Immediate | Purchased |
| Tape & Glue | Assembly and structural support | Local store | Immediate | Purchased |
| Candy | Dispensing item for final output | Local store | Before testing/demo | Purchased |

---

## 12.4 Budget Summary

| Budget Item | Estimated Cost (₹) |
|---|---:|
| Electronics | 960 |
| Mechanical parts | 0 |
| Fabrication materials | 100 |
| Purchased extras | 100 |
| Contingency | 100 |
| **Total** | **1260** |

---

## 12.5 Budget Reflection

**Response:**  
The overall cost increased due to the replacement of the ESP32, which was an unplanned expense. If cost reduction is required, the NeoPixel ring can be replaced with standard LEDs, significantly lowering expenses. The structure can be made entirely using recycled materials to reduce fabrication costs.

Additionally, components like power supplies and adhesives can be reused from existing resources. Proper handling of components can also help avoid damage-related costs in future iterations.

---

# 13. Planning the Work

## 13.1 Team Working Agreement

**Response:**  

Tasks were divided based on individual strengths while allowing flexibility to support each other when needed. Ananya primarily handled electronics, wiring, troubleshooting, fabrication files, and documentation, while Zoya focused on concept development, coding, mechanical design, and system integration.

Decisions were made collaboratively, especially during major design changes such as shifting from the rotary mechanism to the servo-based flap system. Testing results and practical constraints guided most decisions.

Progress was checked through regular build and testing sessions, where both team members reviewed functionality and identified issues.

If a task was delayed, priorities were adjusted to focus on core functionality first. Non-essential features were deprioritized to ensure a working prototype within the deadline.

Documentation was maintained throughout the process, with updates added after key stages including prototyping, testing, and iteration.

---

## 13.2 Task Breakdown

| Task ID | Task | Owner | Estimated Hours | Deadline | Dependency | Status |
|---|---|---|---:|---|---|---|
| T1 | Finalize concept | Zoya | 2 | Week 1 | None | Completed |
| T2 | Complete BOM | Ananya | 1 | Week 1 | T1 | Completed |
| T3 | Test electronics | Ananya | 3 | Week 2 | T1 | Completed |
| T4 | Build structure | Zoya | 5 | Week 2 | T1 | Completed |
| T5 | Write control code | Zoya | 5 | Week 3 | T3 | Completed |
| T6 | Integrate system | Zoya | 4 | Week 3 | T4, T5 | Completed |
| T7 | Playtest | Ananya | 2 | Week 4 | T6 | Completed |
| T8 | Refine and document | Ananya | 4 | Week 4 | T7 | Completed |

---

## 13.3 Responsibility Split

| Area | Main Owner | Support Owner |
|---|---|---|
| Concept and gameplay | Zoya | Ananya |
| Electronics | Ananya | Zoya |
| Coding | Zoya | Ananya |
| App | Zoya | Ananya |
| Mechanical build | Zoya | Ananya |
| Testing | Ananya | Zoya |
| Documentation | Ananya | Zoya |

---
# 14. Weekly Milestones

## 14.1 Four-Week Plan

### Week 1 — Plan and De-risk
Expected outcomes:
- [1] Idea finalized
- [ ] Core interaction decided
- [1] Sketches made
- [ ] BOM completed
- [1] Purchase needs identified
- [1] Key uncertainty identified
- [1] Basic feasibility tested

### Week 2 — Build Subsystems
Expected outcomes:
- [1] Electronics tests completed
- [ ] CAD / structure planning completed
- [1] App UI started if needed
- [1] Mechanical concept tested
- [1] Main subsystems partially working

### Week 3 — Integrate
Expected outcomes:
- [1] Physical body built
- [1] Electronics integrated
- [1] Code connected to hardware
- [ ] App connected if required
- [1] First playable version exists

### Week 4 — Refine and Finish
Expected outcomes:
- [1] Technical bugs reduced
- [1] Playtesting completed
- [1] Improvements made
- [1] Documentation completed
- [1] Final build ready

## 14.2 Weekly Update Log

| Week | Planned Goal | What Actually Happened | What Changed | Next Steps |
|---|---|---|---|---|
| Week 1 | `Finalize idea, sketches, BOM, identify risks, test feasibility` | `decided, rough sketches made, materials like foamboard/MDF identified, basic servo + sensor testing done` | `BOM not fully completed in first week, shifted focus to testing mechanism first` | `Complete BOM and finalize dispensing mechanism dimensions` |
| Week 2 | `Build subsystems, test electronics, start app UI as backup, structure planning` | `physical hand-built structure chosen` | `physical hand-built structure chosen` | `Build outer body and improve subsystem wiring` |
| Week 3 | `Integrate body, electronics, code, first working prototype` | `Foamboard/MDF body built, electronics mounted, code linked with servo + sensor, first working candy dispenser achieved-rotating disc` | `App connection kept optional backup i` | `Improve stability, candy flow, and user experience` |
| Week 4 | `test users, improve design, complete documentation` | `changed candy mechanism completely,Servo vibration reduced, dispensing timing improved, playtested with users, report and presentation completed` | `focused more on physical aspects` | `Prepare final demo and polish aesthetics` |

---

# 15. Risks and Unknowns

## 15.1 Risk Register

| Risk | Type | Likelihood | Impact | Mitigation Plan | Owner |
|---|---|---|---|---|---|
| ESP32 failure or overheating | Technical | Medium | High | Keep backup ESP32, avoid powering high-load components from board | Ananya and Zoya |
| IR sensor false triggering / not detecting coin | Technical | Medium | Medium | Add delay + double-check logic in code, adjust sensor positioning | Ananya |
| Servo jitter or inconsistent movement | Technical | Medium | Medium | Use external power, stop PWM after movement (already implemented) | Zoya |
| NeoPixel not working properly | Technical | Low | Medium | Check data pin, ensure proper voltage and ground connection | Ananya |
| Weak structure (foam board bending or breaking) | Material | Medium | Medium | Reinforce with extra layers, tape, and glue | Zoya |
| Wiring becoming loose during demo | Mechanical | Medium | High | Secure connections with tape, minimize movement | Ananya |
| Power supply issues (insufficient current) | Technical | Medium | High | Use 5V 2A adapter, test under full load before demo | Zoya |
| Time constraints before submission/demo | Time | High | High | Prioritize core functionality over aesthetics | Zoya |

---

## 15.2 Biggest Unknown Right Now

**Response:**  
The biggest uncertainty is the reliability of the IR sensor in consistently detecting coins under real-world conditions. Factors such as ambient light, positioning, and speed of insertion may affect detection accuracy. Ensuring stable and repeatable performance during the final demonstration remains the key concern.
---

# 16. Testing and Playtesting

## 16.1 Technical Testing Plan

| What Needs Testing              | How You Will Test It                                                          | Success Condition                                                        |
| ------------------------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| IR Sensor detection             | Drop MDF tokens / swipe card multiple times at different speeds and distances | Sensor detects input consistently (≥90% accuracy) without false triggers |
| Mechanism movement (servo flap) | Run repeated cycles (10–20 times) and observe flap opening/closing            | Flap opens fully, releases exactly one candy, and closes without jamming |
| Candy flow in tube              | Load multiple candies and observe dispensing over multiple cycles             | Candies move smoothly in single file and do not jam or double-drop       |
| LED / NeoPixel response         | Trigger system repeatedly and observe light feedback                          | LED turns on immediately upon detection and turns off after dispensing   |
| Power stability                 | Run system continuously for extended time (5–10 minutes)                      | No overheating, shutdown, or inconsistent behavior                       |
| Wiring reliability              | Slightly move wires during operation to test loose connections                | System continues functioning without interruption                        |

---

## 16.2 Playtesting Plan

| Question                             | How You Will Check                                                                                |
| ------------------------------------ | ------------------------------------------------------------------------------------------------- |
| Do players understand what to do?    | Observe first-time users without instructions and see if they insert the token/card correctly     |
| Is the interaction satisfying?       | Ask users for feedback after using it and observe reactions to candy drop                         |
| Do players want another turn?        | Check if users immediately try again or ask for more tokens                                       |
| Is the challenge balanced?           | Not applicable — this is not a competitive game, but interaction should feel smooth and rewarding |
| Is the response clear and immediate? | Observe if users notice LED feedback and understand that the system is working                    |

---

## 16.3 Testing and Debugging Log

| Date   | Problem Found                                | Type       | What You Tried                                | Result        | Next Action                   |
| ------ | -------------------------------------------- | ---------- | --------------------------------------------- | ------------- | ----------------------------- |
| Week 1 | IR sensor not detecting coins reliably       | Technical  | Tested with different coins                   | Failed        | Switched to MDF tokens        |
| Week 1 | MDF tokens not detected consistently         | Technical  | Slowed down drop, adjusted sensor sensitivity | Partly worked | Considered redesign of input  |
| Week 2 | Rotary wheel not dispensing properly         | Mechanical | Increased height of wheel                     | Failed        | Modified pocket size          |
| Week 2 | Multiple candies dispensing                  | Mechanical | Reduced pocket size and adjusted rotation     | Failed        | Identified flow control issue |
| Week 2 | Candy jamming in wheel                       | Mechanical | Adjusted alignment and spacing                | Failed        | Scrapped rotary mechanism     |
| Week 3 | ESP32 stopped working (possible power issue) | Technical  | Replaced ESP32                                | Worked        | Improve power handling        |
| Week 3 | IR sensor failed mid-build                   | Technical  | Replaced sensor                               | Worked        | Keep backup components        |
| Week 3 | NeoPixel not working                         | Technical  | Re-soldered connections                       | Worked        | Improve soldering stability   |
| Week 4 | Candy dispensing inconsistent                | Mechanical | Switched to vertical tube + servo flap        | Worked        | Finalize system               |
| Week 4 | Power supply instability                     | Technical  | Changed power source                          | Worked        | Monitor voltage stability     |

---

## 16.4 Playtesting Notes

| Tester      | What They Did                | What Confused Them                              | What They Enjoyed                                 | What You Will Change                         |
| ----------- | ---------------------------- | ----------------------------------------------- | ------------------------------------------------- | -------------------------------------------- |
| Classmate 1 | Inserted token and waited    | Slight confusion about where to insert token    | Enjoyed candy drop moment                         | Make input slot more visible                 |
| Classmate 2 | Tried multiple times quickly | Didn’t realize system needs one-at-a-time input | Found LED feedback helpful                        | Add clearer visual feedback / delay          |
| Friend      | Used system independently    | Initially unsure if system was working          | Found interaction satisfying and wanted to repeat | Improve response speed clarity               |
| Peer        | Observed mechanism           | Curious about internal working                  | Liked seeing moving parts                         | Add transparent section / clearer visibility |
---

# 17. Build Documentation

## 17.1 Fabrication Process

**Response:**  

The project was developed through multiple iterations, starting from basic prototyping and progressing toward a reliable final system.

**Cutting & Structure:**  
The outer body of the dispenser was constructed using foam board. The material was manually cut using a precision cutter to create panels, openings for the input slot, and an output section for candy dispensing. The lightweight nature of foam board allowed for quick modifications during testing.

**Initial Mechanism (Rotary – Failed Iteration):**  
The first design used a rotary wheel mechanism intended to dispense candies one at a time. Circular components and compartments were cut and assembled. However, this system faced multiple issues including candy jamming, inconsistent rotation, and multiple candies dispensing at once. Due to repeated failures, this design was abandoned.

**Revised Mechanism (Final – Vertical Tube + Servo Flap):**  
The final mechanism used a vertical tube system where candies are stacked in a straight column. A servo-controlled flap at the bottom regulates dispensing. This design ensured that only one candy is released per cycle and significantly improved reliability.

**Assembly & Fastening:**  
All structural elements were assembled using tape and glue. Additional reinforcement was added at joints and edges to maintain rigidity and prevent deformation during use.

**Electronics & Wiring:**  
The ESP32 microcontroller was used as the central control unit. The IR sensor was connected to detect coin/token insertion. A NeoPixel ring was used to provide visual feedback, and a servo motor controlled the dispensing flap. All components were wired using jumper wires on a breadboard. An external 5V power supply was used to ensure stable operation and prevent overloading the ESP32. A common ground connection was maintained across all components.

**Testing & Iteration:**  
The system was tested at each stage of development. Issues such as sensor inconsistency, servo jitter, and unstable power supply were identified and resolved through both hardware adjustments and code improvements. Failed approaches were documented and used to guide design decisions.

**Finishing:**  
In the final stage, the structure was cleaned and stabilized. Loose wires were secured, alignment was corrected, and the system was prepared for demonstration. The final build focuses on functionality, clarity of interaction, and reliability.

---

## 17.2 Build Photos

Add photos throughout the project to document the process and iterations.

Suggested images:
- early sketch  
- prototype  
- electronics testing  
- mechanism test  
- final build  

Example:

```md
![Early Sketch](./images/sketch.jpg)
![Prototype](./images/prototype.jpg)
![Electronics Testing](./images/electronics.jpg)
![Mechanism Test](./images/mechanism.jpg)
![Final Build](./images/final.jpg)

Example:
```md
## 17.2 Build Photos

![Prototype Sketches](https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/ANANYA-new-branch/images/01prototype%20sketches%20.jpeg)

![Build Image 1](https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/ANANYA-new-branch/images/01WhatsApp%20Image%202026-04-20%20at%2020.05.06.jpeg)

![Build Image 2](https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/ANANYA-new-branch/images/01WhatsApp%20Image%202026-04-20%20at%2020.05.06%20(5).jpeg)

![Build Image 3](https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/ANANYA-new-branch/images/01WhatsApp%20Image%202026-04-20%20at%2020.05.06%20(4).jpeg)

![Build Image 4](https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/ANANYA-new-branch/images/01WhatsApp%20Image%202026-04-20%20at%2020.05.06%20(3).jpeg)

![Build Image 5](https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/ANANYA-new-branch/images/01WhatsApp%20Image%202026-04-20%20at%2020.05.06%20(2).jpeg)

![Rotary Wheel](https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/ANANYA-new-branch/images/rotary%20wheel.jpeg)

![MDF Cut](https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/ANANYA-new-branch/images/mdf%20cut.jpeg)

![Funnels](https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/ANANYA-new-branch/images/funnels.jpeg)

![D-Day Setup](https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/ANANYA-new-branch/images/dday%20set%20up.jpeg)

![Chart Paper Cover](https://github.com/academicsananya1234-ship-it/ODT2026-group13-sec-B/blob/ANANYA-new-branch/images/chart%20paper%20cover.jpeg)


```

## 17.3 Version History

| Version | Date | What Changed | Why |
|---|---|---|---|
| v1 | Week 1 | Initial concept with IR sensor + rotary dispensing mechanism | To explore automated candy dispensing |
| v2 | Week 2 | Modified rotary wheel size and candy compartments | To fix jamming and multiple candy drops |
| v3 | Week 3 | Replaced faulty ESP32 and IR sensor | Hardware failure during testing |
| v4 | Week 4 | Switched to vertical tube + servo flap mechanism | Improve reliability and single-candy dispensing |
| v5 | Week 4 | Stabilized power supply and secured wiring | Ensure consistent performance for final demo |
---
# 18. Final Outcome

## 18.1 Final Description

**Response:**  

The final project's an interactive candy dispensing system controlled by an ESP32. The system detects the insertion of a token or object using an IR sensor and responds with visual feedback through a NeoPixel LED ring. Once triggered, a servo motor activates a flap mechanism that releases a single candy from a vertically stacked tube.

The interaction's simple and intuitive: the user inserts a token, receives immediate visual feedback, and's rewarded with a candy. The system's powered using an external 5V supply to ensure stable operation of all components.

The final design focuses on reliability, clarity of interaction, and a satisfying user experience, with a working mechanism that consistently dispenses one candy per input.

---

## 18.2 What Works Well

- Reliable single-candy dispensing using the servo flap mechanism  
- Clear visual feedback through NeoPixel LEDs  
- Stable performance due to external power supply  
- Simple and intuitive user interaction  
- Compact and functional overall structure  

---

## 18.3 What Still Needs Improvement

- IR sensor detection could be more consistent in different lighting conditions  
- Physical structure (foam board) could be more durable and refined  
- Wiring could be cleaner and more secure for long-term use  
- Response time between input and output could be slightly faster  

---

## 18.4 What Changed From the Original Plan

**Response:**  

The original plan involved using a rotary wheel mechanism to dispense candies. However, this approach led to several issues such as jamming, inconsistent dispensing, and multiple candies being released at once. After multiple failed iterations, the mechanism was redesigned.

The final system uses a vertical tube with a servo-controlled flap, which proved to be significantly more reliable and easier to control. Additionally, adjustments were made to the power system by introducing an external power supply after encountering instability with the ESP32.

Overall, the project's evolved from a more complex mechanical system to a simpler, more efficient design that prioritizes reliability and user experience.

---

# 19. Reflection

## 19.1 Team Reflection

**Response:**  

The team worked well in terms of adapting quickly to problems and continuing progress despite multiple technical failures. There was a strong focus on finding solutions rather than getting stuck on what wasn't working. Responsibilities were handled flexibly, with tasks being taken up based on urgency rather than strict roles.

However, the project was slowed down by repeated hardware issues, including component failures and unreliable sensor behavior. Time management became more reactive than planned, with a significant portion of time spent troubleshooting instead of progressing steadily.

Overall, while the execution phase faced challenges, the team managed to deliver a working prototype by prioritizing core functionality and making practical decisions under time constraints.

---

## 19.2 Technical Reflection

**Response:**  

This project provided hands-on learning across multiple technical areas.

In electronics, the importance of proper power management became very clear, especially when dealing with components like servos and LEDs that require stable current. The need for a common ground and external power supply was a key takeaway.

In coding, working with MicroPython helped in understanding how to structure logic for real-time interactions, including handling sensor input, delays, and sequential actions.

In terms of mechanisms, the project highlighted the difference between theoretical ideas and practical execution. The initial rotary mechanism seemed viable but failed under real conditions, reinforcing the importance of simplicity and reliability.

Fabrication involved working with foam board and basic tools, which required precision and adaptability. Small alignment errors had noticeable effects on performance.

Integration was one of the biggest learnings — combining electronics, code, and physical design into a single working system required constant iteration and problem-solving.

---

## 19.3 Design Reflection

**Response:**  

The project reinforced the importance of designing for clarity and immediate understanding. Users should be able to interact with the system without needing instructions, which influenced decisions around input placement and feedback.

Designing for delight was explored through the use of NeoPixel LEDs and the satisfying moment of candy dispensing. Small feedback elements significantly improved the overall experience.

Physical interaction played a major role, as the success of the system depended on how naturally users could engage with it. Observing users during testing helped identify confusion points and areas for improvement.

Iteration proved to be essential. Initial ideas that seemed strong did not always work in practice, and multiple redesigns were necessary to arrive at a functional solution.

---

## 19.4 If You Had One More Week

**Response:**  

With an additional week, the focus would be on refining both the physical and interaction aspects of the project. The structure would be rebuilt using a more durable material such as MDF or acrylic to improve stability and finish.

The sensor system could be improved for more reliable detection, potentially by adjusting placement or exploring alternative sensing methods. Wiring would be cleaned and secured more professionally to improve robustness.

The interaction could also be enhanced by reducing response delay and adding clearer feedback cues. Additional visual or auditory elements could further improve user engagement.

Overall, the next iteration would focus on polish, durability, and improving the consistency of the user experience.

---

# 20. Final Submission Checklist

Before submission, confirm that:
- [x] Team details are complete
- [x] Project description is complete
- [x] Inspiration sources are included
- [x] Player journey is written
- [x] Sketches are added
- [x] BOM is complete
- [x] Purchase list is complete
- [x] Budget summary is complete
- [x] Mechanical planning is documented if applicable
- [x] App planning is documented if applicable
- [x] Code flowchart is added
- [x] Task breakdown is complete
- [x] Weekly logs are updated
- [x] Risk register is complete
- [x] Testing log is updated
- [x] Playtesting notes are included
- [x] Build photos are included
- [x] Final reflection is written
---

# 21. Suggested Repository Structure

```text
project-repo/
├── README.md
├── images/
│   ├── concept-sketch.jpg
│   ├── labeled-sketch.jpg
│   ├── circuit-diagram.jpg
│   ├── ui-mockup.jpg
│   ├── prototype-1.jpg
│   └── final-build.jpg
├── code/
│   ├── main.py
│   ├── test_code.py
│   └── notes.md
├── cad/
│   ├── models/
│   └── screenshots/
└── docs/
    ├── references.md
    └── extra-notes.md
```

---

# 22. Instructor Review

## 22.1 Proposal Approval
- [ ] Approved to proceed
- [ ] Approved with changes
- [ ] Rework required before proceeding

**Instructor comments:**  
`[Instructor fills this section]`

## 22.2 Midpoint Review
`[Instructor fills this section]`

## 22.3 Final Review Notes
`[Instructor fills this section]`
