# Orange-Tutorial
Tutorial using [Orange Visual Programing](https://orange.biolab.si/) API.

## Download Orange

[Click here](https://orange.biolab.si/download/#macos) for download the Orange last version:

+ Choose your operative system
+ Execute the download file

## Create a virtual environment an launch Orange

1. Go to the path that do you want to create a virtual environment, and in the command line type this:

```bash
virtualenv --python=python3 --system-site-packages orange3venv
```
Great! You've your virtual environment **named orange3env**.

2. Activate the virtual environment, typing in the command line:

```bash
source orange3venv/bin/activate
```

3. Install Orange and the other necessary packages in your virtual environment:
```bash
# Install Qt dependencies for the GUI
pip install PyQt5 PyQtWebEngine

# Install Orange
pip install orange3
```
4. Finally, launch orange GUI:

```bash
python3 -m Orange.canvas
```
## Let's to explore Orange

+ Open Orange software
+ Click en new

### Load your first dataset

Now, you're in a blank canvas. In the left panel, you can see the widgets that you have installed in Orange. Search the Data widget, and choose the icon *File*, the icon will be added to the canvas.

![](images/iFile.png)

Double click in the icon File, and choose one some the pre-installed datasets.

![](images/iDatasetOrange.png)

###
