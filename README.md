# New-side-bird-stl

This repo is for working with STL files.

## How to edit an STL file

### Option 1: Blender (free, GUI)
1. Open Blender.
2. Go to **File → Import → STL** and select your file.
3. Edit the mesh in **Edit Mode** (`Tab`) using move/scale/rotate tools.
4. Go to **File → Export → STL** and save your updated model.

### Option 2: FreeCAD (free, CAD-style)
1. Open FreeCAD and create a new document.
2. Import your STL (`File → Import`).
3. Switch to **Part** workbench and convert mesh to shape:
   - **Part → Create shape from mesh**
   - **Part → Convert to solid**
4. Modify as needed, then export as STL.

## Tips
- Keep an untouched backup of the original STL.
- If the model has issues, run mesh repair in Blender or FreeCAD before exporting.