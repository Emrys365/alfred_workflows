## Alfred workflow: cd

##### Description:

This workflow could help you:
 - open the given path/file in Finder
 - (cmd) reveal the given path/file in Finder
 - (ctrl) open the given path/file in iTerm

It can remember at most MAX_LENGTH history records that you searched before and you can access them again conveniently.

> MAX_LENGTH is a variable that limits the maximum number of records to remember, and you could modify it as you like in `Workflow Configuration (Environment Variables)`.

##### Download:

Go [here](https://github.com/Emrys365/alfred_workflows/blob/master/cd.alfredworkflow) and download it directly.

##### Examples:

+ `cd` + nothing : It will list all the history records.

+ `cd` + `path/file name` : It will open the `path` in Finder or open the `file` directly.

![demo_1](demo_1.png)

+ ` cd` + `any string` : It will list all history records that are possibly relevant to the input.

![demo_2](demo_2.png)

+ `cd` + `path/file name` & press `command` while selecting an item in the list : 

  It will reveal the `path`/`file` in Finder.

  ![demo_3](demo_3.png)

+ `cd` + `path/file name` & press `ctrl` while selecting an item in the list : 

  It will open the `path`/`path of file` in iTerm.

  Note : Please make sure you have installed `iTerm` before you try this !

  ![demo_4](demo_4.png)

