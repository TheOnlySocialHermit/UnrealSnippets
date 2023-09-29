# UnrealSnippets For Visual Studio 2022

A list of useful Unreal Engine snippets.

Don't know how to use a snippet? They are easy to use, and awesome for improving your workflow!

* Just start typing in the shortcut provided below and then press 'Tab' and the snippet code will be input into your code file, with declarations at certain breakpoints.
* To go between each of the declaration breakpoints, just press 'Tab' and then type in what you want in that breakpoint.
* Once you are happy with the configuration of the snippet, press 'Enter' to finalize the snippet.

# How to install?

Don't know how to get snippets into your Visual Studio Editor? Thats OK i'll walk you through it!

First go ahead and download the .zip of this repo anywhere you wish onto your computer. 
Then Go into that .zip file and copy the 'UnrealSnippets' folder into any folder you wish.
After that, if you want you can delete the .zip file.
Keep note where you put the extracted folder as this is important for when it comes time to put the snippets into the editor.

I know of Three ways to do this personally, and i'll cover all three of them!

From the Editor (Entire Folder):
* Open up your Visual Studio, from here either open a project, a folder, or just 'Continue without code'.
* From there, at the top of the editor click on the 'Tools' Menu and then click 'Code Snippets Manager' (You can also use the hotkey which is - (Hold ctrl -> press K -> then press B))
* Once inside the snippets manager window, there is a dropdown for 'Language' click the dropdown and change it to 'Visual C++'
* From there click the 'Add' button and navigate where you saved the extracted 'UnrealSnippets' Folder.
* Select the 'UnrealSnippets' Folder, and click 'Select Folder'
* Hurray! You now have those snippets added to your editor!

From the Editor (Importing):
* Follow steps 1-3 from the above.
* Now instead of clicking the 'Add' button, click the 'Import' button.
* Navigate to the location of the extracted 'UnrealSnippets' Folder.
* Choose one, all, or any desired specific snippets using the common selection methods (ctrl-A: All, click->shift click: Select All between selections, ctrl click: Add Selections to list of selected)
* Once you have chosen all the desired snippets you wish to import, click 'Open'.
* Hurray! You now have those snippets added to your editor!

From your File Explorer:
* Navigate to where you extracted the 'UnrealSnippets' Folder and go into the folder.
* From there copy any or all the snippets you want installed into your editor.
* Now we will navigate to where the snippets are stored on your local computer. (This location is most commonly inside your: C:\Users\*YourUserName*\OneDrive\Documents\Visual Studio 2022\Code Snippets)
* Inside that folder Navigate into the 'Visual C++\My Code Snippets' Folder.
* Now you can paste them inside of that folder, and Hurray! You have now added those snippets to your editor!
* Note: You can also just paste the whole 'UnrealSnippets' Folder into the 'Visual C++' Folder if you just want the whole folder imported in.



# What is Included?

ForEach snippet. -- Shortcut: ueach

* Creates a C++ ForEach that when ended ends in the body of the loop
* Declarations include: Type, Name of the looping variable, and the name of the Collection to be iterated.


UFUNCTION snippet -- Shortcut: ufunc

* Creates a UFUNCTION that ends at the end of the function declaration.
* Declarations include: Metadata (i.e. BlueprintCallable), Return Type, Function Name, and any Arguments.

UE_LOG snippet -- Shortcut: ulog

* Creates a UE_LOG call that ends at the end of the call line.
* Declartions include: Log Level (i.e. Display, Error, Warning), The Message (pre-wrapped in quotes), and any optional Args for the message.

UPROPERTY snippet -- Shortcut: uprop

* Creates a UPROPERTY variable that ends at the end of the variable declaration.
* Declartions include: Metadata (i.e. EditAnywhere), Type, Variable Name, and Default Value.


That's all for now! I'll keep this repo updated with any more snippets that I find helpful and useful!

Feel free to use these in any way you want, alter them, give them to friends, Hope you find them as useful as I do!
