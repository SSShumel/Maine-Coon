
Beam.igr is a SmartSketch file that contains a simple beam with
Mathcad inserted as an object.  The length of the beam and the distance of the
point load can be changed via selecting the dimensions L and a1, respectively,
and making a change.  The point load and the distributed loads are variables in
the SmartSketch variable table called PLoad and DLoad, respectively.
Changing any of these values causes the Mathcad object to update and show the
new diagrams.

If you keep the file Beam.igr and the Visual Basic file 
in the same folder the example should execute properly as is.  
However, if you save the VB file in some other folder you will
have to make the modifications outlined below to make the example work
properly.
 

If the folder where you have the VB file is different
than where you have the file Beam.igr you'll need to make 
these modifications...

Open the file Beam.igr in SmartSketch.
Open the variable table.
Select the variable "boom" and delete it.
Select the open field for a new variable and key in a new name.
Select the Formula field for that variable.
Select the fx button on the variable table (Function Wizzard).
Select Visual Basic.
Navigate to the folder containing the VB files.
Select the VB module Module1.bas.
In the Function Name window select the single function available in the form 
  "Module1.GetC" then click the Next button.


In Step 2 of the wizzard when it asks for variable names answer
with the same name that is shown to the left i.e. L, a1, PLoad, and DLoad.


It should be set up now and the Mathcad object will reprocess on changes to
the variable table or dimensions in the drawing file.


NOTE: The shear diagram does not show all of the graph while inserted in
Imagineer.  If Mathcad is activated all the graph is shown but the
metafile doesn't show all of it.

