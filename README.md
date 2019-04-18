# opencv-container
Singularity container for OpenCV

I had a number of issues with correctly setting up the commands for the cmake step of creating the singularity container.

So I decided to build a container of dependencies and download of opencv source code.

I then tried varying cmake commands till it finally worked as expected.

The nest step is to merge the 'opencv' and 'cv-cmake' recipe files into a single recipe file, which should work.
