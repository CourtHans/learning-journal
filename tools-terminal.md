# Class 2: The Coder's Computer

## Text Editors

The main requirement for choosing a text editor is simply this: *which one do you like the best?*

If you were to conduct a google search for [“best text editor”]( https://lmgtfy.com/?q=best+text+editor) you’d get a myriad of results, but each is opinion-based and unique to the tasks in front of the developer. However, a few features you should look for are:

1. *Code completion* – like the feature in Microsoft Excel that provides suggested formulas, this feature can help you work faster by offering predictive suggestions. Code completion can also help you close tags, assisting in clean coding.

2. *Syntax highlighting* – syntax highlighting color codes different attributes and elements, making your written code easier to read/interpret (also a useful tool for spotting coding errors)

3. *A nice variety of themes* – a text editor that provides theme options can help you reduce eyestrain through selection of different background and text colors.

4. *A robust extension list* – this is your a la carte list for expanding functionality of your chosen tool! As your skills and needs grow, a variety of extension options can help refine your tool to keep up with your expanding skillset and project demands.

As with anything, choosing the right tool for the job helps you create and deliver the most elegant products in the most efficient manner.

There are text editors that come standard with your computer (TextEdit and Notepad are the most common), though these are often bare-bones and provide extremely limited functionality. There are also 3rd party options that can be downloaded and installed to your computer; examples include: Notepad++, BB Edit, Visual Studio Code, Atom, Brackets, and Sublime Text. Some are free and some require purchase of a license.

If you’re looking for a tool that does MORE than just help you manage text, you may want to consider an IDE (Integrated Development Environment). An IDE is “a suite of different software all coming together. An IDE is a text editor, a file manager, a compiler, and a debugger all in one software package.”

### Linux Tutorial

Opening a terminal in a Mac - you'll find the program Terminal under Applications -> Utilities. An easy way to get to it is the key combination 'command + space' which will bring up Spotlight, then start typing Terminal and it will soon show up.

The file system under Linux is a hierarchical structure. At the very top of the structure is what's called the root directory. It is denoted by a single slash ( / ). It has subdirectories, they have subdirectories and so on.

The command line has a nice little mechanism to help us in this respect. It's called Tab Completion. When you start typing a path (anywhere on the command line, you're not just limited to certain commands) you may hit the Tab key on your keyboard at any time which will invoke an auto complete action.

>Reminder: Linux is case-sensitive.

## Glossary

**GUI** – graphical user interface

**Command line** - A command line, or terminal, is a text-based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

**Option**- A command line, or terminal, is a text-based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

**Shell**- a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you.

**cd**- change direction (usually run with a single command line argument which is the location we would like to change into)

**pwd**- print working directory. As you're moving around, it can be easy to lose track of where you are at. Make use of this command often so as to remind yourself where you presently are.

**ls**- list

**path**- a path is a means to get to a particular file or directory on the system. There are 2 types of paths we can use, *absolute* and *relative*.

**Absolute paths**- specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )

**Relative paths**- specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.

`~` **(tilde)** - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents

`.` **(dot)** - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).

`..`**(dotdot)**- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.

**file**- obtain information about what type of file a file or directory is.

**ls -a** - List the contents of a directory, including hidden files.
