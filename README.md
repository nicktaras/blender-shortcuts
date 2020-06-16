# blender-shortcuts

- tab - toggle between scene and edit mode
- x - open delete options from edit mode
- p - move selection e.g. move selected mesh in edit mode to a new layer
- m - open layer selection to move selected object
- z - toggle to see wireframe of scene
- a - select all
- b - in edit mode box select mesh
- c - in edit more paint select mesh (esc to stop paint selection)
- n - toggle object details panel
- ctrl + r - loop cut tool, when it edit mode you can further divide your mesh cutting horizonal and vercial lines through your model
- g * 2 - Slide selected verticies. This saves you from having to use the axis handles. 

# blender-shortcuts (advanced)

- When creating an object and using the mirror modifier, using the LEFT Mouse + G will adjust the clipping area accordingly. (Available in latest version of Blender).

# Modifiers

Subsurf - Subdivision Surface Modifier. It smoothes your object and adds more detail.
Mirror - When creating object with symmetry e.g. an owl with two legs. You can create one leg, then add the mirror modifier, then select mirror object as the owls body object. This will place the leg in the right location automatically. 

# Texture Steps

1. Inside the shading view mode
2. Select the texture option from the options on the top right
3. Then inside the node section add a new texture
4. Select, image and UV in the set up
5. Click to Add image, give it a name
6. You should then see the texture appear
7. Copy and paste the texture to each object
8. The move the the UV view mode

# handy tips

Limited Desolve:

Reduces detail on planar faces and linear edges with an adjustable angle threshold. Always dissolve vertices that have two edge users at boundaries. Prevent faces from joining when they don't share certain properties (material for e.g.).

Tip - This is a great tool when you want to remove all inner connected vertices (line fills).

Non manifold:

Ensure that all of the mesh is complete / no gaps are present. This function can be found in the select menu.

