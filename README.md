CREATING PREFABS OF LEVEL PIECES

*SETING UP THE MODEL TO USE IN THE SCENE
- Whenever a Model is imported is fundamenta to:
  .Generate the LighmapUV (this option will be available at the Inspector once the model is selected)
  .Remove all animation setings(also at Inspector)
  .Generate Coliders(Inspector)
  .After applied to the scene its mandatory to check the "STATIC" option at the inspector to let unity know that this Obj is not animated
  
  --------------------------------------------------------------------------------------------------------------------------------------
  
  *ASSEMBLING THE LEVEL 
  - To connect different pieces of the Level you should use the Vector link (Select the piece, then press V and Drag to the next piece)

------------------------------------------------------------------------------------------------------------------------

*ORGANIZING THE PROJECT
- In order to organize the Hierarchy Panel, you should go to the top Menu "Game Obj" and "Create Empty" then you'll have a empty obj on the hierarchy panel that you can use as s folder, now name it as "level" and drag and Drop all the Level Obj inside this "folder"

----------------------------------------------------------------------------------------------------------------------------

*LIGHTNING
-To start creating the ligh Objs, first create a Obj Empty and name it "Lights" then you right click this Obj and go to Lights and choose your light type.
