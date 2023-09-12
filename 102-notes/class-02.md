# Class 02 - The Coder's Computer

## Choosing a text editor

When choosing a text editor for programming four important features are:

- code completion, where the editor will autocomplete and suggest things such as HTML tags while you type
- syntax highlighting to improve readibility of code
- comfortable themes that don't hurt the eyes
- customisable with extensions to suit your needs

## Using the command line

Some common command line commands are:

- pwd, which stands for print working directory and tells you the current directory
- ls, which provides a list of files and directories located in the current directory
- cd or change directory which is used to navigate to a directory within the current one
- mkdir, to make a new directory where you located
- touch, used to make a new file

For example, the following sequence of commands will navigate to a directory called _projects_ then create a new directory called _new-project_ before creating a new file called _newfile.md_ and finally navigating back to the previous directory and displaying the contents of the _new-project_ directory.

                cd projects
                mkdir new-project
                touch new-project/newfile.md
                cd ..
                ls projects/new-project
