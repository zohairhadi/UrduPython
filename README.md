# UrduPython
> Ever had that random thought of programming in Urdu? Well, you're at the right place.

Programming Language in Urdu, based on Python - اردو میں کوڈ لکھیں

## Pre-requisites
- Python 3+
- Pip
- (optional but recommended) Virtual environment, like ```conda``` or ```virtualenv```

## Why?
Just look at how beautiful it is :)

### Side by Side Comparison of UrduPython vs Python
![Side by side comparison of UrduPython vs Python](./images/side-by-side-loop-code.png)

### It works!
![Running UrduPython code](./images/urdupython-loop-running-example.png)

## How to Install
### Pip
If you've installed ```pip```, you can install UrduPython from [Test PyPI](https://test.pypi.org/project/urdupython/) using the following command:
```
pip install -i https://test.pypi.org/pypi/ --extra-index-url https://pypi.org/simple  urdupython
```

### Source
1. Download this repo as a ZIP, or clone it via Git.
2. Open the repo's folder in your Terminal.
3. Run ```pip install -e .```

## How to Use
1. Create a new file in a folder.
2. Write some Urdu code in this new file.
The mappings are as following:

| Python (original)   | 🇵🇰 Ur          |
| -------------       | ------------- |
|    ```print```             |       لکھو|
|    ```if```                |       اگر|
|    ```elif```              |       ورنہاگر|
|    ```else```              |       ورنہ|
|    ```while```             |       جبتک|
|    ```for```               |       جو|
|    ```in```               |       اندر|
|    ```input```             |       داخله|
|    ```break```             |       توڑ|
|    ```continue```          |       جاری|
|    ```pass```              |       گزر|
|    ```True```              |       حق|
|    ```False```             |       باطل|
|    ```is```                |       ہے|
|    ```class```             |       طبقه|
|    ```def```               |       وضح|
|    ```init```              |       ابتدا|
|    ```self```              |       خود|
|    ```return```            |       واپس|
|    ```string```            |       ستلی|
|    ```str```               |   ستل|
|    ```append```                |   شامل|
|    ```pop```               |   نکل|
|    ```and```               |   اور|
|    ```or```                   |   یا|
|    ```all```               |   سب|
|    ```any```               |   کوئ|
|    ```None```              |   ندارد
|    ```,```                |       ،       |
|    ```.```                |       ۔|
|    ```0```                 |       ۰|
|    ```1```                 |       ۱|
|    ```2```                 |       ۲|
|    ```3```                 |       ۳|
|    ```4```                 |       ۴|
|    ```5```                 |       ۵|
|    ```6```                 |       ۶|
|    ```7```                 |       ۷|
|    ```8```                 |       ۸|
|    ```9```                 |       ۹|

Find the whole list of keywords [here](./urdupython/languages/ur/ur_native.lang.yaml). Don't worry if you can't find a mapping, you can also use English Python!

An example of a Hello World Program:
```
print ("Hello world!")
```
would be
```
لکھو ("Hello world!")
```
There are many more sample codes available [here](./urdupython/samples)

3. Open a Terminal in the folder of this file.
4. Run the code in one command: ```urdupython <NAME_OF_YOUR_FILE>```

For more help, run ```urdupython --help```. For better understanding, do run the sample code files in the "samples" folder.

## Guide
### For macOS
Use TextEdit (default text editor) to write Urdu code. Activate right-to-left typing through Menu: Format->Text->Writing Direction->Right-to-Left

### For Windows
Download and install Notepad++. Right click and activate RTL (Right-to-left).

### For Linux
Open gEdit (or any similar text-editing program), and start coding right away.

## Tests
### Platform(s) tested on
- macOS Big Sur 11.1
- Termux (Android)
- Ubuntu 20.04.3 LTS
