## Archived: 2026-10-31
* Repository Context: SolidMakerConverter is a C# project that converts Cura Slicer `.gcode` files into Solidmaker/XVico X9 `.slm` files.
* Purpose: To bypass buggy SolidPreform software which produces faulty prints. The printer requires specific `.slm` files with binary content.
* Workflow:
  * Uses a specific Cura profile, thumbnail creation python script, and settings embedded in a `.3mf` file.
  * Drag and drop generated `.gcode` onto `SolidMakerConverter.exe` to produce `.slm` files.
  * Solidmaker/X9 uses M910, M920, M930 to set up three tools specifying speed and laser power.
* Instructions: Provided step-by-step workflow for setting up Cura 4.9.1 to work with the project.
* Key Files: `SolidMakerConverter.sln`, `Cura Files`, `README.md`, `SolidMakerConverter/` source folder.
