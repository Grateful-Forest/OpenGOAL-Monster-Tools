# OpenGOAL-Monster-Tools
One-Click Exporter of All Monster Related Code

![Navmesh](https://github.com/user-attachments/assets/21cf6645-7de2-492b-bf42-3eaaba11073d)

Features:
- Do nothing but drag a shape in Blender to make an area monsters roam in. 
- Use any shape without worrying about triangulation.
- Click and drag lines to generate paths monsters follow when idle.
- Size 3D spheres to set obstacles in 3D space.
- Paint any area to mark gaps monsters jump over.
- Correctly export all monster related code in a single click.
- Do nothing but CTRL-V to see your monsters in game.

Includes:
- Checks that keep you in the 255 OpenGOAL limit.
- Unique instancing. Touch up a previous export and it'll replace the old one, or create a new one, your indexing won't conflict.
- Place everything with accurate precision, by placing it exactly in 3D space.
- One-click handling of all code, including formatting complex use-cases. So it is both a) instantaneous and single-click, and b) generates all possible required code, so only a CTRL-V is needed.

Instructions:
1. Install the Blender add-on.
2. Add support for [navmeshes](https://github.com/LuminarLight/LL-OpenGOAL-ModBase/commit/4f897008fa2ec8809e04c2b32d5ef9c329afede8?diff=unified&w=0). (Thanks to LuminarLight for their original navmesh implementation)
3. Select your navmesh in Blender and generate.
