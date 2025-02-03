# Input Validation 

## Setup
Setup a virtual environment and install the required packages.

```bash
python3 -m venv myenv  # Create the environment
source myenv/bin/activate  # Activate the environment
```

Install the `Pillow` package for image processing inside the virtual environment: `pip3 install Pillow`.
(You can also use the requirements.txt file to install the required packages: `pip3 install -r requirements.txt`)

## Running the program

Use the `view.py` file to run the GUI application. 
You can select a CIFF file to upload and view the image. 
The program will use the `ciff.py` script to decode the image and display it in the GUI.
The `moodle_submission.py` script can be used either separately or from the GUI menu to run the parser for all the test images.

```bash
python3 view.py
```

or 

```bash
python3 moodle_submission.py
```