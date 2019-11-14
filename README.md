 # SymoblicateCrash-Script
 
 This shell script will convert the desymoblised crashes files to symblise them.
 
 It needs few inputs:
 
 1. dSYM file(This file must be from the crashed app build)
 2. Crash file.
 
 Preperation :
 
 1. Create a folder for dSYM and place the dSYM file in it.
 2. Create a folder for crash filder and place all crash files which was generated on same dSYM.
 
 
 Execution: 
 Generally we will execute the shell script as follows:
 
 sh<one space><scriptName>
 
 For our case: We need to two parameter to pass 
 
 Execution command: 
 sh Symbolicate<one space><dSYMFolderPath><one space><Crash files folder>
 Example: sh Symbolicate /Users/iOSSprinter/DSYMFolder/DSYM/Product.app.dSYM/Contents/Resources/DWARF/Product /Users/iOSSprinter/CrashFilesFolder
 
