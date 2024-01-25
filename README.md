# face-filter

How to set up the project:

- Establish a python virtual environment        python -m venv .virtenv
- Activate the virtual environment              .virtenv\Scripts\activate
- Install dependencies                          py -m pip install opencv-python numpy dlib matplotlib.pyplot

What the script does:

- Detects facial landmarks using dlib
- Highlights face with a bounding box
- Creates a filter layer from a foreground image with alpha values
    - In this case, a simple whiskers image that centres on the tip of the nose
- Displays filter layer on top of background image (face)
