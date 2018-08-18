# Prusa MK3 Arducam Mount Files

This mount is meant for the Arducam with CS lens:

    https://smile.amazon.com/gp/product/B012ETE75I

It attaches to the aluminmum rail under the bed and provides 2 degrees of
freedom for aiming the camera. The mount is particularly meant to keep the
center of mass of the camera module over the support.

The model:
 - [arducam_mk3_mount_v3.f3d](arducam_mk3_mount_v3.f3d)    

STL files:
 - pivot_arm.stl
 - rail_arm.stl
 - rotation_plate.stl
 - rotation_body.stl

Suggested print orientations:

 - printing_orientations.png  

Use the layer editing feature of Slic3r PE to add detail around the horizontal
holes:

 - rotation_body_layer_detail.png
 - pivot_arm_layer_detail.png  

The assembly:

 - arducam_mount_assembly.png  
 - final_assembly_detail_1.png
 - final_assembly_detail_2.png
 - final_assembly_detail_3.png

Note:  These pictures show an earlier version.  I added more rotation, an
offset to account for the plate at the end of the extrusion, and tweaked the
tolerances in the final model.  But the overall build is as shown.

In addition, you'll need:
 - For mounting the arm to the extrusion:
   - 2 M4x25 screws
   - 2 T drop nuts, such as:  https://smile.amazon.com/gp/product/B078RGCSZT
 - For the horizontal pivot:
   - 1 M5x30 bolt 
   - 1 M5 hex nut
  - For the vertical pivot:
   - 1 M5x10 bolt (threads directly into the hole)
  - For securing the vertical adjustment:
   - 1 M3x10 bolt and nut
  - For securing the camera to the mount:
   - 4 M3x10 screws and nuts
   - washers to provide standoff for the components on the back of the board
     (I didn't use washers, so I was careful not to over-tighten the mount screws.)
