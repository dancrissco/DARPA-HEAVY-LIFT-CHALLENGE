# DARPA-HEAVY-LIFT-CHALLENGE
Repository for Design History Files for the project
DARPA Heavy Lift Challenge — Design History Files (DHF) Repository
Open-Source Air-Supported VTOL Framework (HawaFrame)

Welcome to the official repository for our open-source entry into the 2026 DARPA Heavy Lift Challenge.
This workspace hosts all Design History Files (DHF), engineering documentation, simulations, and RFQ packages required for the development of our novel HawaFrame — an ultra-lightweight, RF-welded, air-supported VTOL structure designed to maximize lift efficiency while dramatically reducing structural mass.

📌 Project Vision

Build a 165-lb VTOL aircraft using only ~55 lb of structural mass, while carrying a 110-lb payload, leveraging:

RF-welded tubular “air-frame” structures

Modular 3D-printed motor corner brackets

Parametric CAD (OnShape) + physics simulations (CoppeliaSim)

Rapid assembly & field-repair capability

Open-source philosophy → community-driven innovation

The goal is to demonstrate a new class of inflatable-rigidized air-supported drone frames that deliver unprecedented payload-to-mass ratios, cost efficiency, and manufacturability.

📁 Repository Structure

This repository is split into engineering-ready folders to match professional DHF expectations:

DARPA-HEAVY-LIFT-CHALLENGE/
│
├── README.md                          → Introductory overview (this file)
│
├── DHF/                               → Design History File master folder
│   ├── 01_URS/                        → User Requirement Specifications
│   ├── 02_FRS/                        → Functional Requirement Specs
│   ├── 03_System_Architecture/        → Block diagrams, subsystem maps
│   ├── 04_Risk_Analysis/              → ISO 14971 style risk matrix
│   ├── 05_Design_Inputs/              → Materials, physics assumptions
│   ├── 06_Design_Outputs/             → CAD models, tube designs, brackets
│   ├── 07_Verification/               → Calculations, test setups
│   ├── 08_Validation/                 → Full-scale test plans
│   └── 09_Document_Control/           → Versioning + change logs
│
├── RFQ/                               → Vendor-facing Request For Quotes
│   ├── RFQ_Tube_Fabrication/
│   ├── RFQ_RF_Welded_Tubes/
│   ├── RFQ_Corner_Motor_Mounts/
│   └── RFQ_Assembly/
│
├── CAD/                               → OnShape exports (STEP, STL)
│
├── Simulation/                        → CoppeliaSim scenes, Python scripts
│
└── Media/                             → Renders, diagrams, LinkedIn visuals

🚀 What Makes HawaFrame Unique

Air-supported rigidity (inflatable tubes with end-caps + RF welding)

Lowest structural weight pathway for a 165-lb class VTOL

Field-serviceable corner modules (motors, ESCs, battery mounts)

Parametric adjustability → scale to multiple rotor diameters

Integrated payload-and-motor support from the pressurized frame

This design exploits regulatory allowances for air-blown structures, giving us a competitive advantage.

🔬 Current Status

✔ Frame geometry established in CoppeliaSim

✔ Tube patterns and corner brackets prototyping in progress

✔ Repository structured for DHF compliance

✔ RFQ templates drafted

⏳ Integration of propulsion units (ESC + motors)

⏳ Structural testing simulations

⏳ Open-source community onboarding

📢 Contributing

We welcome researchers, aerospace engineers, materials specialists, robotics hobbyists, and students interested in:

Inflatable structures

UAV propulsion

CAD design

Simulation

Manufacturing (RF welding, TPU composites)

To join, open an Issue or submit your first PR.

📬 Contact & Updates

Follow the ongoing engineering journey on LinkedIn, where regular updates, Gemini visuals, and simulation breakthroughs are shared with the community.
