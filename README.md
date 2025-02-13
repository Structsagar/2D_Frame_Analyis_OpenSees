"# 2D_Frame_Analyis_OpenSees" 
"# 2D_Frame_Analyis_OpenSees" 
"""
This 2D frame analyzer built using OpenSees allows users to easily construct structural models by specifying their building input parameters. The `build_model` function dynamically adapts to the number of bays provided. For instance:
- If the structure has 3 bays, the function is called with `build_model(Lx1, Lx2, Lx3, Lz, no_of_bays, no_of_floors)`.
- For any number of bays, simply extend the parameters: `build_model(Lx1, Lx2, Lx3, Lx4, ..., Lz, no_of_bays, no_of_floors)`.

Users define bay lengths = [0,4, 9, 15, 20] --> different bays length must be specified with reference to origin <--  
and floor height (Lz = 3), and the code builds the frame model accordingly. This makes the framework scalable, user-friendly, and suitable for various building configurations.
"""
