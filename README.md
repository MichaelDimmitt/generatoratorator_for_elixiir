Note: this will probably be a bash cli to start. 😉
FIRST for elixiir, and then for rrhuby, and then for other lannnguages.

## Starting products: (to be built)
project #1:
1. Take current file 
 - create example-template folder, unless it exists
 - add new example to example-template folder
 - do not override existing files
 - add a new name ? [Yn]
 - also create template from "commit sha"
 - multi-file support, would put all files into a folder of the specified template name.
 
project #2
2. promote project templates to user level so that it can be used in other projects

project #3:
3. open example-template folder if it exists, "good --reveal"
 - note: if global templates exist they should be opened too.
 - note: we follow the following precedence
 1. local
 2. global
 3. language template defaults. (these do not show by default but can be requested) (also link to generator website)
 also when we are adding templates in project #1 we need to look for name colisions on higher scopes too!
 
project #4:
generator command history.
every time generator command add it to a history log file

(you could rebuild an entire project if you knew all generator and migration commands!)

project 5:



# Core Questions:
How much do people know about generators?

Why are custom generators not often used in development?
(note: there is an advantage to copy pasting templates, as you see the code before copying it)

# generatoratorator_for_elixiir

1. Grab default generator
2. Note: It is not the way we prefer
3. Make modifications to the file, click button or run command to save the generator in example templates file.
4. Otherwise, at any moment save template example.

another ideas
1. generator migrations. analytics thing. learn what your style is that you do on a project.
2. generator command history

command line features 
1. open example templates shortcut in vscode.
2. save new example template in the project
3. save new example template globally

what mike likes
1. save templates to the example directory. (encourages convention for future team members)
ryan input - probably will only use generator one or couple times. (this will be helpful for future project, need to be global)

what ryan likes
1. example templates need to be promotable.

## distraction, Another idea
```
1. good implementation documentation cli
command === "good"

prompt, what is good about this file ? (title, description)

after, any edits need to be made? sending your to generated file, please wait.
5, 4, 3, 2, 1

also, "good-template" command
good "implementations file" has a see templates link.

good-template --show
```
Sometimes and alternative to this is called an engine like a rails engine that all projects inherit from.
