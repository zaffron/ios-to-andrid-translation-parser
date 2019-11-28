# ios-to-andrid-translation-parser

This simple script will help you to parse your ios translation file into csv format.
Expected type of test cases:
`
xyz = "HELLO";
"zyx" = "yello";
xyz = xyz;
"   xyz " = "   xyz";
"?&(xyz" = "?32 xyz";
`
Please remove the comments if you have any.
And remember, this is a python script so you *must have python installed on your pc or microwave where you executing this*.

## Procedure to parse

1.  Clone the repo
1.  Copy the file you want to translate into the directory(remember to remove all the comments before you copy the translation file)
1.  Open the directory in terminal.
1.  Run `python translation_parser.python` in the opened terminal
1.  It will ask for the filename. Provide the filename of the translation you copied to the directory. Remember the translation file should be on the same directory.
1.  Hit enter after entering name.
1.  Once the process completes, check the directory for the `.csv` file with the same filename.
1.  You are ready to go.

