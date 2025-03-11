# Github Copilot Training

1. Install Github copilot extention in VS Code so we can interact with copilot via chat.
2. Some of the below key board shortcuts to interact with co-pilot. <br>
  a. Ctrl + Enter key: Show combined suggestions. <br>
  b. Alt + ] key: See next suggestion. <br>
  c. Alt + [ key: See previous suggestion. <br>
  d. Ctrl + I key: Suggest Terminal Command. <br>
3. Some of the mentions to make co-pilot easy to understand. <br>
  a. @workspace: Copilot will use the entire project as context. <br>
  b. @terminal: context about the integrated terminal shell and its contents. <br>
  c. `/clear` helps to clean the chat. <br>
  d. `/doc` helps to create the documentation or comment lines. <br>
  e. `/explain` helps to describe the selected code. <br>

## Reverse Engineering

### Here we are going to get help from co-pilot to understand the project structure.
```
@workspace **Reverse Engineering**: Explain me the current project structure
```
### To Understand the code.
select the specific set of code which required to understand.
```
/explain explain me the selected code

or

@workspace /explan explain me the selected code
```
### To Understand the entire file.
```
@workspace /explan explain me the **selected** file.
```
### To understand entire project
```
@workspace explain me the entire project.
```
### To generate comments for the code.
```
@workspace **explain** me the **entire** project.
```
### Refactor the Code.
```
@workspace **refactor** the current file into multiple files.
```
To insert the new file, there will be 3 dots - insert into the file by providing the name and save.

