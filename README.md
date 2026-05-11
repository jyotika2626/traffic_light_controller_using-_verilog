🚦 Traffic Light Controller using Verilog HDL

A simple Traffic Light Controller designed using Verilog HDL and implemented as a Moore Finite State Machine (FSM).

The controller cycles through the following sequence:
GREEN → YELLOW → RED → GREEN
This project was simulated using EDA Playground and verified using EPWave waveforms.

📌 Features
Moore FSM implementation,
Clock-driven state transitions,
Verilog RTL design,
Waveform verification,
Modular and beginner-friendly design.

🧠 FSM States
State	   Binary	   Light
GREEN	    00	     Green ON
YELLOW	  01	     Yellow ON
RED	      10	     Red ON

⚙️ Working
At every positive edge of the clock:

GREEN → YELLOW
YELLOW → RED
RED → GREEN

The output depends only on the current state, making this a Moore FSM.

🛠️ Tools Used
Verilog HDL
EDA Playground
Icarus Verilog
EPWave

📂 Project Structure
traffic-light-controller/
│
├── design.sv
├── testbench.sv
├── waveform.png
└── README.md

🎯 Learning Outcomes

This project helped me learn:
FSM design
Sequential logic
State transitions
Verilog simulation
Waveform debugging

👩‍💻 Author
Jyotika Nirban
