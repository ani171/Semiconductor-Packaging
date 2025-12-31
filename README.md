# Semiconductor-Packaging

## Module 1
#### Why is semiconductor packaging needed?
- When dies/chips come out of the wafer, they are made in a protected environment, but ICs are exposed to the real world. So packaging:
  1. Enables the die to connect to other dies
  2. Protection of semiconductor devices (Corrosion, moisture, and physical damage)
<br> </br>
#### IC Manufacturing Flow:
1. Design – Circuit & layout design
2. Wafer Process – Fabrication of ICs on wafers
3. Package & Test
    - Wafer Test – Test individual dies on wafer
    - Package – Encapsulation of dies
    - Package Test – Test packaged ICs
4. Assembly – Final integration into products

#### Types of Manufacturers:

- IDM (Integrated Device Manufacturer) – Handles design, fabrication, packaging, and testing in-house
- OSAT (Outsourced Semiconductor Assembly & Test) – Specializes in packaging and testing only
- Fabless – Only designs ICs; fabrication outsourced
- Foundry – Only fabricates ICs for other companies

#### Silicon lifecycle
<img width="646" height="541" alt="image" src="https://github.com/user-attachments/assets/7fcb828b-dfbd-4ff1-b2e8-97e7ae28cfdd" />

#### Choosing the right package
1. Application – Memory/logic, etc.; bandwidth decides speed and number of interconnects
2. Thermal Dissipation – Chip power and mounting material decide package type; high-temperature chips can’t use laminate organic substrates
3. Form Factor – Package thickness and footprint constraints
4. Reliability – Performance over time and operating conditions
5. Durability – Mechanical and environmental robustness
6. Cost 

 INSERT DRAWN IMAGE

 #### Packaging classification
 1. Through hole mounting - TO, DIP, PGA
 2. Surface mount technology
  - QFN (Quad Flat No-Lead) – Leadless package, good thermal and electrical performance, small footprint
  - QFP (Quad Flat Package) – Gull-wing leads on all sides, easy to inspect and solder
  - PBGA (Plastic Ball Grid Array) – Solder balls underneath, high I/O density, better signal integrity
  - LGA (Land Grid Array) – Flat lands instead of balls, used where socketing or fine pitch is needed
  - CSP (Chip Scale Package) – Package size ≈ die size, similar to BGA, very compact
  - PoP (Package on Package) – Multiple packages stacked vertically, saves board space (common in mobiles)
  - MCM (Multi-Chip Module) – Multiple dies integrated in one package, improves performance and integration

- Options for carrier: Leadframe, laminate, plastic, ceramic(for high temperature), organic RDL, silicon, glass
- Options for interconnections - Wirebond(Stitch type), Bump/Solder

#### Anatomy of packages
-Leadframe - a thin metal frame that holds the silicon die and connects it to the outside world
<img width="1540" height="714" alt="image" src="https://github.com/user-attachments/assets/6e1b71fe-7428-4ba8-b433-f2156fd5dad2" />

- Laminate
