# SloBlo_KiCadLibs

Use Blender for export:
 - Enable Add-on "Import-Export X3D, Import VRML2"
 - Create your model
   - don't use Nodes shaders!
 - Use File -> Export -> X3D Extensible 3D (.x3d)
   - set Transform -> Scale to 0.397 (vertices are interpreted in inches by KiCad)
   - set Transform -> Up to 'Z up'
 - Import .x3d file on the 3D Models tab within KiCad Footprint editor
 