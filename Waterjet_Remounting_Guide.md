Part A - Designing the CAD Files:
  1. Especially important to create a rectangle base in the sketch representing the plate itself.
  2. Decide a splitting point for the two CAD files to mirror each other at, cutting space on waterjet is 15~20 inches (rough estimate).
  3. Two CAD sketches will need to be drawn, the left side sketch will be done regularly.
  4. The right side sketch will need to be mirrored vertically and horizontally about the center of the plate compared to the full design.
  5. If a design must be split in the middle of a cut out piece, the halves of that piece should extend ~2/100 inches to ensure that they connect to form the full cut out.
  6. Cut one sketch, remount, then cut the other/

Part B - Using ProtoMAX Layout:
  1. Open the .dxf file by going to File -> Import from other CAD in ProtoMAX Layout.
  2. There may be an issue where the sketch is much larger than expected due to imperial-metric conversion issues: right click the "Size" command then select the appropriate conversion.![image](https://github.com/NovakovM/Vivado-PS-PL-Notes/assets/84331501/12e92a7a-fb9b-4532-a1f3-425ce410da79)
  3. To move the sketch to the origin, click "Move", the bottom left corner of the plate, then the zero command that should pop-up after "Move" was clicked.![image](https://github.com/NovakovM/Vivado-PS-PL-Notes/assets/84331501/286b6ccd-5801-47dc-a026-0f87233b73a5)
  4. To avoid the program trying to cut out the plate, click "Select" then click the outer box and hit delete.![image](https://github.com/NovakovM/Vivado-PS-PL-Notes/assets/84331501/6f56ac28-664a-4cd7-9d51-36005dc1609c)
  5. Click "Autopath", then click the 0,0 origin point when the prompt appears asking for the start point.![image](https://github.com/NovakovM/Vivado-PS-PL-Notes/assets/84331501/4e20c40d-407c-4498-aa38-3cc73d24297f)
  6. Click (maybe right click) "Post", zoom in and watch for the pink shaded waterjet path. It may be that it attempts to cutout arond the outside of the shapes instead of the inside (reject the prompt if this is the case).![image](https://github.com/NovakovM/Vivado-PS-PL-Notes/assets/84331501/846fa22a-2ea2-4c5e-8801-4926a07609e1)
  7. To remedy this, click "Lead i/o", then select the leads protruding from the paths and move them to the orientation opposite of what they were (inside/outside the cut out).![image](https://github.com/NovakovM/Vivado-PS-PL-Notes/assets/84331501/f9bd97ca-5ba4-4c1e-b518-f6b91bb7ba04)
  8. Click "Post" again and see if the issue is fixed. If so, accept the prompt and ProtoMAX Make should open with the new file created.
  9. In ProtoMAX Make, click "Go Home" and make sure the jet returns to the home position.![image](https://github.com/NovakovM/Vivado-PS-PL-Notes/assets/84331501/e8f0169b-f281-44e3-9849-0a6a571de18f)
  10. Click "Begin Machining", then click Dry Run Full Speed to make sure the jet does not colllide with any of the clamps.![image](https://github.com/NovakovM/Vivado-PS-PL-Notes/assets/84331501/3e8f93d7-86df-4921-a24a-6186622684f5)
  11. If the dry run didn't have any issues, the full run is safe to go.

Notes:
  If the plate can't be easily moved with your hand, it should be sufficiently clamped in the waterjet.
