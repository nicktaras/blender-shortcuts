# Blender Shortcuts

## General Shortcuts (Blender 2.8+)

- **Cmd + E**: Open the menu to extrude and other features.
- **Shift + A**: Open the quick menu to add shapes and objects.
- **Shift + A (Image)**: Add background image. Select "Image" from the menu.
- **Image Reference**: Open the "Object" menu, select "Image" > "Reference Image." You can toggle the display to be visible only in certain views (e.g., front view) by selecting "Perspective" in the options.
- **Object > Set Origin**: Change the origin (registration point) of the object.
- **Ctrl + R**: Loop cut tool. Hover to bring up a line. Click to place the line.
- **Ctrl + Tab**: Quick mode change (Object/Edit mode).
- **Ctrl + B**: Bevel edges. Scroll the mouse wheel to adjust the bevel smoothness.
- **Ctrl + S (While Beveling)**: Apply smooth beveling while moving the mouse during a bevel operation. [Bevel Documentation](https://docs.blender.org/manual/en/latest/modeling/meshes/editing/edge/bevel.html)
- **Ctrl + J**: Join objects. The last selected object becomes the active object.
  
## Object and Edit Mode

- **Tab**: Toggle between Object and Edit mode.
- **X**: Open delete options (in Edit mode).
- **P**: Move selection to a new layer (in Edit mode).
- **M**: Move object to a new layer.
- **Z**: Toggle wireframe view of the scene.
- **A**: Select all.
- **B**: Box select (in Edit mode).
- **C**: Circle select (in Edit mode; press Esc to stop).
- **N**: Toggle object properties panel.
- **Ctrl + R**: Loop cut tool. You can divide your mesh further by cutting horizontal and vertical lines.
- **G * 2**: Slide selected vertices without using axis handles.
- **Ctrl + P**: Parent selected objects.

## Advanced Shortcuts

- **Left Mouse + G (Mirror Modifier)**: Adjust clipping area when using the mirror modifier.
  
---

# Modifiers

### Subsurf (Subdivision Surface Modifier)

- Smoothes your object and adds more detail.

### Mirror Modifier

- Use for symmetrical objects (e.g., creating an owl with two legs). After creating one object (e.g., leg), apply the mirror modifier and select the mirror object (e.g., the body) to automatically place the mirrored object.

---

# Parenting

- **Ctrl + P**: Parent objects. Select objects in the layer, with the last object as the active one. This will open a parenting modal. The most typical choice is "Object (Transform)".
- Parent objects on top of other parents to create complex animations.
- **Spacebar**: Search and set a parent to an empty object.

---

# Transformation Constraints

- A useful trick is to add two objects: one rotates, and the other moves up and down. This is used to create linked transformations.

---

# Vertex Groups

- When painting on a mesh, a vertex group is created for the bone. Vertices outside the group will be automatically added to the group.
- For symmetrical meshes and armatures, you can use **X Mirror** for mirrored painting.
  
Examples of vertex group use:
- Cloth simulation: You can define which parts of the mesh are affected by the cloth simulation by selecting a vertex group.
- Particle System: Choose where particles will emit from using vertex groups.

---

# Armature

- **Shift + A**: Create a bone at the cursor location.
- You can subdivide bones for more control over your rig.
- **Ctrl + P**: Connect bones, similar to parenting objects.
- **Armature Deform**: Used for character rigging.
- **Pose Mode**: Used for animating characters and poses.

---

# Inverse Kinematics (IK)

- Inverse Kinematics allows you to manipulate a chain of bones by moving the end bone, and the rest of the bones will automatically adjust to maintain the correct pose.

---

# Center Selected Element

- **Alt + G**: Reset the location of the selected element to the origin.

---

# Texture Setup Steps

1. Select each object and apply scale: **Object > Apply > Scale**.
2. In the shading view mode, select the texture option on the top-right.
3. Inside the node editor, add a new texture.
4. Select the texture type: Image and UV.
5. Click "Add Image," name it, and the texture should appear.
6. Copy and paste the texture to other objects.
7. Switch to the UV view mode to adjust the texture mapping.

---

# Handy Tips

### Limited Dissolve

- Reduces the detail on planar faces and linear edges based on an adjustable angle threshold. This is useful for simplifying the geometry of flat surfaces.

### Non-Manifold Geometry

- Ensures that there are no gaps in your mesh. Found in the select menu, this tool helps identify and fix issues with non-manifold geometry.

---

# Further Learning via Blender Cloud

- [3D Printing](https://cloud.blender.org/p/3d-printing/)
- [Blender Fundamentals](https://cloud.blender.org/p/blender-fundamentals/)
- [Blenderella](https://cloud.blender.org/p/blenderella/)
- [Game Asset Creation](https://cloud.blender.org/p/game-asset-creation/)
- [Animation Fundamentals](https://cloud.blender.org/p/animation-fundamentals/)
- [Stylized Character Workflow](https://cloud.blender.org/p/stylized-character-workflow/)

---

