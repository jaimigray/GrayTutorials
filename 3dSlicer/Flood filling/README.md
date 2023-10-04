# Using the Segment Editor "flood filling" tool in 3D Slicer

*The Flood filling tool in 3D Slicer's Segment Editor fills connected voxels with similar intensity. This tool works well for datasets with distinct components that are not tightly connected to each other.*

- Load in a dataset you want to segment
- Switch to the **Segment Editor** module
- Add a new segment and select the **Flood filling** tool
<img src='https://github.com/jaimigray/GrayTutorials/blob/main/3dSlicer/Tutorial%20images/tutorial%20images/Slide1.JPG?raw=true'>

- Insert a value for **Intensity tolerance**. Bear in mind that this value will control how many grayscale values are filled in both directions from whichever voxel you click on.
<img src='https://github.com/jaimigray/GrayTutorials/blob/main/3dSlicer/Tutorial%20images/tutorial%20images/Slide2.JPG?raw=true'>

- Click your selection in one of the 2D windows, selecting your starting voxel for the flood filling tool. For this example I am selecting a high density voxel in the lower jaw of a snake skull. 
- This will fill all of the connected voxels within the **intensity tolerance** you set. It will expand the selection until it hits a boundary that is outside of the intensity tolerance.
<img src='https://github.com/jaimigray/GrayTutorials/blob/main/3dSlicer/Tutorial%20images/tutorial%20images/Slide3.JPG?raw=true'>

- Click the **Show 3D** button to display your new segment in the 3D window
<img src='https://github.com/jaimigray/GrayTutorials/blob/main/3dSlicer/Tutorial%20images/tutorial%20images/Slide4.JPG?raw=true'>

