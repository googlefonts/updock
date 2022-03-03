# Updock

What's Updock? Other than a famous query by an even more famous bunny, it's a beautiful script font with a nearly upright stress. Updock is an extremely legible formal script with clean connectors and a variety of of discretionary ligatures.

![Sample Image](documentation/image1.png)

## Building the Fonts

The font is built using fontmake and gftools post processing script. Tools are all python based, so it must be previously installed.

To install all the Python tools into a virtualenv, do the following:

From terminal:

```

cd your/local/project/directory

#once in the project folder create a virtual environment. 
This step has to be done just once, the first time:

python3 -m venv venv

#activate the virtual environment

source venv/bin/activate

#install the required dependencies

pip install -r requirements.txt

```

Then run the this command:

```
cd sources
gftools builder config.yml
```
