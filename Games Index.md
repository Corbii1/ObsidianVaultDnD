List of current campaigns

```button
name Add New World
type note(, split) template
action World
folder 02 - Worlds
prompt true
```
^button-addWorld

```dataview
TABLE file.name as "World"
from !"99 - Meta/Templates"
where type="world"
sort file.name ASC
```