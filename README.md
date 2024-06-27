#  Familytree

## Creates a Family Tree

##### This python script, when executed, reads "Dasharath.xlsx" and creates an HTML file which can be used to host a demo family tree

##### Modify the spreadsheet to create your own family tree applying the rules of uniqueness below to the spreadsheet columns	   

| Worksheet | Column          | Rule                                                                                     |
|-----------|-----------------|------------------------------------------------------------------------------------------|
|Main       | person          | Each entry in this column must be unique.                                                |
|-----------|-----------------|------------------------------------------------------------------------------------------|
|Main       | person_full     | None                                                                                     |
|-----------|-----------------|------------------------------------------------------------------------------------------|
|Main       | spouse_full     | None                                                                                     |
|-----------|-----------------|------------------------------------------------------------------------------------------|
|Main       | parent          | All except one entry in this column must be present in column `person`.                  |
|-----------|-----------------|------------------------------------------------------------------------------------------|
|Main       | tooltip         | None                                                                                     |
|-----------|-----------------|------------------------------------------------------------------------------------------|
|Main       | spouse          | Each entry in this column must be unique.                                                |
|-----------|-----------------|------------------------------------------------------------------------------------------|
|Main       |                 | When entries from columns `person` and `spouse` are concatenated together, they must     |
|Main       |                 | form a unique set excluding blanks                                                       |
|-----------|-----------------|------------------------------------------------------------------------------------------|
|images     | person          | Entries must be unique, present in either `person` or `spouse` column of worksheet `Main`|
|-----------|-----------------|------------------------------------------------------------------------------------------|
|images     | image           | Each entry in this column must be unique                                                 |
|-----------|-----------------|------------------------------------------------------------------------------------------|

### The HTML file created by python will be rendered on a web page as shown below
![Family_tree.png](https://onedrive.live.com/embed?resid=5C40D3A85A75F1BF%2155960&authkey=%21ADHNdj6-8Zx7dss&width=528&height=812)

