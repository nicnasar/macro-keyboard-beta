# Macro Keyboard Beta v0.1
Repository for holding all the files of the Macro Keyboard developed by Nicolas Nasário and Alvaro Radavelli.

## Step-by-Step Guide on How to Make the PCB

I'm using a different technique that I learned from this video:

[![](https://markdown-videos-api.jorgenkh.no/youtube/{gY0AELOHGRc})](https://youtu.be/{gY0AELOHGRc})

In order to replicate that, you have to do the same steps as shown below:

1. Develop the PCB and generate the gerber files;
2. Use a CNC router to make the board;
3. Cover the backside with spray paint;
4. Use a Laser CNC to remove the paint **only** on the backside;
   - To do this, you are going to have to export the SVG files;
   - Then, open them on your favourite app for converting vector files into image files;
   - Convert your file with a resolution of at least 10,000 pixels (I know it looks too much, but trust me, it's worth it);
   - Open the image file on a PNG to DXF file (assuming that you used PNG);
   - Convert the image and then open in the app;
   - Use your board holes to align it to the CNC base, remember to glue or tape a sacrificial MDF board;
   - Position your board an then turn on the laser;
5. Spray paint the other side and repeat the same steps above, but this time to engrave the text and details.

### And then, you have your PCB!

[Placeholder for image of PCB ready]

![Alt text](images\3d-file.png?raw=true "3D-file")
