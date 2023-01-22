<h1 align="center">BB to xterm</h1>
<p align="center">Convert BBcode color's to xterm256 colors</p>

## about
Used to convert [asciiart.club](https://asciiart.club/) ascii output with color

Simple project made in a day.

## example output

Original             |  Ascii
:-------------------------:|:-------------------------:
![](./example.png)  |  ![](./example-output.png)

## Install dependencies
```
python -m venv venv
source venv/bin/activate        # Bash/Zsh
source venv/bin/activate.fish   # Fish
pip install -r requirements.txt
```

## Usage
Use a terminal with xterm256 color support for best results.

Go to [asciiart.club](https://asciiart.club/) and load you image  
Change colors from `Black on white` to `White on Black`  
Copy BBCode output to a file  
To convert the file run the python script  
`python BB-to-xterm.py /path/to/your/ascii.bbcode`  
this will print the result in to the console. to save you can just pipe the data to file  
`python BB-to-xterm.py /path/to/your/ascii.bbcode >> output.ascii`  
