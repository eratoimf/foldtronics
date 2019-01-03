#You are going to need:

* The latest Rhino5 WIP

* Grasshopper

* Eagle

* Illustrator

* Silhouette Studio

#Steps:

1. Import a 3d model in Rhinoceros.

2. Run the "Grasshopper" and open "HoneycombConvert_8.gh".

3. Select the model in Rhinoceros and right click a brep component and "Set one brep" on Grasshopper.

4. Open "Remote Control Panel" of View of Grasshopper.

5. Change the width of the cell using the slider.

6. Convert model into honeycomb structure and 2d cut data by clicking "Convert Honeycomb".

7. Move the component(blue color) and change the size by "select components from this list".(still construction)

8. Creating the 2d data by clicking "bake" of geometry component of "bake this".

9. Export cut lines with “ selected objects” as AI file. 

10. Import AI file into Illustrator, and replace them within A4 paper. 

11. Export it as DXF file.

12. Open the Eagle and Import DXF with import_dxf_polygons_v4.ulp, set Import to layer “20 -Dimension" using this library. 
(https://todbot.com/blog/2011/06/06/from-illustrator-to-eagle-vector-graphics-in-circuits/comment-page-2/)

13. Place components with parts library of foldpin6.lbr

14. Autorouting 

15. Export DXF file 

16. Open DXF in Silhouette Studio ( Check Preference , DXF size) 



Copyright (c) 2018-2019 Junichi Yamaoka. All Rights Reserved.

