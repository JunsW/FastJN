# FastJN

![Build Pass](https://img.shields.io/travis/rust-lang/rust.svg)

This repository contains some automator scripts that make your life with Jupyter notebook much more efficient.

## How to use

Download or clone this project, you will find those wierd folder-like files are actually automator scripts.

![pic]()

Double-click on the script and click “install” button on the pop-up window. it will automatically installed and a system preferenc might show up to allow you manage the actions. Just close it if you don’t want to do any further customization.

For example, if you installed _Open ipynb_, right click on any “.ipynb” file, you will find “Open ipynb” in the “Quick Actions”.

All donw👏.

> Those quick actions installed can be accessed by right click menu on all types of files in Finder. Don’t do it on wrong file tpyes.

## Content

1. Open ipynb
With this script, you can open any `ipynb` file by simply right clicking file and selecting this item in the “Quick Actions”.

This action will open a new Terminal window that is running jupyter notebook. So you need to manaully close jupyter notebook session when finished editing. 

Select the terminal window and press `Control+C` to end the session and `CMD+Q` to quit the terminal.  
Or  
Select the terminal window and press `CMD+Q` and then click on `Terminate Process` button on popup alert.

2. Convert to html
This action will convert your `ipynb` to a html file. 
The new file wiil be in the same folder as your `ipynb` file.

3. Convert to pdf
This action will convert your `ipynb` to a pdf file. 
The new file wiil be in the same folder as your `ipynb` file.

> This function need to `pandoc`.  
Run `pip install pandoc` in your terminal when you see error.


