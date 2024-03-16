#<p style="text-align: center;">PenpotCommand</p>

This repository will be used to simplify the launch of a local instance of Penpot. You need to have docker-engine installed on your computer. Clone this repository and launch the following command :
``` 
path_to_repository/penpot install
```

You can then restart your terminal to get the updated $PATH and use the command :
```
penpot [start|stop|update|config|backup|install|remove|help]
```

<br/>
## Commands Details

```
penpot start
```
This command launch the instance of Penpot and opens a new tab in the user's default browser.
___

```
penpot stop
```
This command stops the instance of Penpot, but doesn't close any opened tab.
___

```
penpot update
```
This command updates Penpot's version, but needs to be tested further to be sure about its behavior.
___

```
penpot config
```
Not yet implemented !
___

```
penpot backup
```
Not yet implemented !
___

```
penpot install
```
This command installs the files in the right directories and enables the use of the word 'penpot' as a command.
___

```
penpot remove
```
Not yet implemented !
___

```
penpot help
```
This command shows how to use the command.
___