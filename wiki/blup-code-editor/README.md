# Blup Code Editor &#x20;

Welcome to the Code Editor section of Blup, your go-to Low Code IDE for Flutter app development! Our versatile code editor is designed to empower developers with the flexibility to code in any language by supporting various file extensions. Whether you're crafting Flutter widgets or diving into backend logic, Blup's intuitive and dynamic code editor ensures a seamless and efficient coding experience. Explore the possibilities and streamline your development process with Blup's adaptable code editing capabilities.



The Code Editor is divided into two parts. Let's understand each one of them in detail:

## File Explorer

On the left side of the editor, you'll find the file explorer, just like you see in Android Studio or Visual Studio Code. It lets you easily check out your project files. This explorer is not just for show – you can do a bunch of things with your project files using it. Let's go through each of them to make sure you're getting the most out of it!\
\
**New File :**  This feature lets you make a new file. When you click it, a window pops up, and you can type in the file name and its extension. If you don't add the extension, it will just make a text file with that name.

**New Dart File :** This functions just like the new file option, but the difference is, if you don't add any extension, it will specifically create a Dart file. This is handy because we're mostly dealing with Flutter projects here.

**New Folder :** This feature allows you to create new folders, helping you organize your projects effectively

**Rename :**  Allows you to rename your files and folders

**Add Packages (pub.dev) :** This feature lets you add any custom library from pub.dev. Clicking on it opens a pop-up displaying popular libraries and a search bar for you to find the one you want to use in your project. It's similar to adding a library from the pubspec.yaml file, but we've made it easier for you. This comes in handy when you want to incorporate various custom libraries from the internet.

**CRUD operations :** You can carry out CRUD operations, such as copying or cutting files or folders, either individually or in multiples, and then paste them to a location. Additionally, you can delete single or multiple files and folders.

**Find in Files :**  This feature enables you to search for specific keywords or anything you need within project files. The search folder depends on where you open this option. If you right-click on a file, it uses the parent folder of that file as the search folder. If you click on a folder, it uses that folder. Similarly, if you open the "Find in Files" using shortcut keys (which we'll discuss later), it takes the root directory as the search folder. The search results provide the exact line number, file path, and a few display lines of the code where the word is present. This feature is particularly useful when working with multiple files and needing to search for something specific.

**Replace in Files :** This feature functions just like "Find in Files," with the added capability of allowing you to replace the searched word with another. You can choose to replace all occurrences of that word or target a specific instance by previewing the code in the search results.

**Reformat Code (With Dart format) :** This feature helps maintain code readability. When writing code, things can get messy. Clicking on this option automatically reformats the code, adhering to Dart standards, and provides you with cleaner and more readable code in return.

### Editor Area

This is your coding space, operating like a traditional editor with a custom-built color scheme for both light and dark modes, enhancing readability and appearance. Right-clicking within the editor unveils various actions, most akin to those found in the file explorer. However, we'll delve into two specific options unique to the editor.

**Go To Declarations:** Clicking this option redirects your cursor to the line in the file where the variable is declared. The editor automatically detects the word if you haven't selected the entire word; if you have, it finds the declaration for the selected part. If no declaration is found, nothing happens.

**Go To Usages :** Clicking this option opens a pop-up displaying all the usages of the particular word. If you haven't selected the word, the editor automatically detects the word at the cursor. If you have selected the word, it finds the usage of the selected part, providing the code snippet, line number, and file path where the word is used. This feature is immensely helpful during coding, widely utilized by developers for efficient coding.

The Editor area offers another feature that enhances coding ease and efficiency: the **QT AI Auto completer**. Let's delve into its details.

QT AI enables you to input prompts, generating code snippets based on the prompt, understanding both the code and file context. It functions as a helpful coding co-pilot, assisting you in effortlessly creating new functionalities and writing logic. The code is automatically generated at the cursor location. For example, if you prompt "Write a function to add two numbers," it will generate a code snippet at the current cursor position, making your coding tasks more convenient.

#### Shortcut Keys

Now that we've covered all the editor functionalities, let's explore the time-saving shortcuts for these features. An editor is incomplete without shortcut keys, and Blup Editor offers several shortcuts for effective coding without relying on your mouse or unnecessary actions. Let's delve into these productivity-enhancing shortcuts.

**Ctrl + F :** Enables you to search for a word within the opened file

**Ctrl  + R :** Enables you to replace a word within the opened file

**Ctrl + Shift + F :** Opens Find in Files dialog

**Ctrl + Shift + R :** Opens Replace in Files dialog

**Ctrl + Mouse left click :** Clicking on a word takes you to its declaration, and if it's the root declaration, it opens the usages for the same word

