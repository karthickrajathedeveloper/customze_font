## FontConvert Instructions
 This guide provides instructions for unzipping the FontConvert folder, navigating to the directory via command prompt, and using the fontconvert command.

## Unzip the FontConvert Folder
```
1. Locate the FontConvert folder in your directory.
2. Right-click on the FontConvert folder.
3. Select "Extract All..." from the context menu.
```
## Follow the prompts to unzip the folder to your desired location.
# Open the Command Prompt
```
Press Win + R to open the Run dialog box.
Type cmd and press Enter to open the command prompt.
```
# Navigate to the FontConvert Directory
In the command prompt, enter the path name for the `FontConvert` directory using the cd command. For example:
```
sh
cd C:\2024\New folder\FontConvert\fontconvert
```
Press Enter to change the directory to the FontConvert folder.

## Using the fontconvert Command
In the command prompt, enter the fontconvert command with the required parameters. The usage is as follows:

sh
```
fontconvert fontfile size [first] [last]
```
 - fontfile: The name of the font file you want to convert.
 - size: The size of the font.
-  [first]: (Optional) The first character to convert.
-  [last]:  (Optional) The last character to convert.
To generate a header file (.h), redirect the output of the fontconvert command to a file. For example:

sh
```
fontconvert myfont.ttf 12 > myfont.h
```
This will create a file named `myfont.h` with the converted font data.

Example
sh
```
cd C:\2024\New folder\FontConvert
fontconvert myfont.ttf 12 > myfont.h
```
This example navigates to the FontConvert directory, converts the myfont.ttf file with a size of 12, and outputs the result to myfont.h.
