# RELEASE NOTES

## HeylandCircle v0.2.0 (Nov 19, 2026)
- Equivalent circuit: Parameter extraction from test data implemented, pytest and example script (motor_equivalent_circuit.py) added
- Circle diagram example figure: Included in the README
- Fixed: Naming consistency in MachineTestData (Isc → I_sc)
- Read the Docs documentation
- CI badge: Added in README
- Binder badge: Added in README
- Fixed: Repeated calls to `CircleDiagram.plot()` no longer rescale the input `MachineTestData` (results now identical across calls)
- Fixed: Repository links updated to the abruan-aerospace GitHub organization
- Fixed: Example docstring in motor_circle_diagram.py

## HeylandCircle v0.1.0 (May 11, 2026)
- Initial release of the HeylandCircle framework.
- Initial release supporting the paper: "HeylandCircle: A Computational Framework for the Geometric Reconstruction of the Heyland Circle Diagram", arXiv: 2025 [eess.SY]
- Scripts included:
    - motor_circle_diagram.py