HelloZWorld
===========

The 3D equivalent of "Hello world" using Unity on zSpace

You should be comfortable with importing packages in Unity and some basics of the Inspector window.

These instructions are current as of October 24, and provide workarounds for problems with the zSpace Unity packages.

INSTALLATION

Start a new project in Unity. Import the ZSCore and ZSUtility packages per zSpace instructions. Then import the Hello Z World package. Ignore any complaints from Unity during this process.

Open the Hello Z World scene.

Now drag a ZSCore prefab into the Hierarchy and connect the camera to it, per zSpace instructions. Drag a ZSStylusSelector prefab into the Hierarchy. Expand that object and delete the SplineTool. Unity will complain about you trying to do this; do it.
Then go to Edit, select Project Settings and Player. Look in the lower part of the window and change the API Compatibility Level setting to .NET 2.0. Unity will complain; ignore it.

Now quit Unity - saving the document - and restart; this is the easiest way to trigger a recompile. Select Main Camera and connect the ZSStylusSelector to the Stylus field. At this point Unity will be satisfied and you can start working with the project.

USAGE

The Hello Z World project does very little, which is the point, because its purpose is to get a working zSpace Unity project.

The earth spins; as long as that continues then nothing has crashed. You can pick up letters as usual with a zSpace app. Clicking on the Reset capsule with the main stylus button restores all the letters to their default position.