# Team PAA SDV

Team PAA SDV is a browser-based electric vehicle simulator presented at **JKUAT Tech Week 6.0** for the Software-Defined Electric Vehicle Design Challenge.

**Team PAA:** Evans Kimutai and Charles Kaguchia. The original simulator and technical paper use the name **Duma SDV** and credit **FNM**.

[Simulator source and setup](https://github.com/MrNahadi/DUMA-SDV#quick-start) · [Technical paper](https://github.com/MrNahadi/DUMA-SDV/blob/95a9fc179c7710fd3f34e53ab581f36cba73e321/paper/main.pdf)

## What it demonstrates

Six simulated electronic control units exchange messages over a CAN bus. A TypeScript simulation core advances the battery, motor and vehicle models in fixed 10 ms steps. A browser dashboard, 3D car and live CAN trace show how controller decisions affect the vehicle.

| Competition deliverable | Team PAA implementation |
| --- | --- |
| System architecture | Browser interface, state and timing, and simulation core with six ECUs |
| Software design documentation | Technical paper, simulation specifications and architecture decisions |
| Functional prototype | A runnable browser application and guided demo |
| Digital dashboard | Speed, battery charge, power, estimated range and warnings |
| Vehicle simulation | Startup, driving, regenerative braking, AC and DC charging, and fault handling. The demo also includes an over-the-air update. |

## Tech Week presentation notes

These notes draw only from the EV material in slides 1–5.

- **Why PAA:** The antelope inspired the project’s emphasis on quick response, agility and efficient use of energy.
- **Design inspiration:** *Slow Roads* inspired the uncluttered visuals, the open-road feel and the simple driving controls.
- **Documentation:** The presentation points viewers to project documentation. The technical paper linked above explains the system architecture and simulation.

To see the scenarios run, follow the simulator setup instructions and select **Start demo** in the application.
