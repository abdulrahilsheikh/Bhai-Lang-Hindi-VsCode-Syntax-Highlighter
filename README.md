# Bhai Lang Hindi VsCode Syntax Highlighter for Visual Studio Code

## Contents

-   [What this extension is](#what-this-extension-is)
-   [What this extension isn't](#what-this-extension-isnt)
-   [Feature list](#feature-list)
    -   [Syntax Highlighting](#syntax-highlighting)
    -   [Commands](#commands)
-   [How to run Bhai Lang Hindi](#how-to-run-bhai-lang-hindi)
- [Credits](#credits)


## What this extension is

This is basic sysntax highlighting tool for Bhai-Lang-Hindi. Just to highlight syntax. This language Bhai Laang Hindi is inspired from the laguage [Bhai-Lang](https://bhailang.js.org/).


## What this extension isn't

-   This extension does not allow you to debug Java or Processing projects.
-   This is **NOT a language server**, and hence cannot provide the features a language server can. And that type of thing is definitely out of the scope of my abilities. Language servers take entire teams from big companies such as Microsoft to make.
    -   This extension cannot provide IntelliSense, for example

## Feature List

### Syntax highlighting

Open any .bhai file and choose "Bhai-Lang-Hindi" from the drop down menu in the bottom right corner. Syntax highlighting is developed using  [Yo Generator](https://yeoman.io/).


### Commands

All the commands are hindi version of python syntaxes. All the hindi commands will function  same as those python english commands.
You have to programme in Bhai Lang Hindi the same way you programme in Python.

### Below is the synatx list for Bhai-Lang_hindi

#### Variables and Literal

|Bhai Lang Hindi Syntax | Python Syntax |
|-----------------------|---------------|
|`अंक`|`int`|
|`दशमलव`|`float`|
|`हां_या_नहीं`|`bool`|
|`वाक्य`|`str`|
|`सच_है_भाई`|`true`|
|`गलत_है_भाई`|`false`|
|`खाली`|`None`|


#### Flow Control and operator

|Bhai Lang Hindi Syntax | Python Syntax |
|-----------------------|---------------|
|`अगर_भाई`|`if`|
|`और_अगर`|`elif`|
|`वर्ना`|`else`|
|`जारी_रखें`|`continue`|
|`रोक_दे`|`break`|
|`लौटाये`|`return`|
|`बदमे_देखेंगे`|`pass`|
|`जबतक_भाई`|`for`|
|`जबकि_भाई`|`while`|

#### Logical operators

|Bhai Lang Hindi Syntax | Python Syntax |
|-----------------------|---------------|
|`और`|`and`|
|`या`|`or`|
|`नहीं`|`not`|
|`अंदर_है_भाई`|`in`|

#### Built-in functions

|Bhai Lang Hindi Syntax | Python Syntax |
|-----------------------|---------------|
|`एब्सॉ`|`abs`|
|`दीखा_भाई`|`print`|
|`श्रेणी`|`range`|


#### Function declaration and class

|Bhai Lang Hindi Syntax | Python Syntax |
|-----------------------|---------------|
|`_बताओ_भाई`|`def`|
|`शुरू_करे_भाई`|`init`|
|`कक्षा`|`class`|
|`खुद`|`self`|

## How to run Bhai Lang Hindi

To run the code first you need to run the Bhai-Lang_Hindi interpreter using python in terminal.

`C:/Users/hp/AppData/Local/Programs/Python/Python3/python.exe G:/bhai-lang-hindi-interpreter.py`

You can get the Bhai-Lang-Hindi interpreter from here -> [Bhai-Lang-Hindi-interpreter.py](https://github.com/abdulrahilsheikh/Bhai-Lang-Hindi_Interpreter)

Then paste the location of your .bhai (Bhai-Lang-Hindi) file in same terminal.

`G/demo.bhai`

Thats it you are done.


# Credits

As this laguage is based on python the tmLanguage.json file is taken from [Microsoft Vscode Github](https://github.com/microsoft/vscode/blob/main/extensions/python/syntaxes/MagicPython.tmLanguage.json) repository and modfied for the current project.
