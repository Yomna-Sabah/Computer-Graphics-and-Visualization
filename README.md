# Computer-Graphics-and-Visualization

## Part1

1. draw a floor and put the full body on top of it.
2. put a texture on the floor
3. use a menu binned to the right mouse button to change the floor texture.
4. you are required to to design two animations:
    * Using the robotic body without interaction with any object.
    *  The robotic body should interact with loaded objects
5. download different objects and load it in your scene to make sense of the animation environment.

You can find in the part 1 folder:
   1. Assignment 3 zip folder containing:
      - main.cpp
      - image folder for texture mapping images
      - data folder for .obj and .mtl file of objects
      - imageloader and glm files
   2. Demo video zip folder containing:
      - Demo video to illustrate robot animation & texture mapping 
   3. README explaining functions added, self-animation technqiues, loaded objects interaction animation techniques and texture mapping technique

## Part2

* Build your own volume rendering app with VTK & Qt
* Use datasets provided in data directory (Head and Ankle)

**Note** You must use [vtkDICOMImageReader](https://vtk.org/doc/nightly/html/classvtkDICOMImageReader.html#details) object.

* Features 
    * Support loading DICOM series dynamically using load button
    * Surface rendering (With adjustable iso value) using sliders
    * Ray casting rendering (with a fixed transfer function)
        * Bonus (Adjustable transfer function)
        
You can find in the part 2 folder:
   - Assignment Code (app.py & win.py)
   - Demo video to demonstrate how to run
   - README explaining how to run along with sample results
   - data folder containing dcm slices of Head and Ankle
