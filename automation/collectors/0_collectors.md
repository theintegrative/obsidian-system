## Why, what is the purpose?
Collectors are the folders with each their rules that will collect repeating notes like daily notes, yearly notes. These notes are usefull for creation of nice pieces of art but are way to systemised to be considered as end products. 

If you are using this with github, this is how you use this:
1. Create a new template
2. Create a new folder with the right prefix- end the -suffix with `-log`

 > The suffixes can be changed in the future if needed,  you are in control
 
Go to the root directory of this vault:
```shell
echo "automation/collectors/{prefix}-log/{prefix}*.md" >> .gitignore
```
 
If the template needs to be triggered when created inside that folder 
4. Go inside settings > community plugins > templater 
5. Go down to folder templates
6. Select the automation/collector folder and choose the right one
7. Then select the note inside automation/templates that will be triggered
