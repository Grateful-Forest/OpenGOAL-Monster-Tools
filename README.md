# OpenGOAL-Monster-Tools
One-Click Monster Exporter for Jak 1

![Navmesh](https://github.com/user-attachments/assets/21cf6645-7de2-492b-bf42-3eaaba11073d)

Features:
- Do nothing but drag a shape in Blender to make an area monsters roam in. 
- Use any shape without worrying about triangulation.
- Click and drag lines to generate paths monsters follow when idle.
- Size 3D spheres to set obstacles in 3D space.
- Paint any area to mark gaps monsters jump over.
- Export complex set-ups instantly with one-click handling of all code.
- Take no action except CTRL-V to see your monsters in game.

Includes:
- Automatic check to keep you in the 255 OpenGOAL limit.
- Unique instancing. Re-generate an old monster and it will automatically update the old one, or create a new one, your indexing won't conflict.
- Place everything accurately by placing it in 3D space.
- One-click code handling means it's both A) Instantaneous and single-click, and B) Generates all possible required code, so only a CTRL-V is needed.

Instructions:
1. Install the Blender add-on.
2. Add support for [navmeshes](https://github.com/LuminarLight/LL-OpenGOAL-ModBase/commit/4f897008fa2ec8809e04c2b32d5ef9c329afede8?diff=unified&w=0). (Thanks to LuminarLight for their original navmesh implementation)
3. Select your navmesh in Blender and generate.
