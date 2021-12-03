
This is basically the same as the Mathcad ditch example that uses
the SmartSketch Component.  However, this time a Mathcad 
object is inserted into the SmartSketch drawing and we use
VB to make the connections.
  
Directions:

Place the Ditch.igr and MathCAD.bas files in the same folder.
Open the SmartSketch file Ditch.igr.
Open the Variable Table.
Select the one of the dimensions (e.g. BW, D, SideLength) and change 
  its value.
The Mathcad Object will automatically update based on the new drawing 
  dimensions.

You can open the file MathCAD.bas to see the VB code needed to
  make this example work.
You can open the Imagineer variable table to see how the VB module
  function was called.
The dummy variable "Wow" has a VB module function specified in
  its formula property.

Note: The Mathcad object is sized to display only the answer for
flow rate.  To see all equations in the worksheet, select the smartframe
around the object and resize it with the handles in the middle of the segments, 
not the corners.
