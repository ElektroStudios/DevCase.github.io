# ItemVerbs Enumeration
 

A verb is a string used to specify a particular action that an item supports. 

 Invoking a verb is equivalent to selecting a command from an item's context menu. 

 Typically, invoking a verb launches a related application. For example, invoking the "open" verb on a ".txt" file opens the file with a text editor, usually Notepad.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ItemVerbs
```

**VB**<br />
``` VB
Public Enumeration ItemVerbs
```

**VB Usage**<br />
``` VB Usage
Dim instance As ItemVerbs
```

**C++**<br />
``` C++
public enum class ItemVerbs
```

**F#**<br />
``` F#
type ItemVerbs
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Shell.ItemVerbs.Open">**Open**</td><td>0</td><td>Opens an item. 

 This is usually the default verb.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ItemVerbs.OpenAs">**OpenAs**</td><td>1</td><td>Opens dialog when no program is associated to the file-extension.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ItemVerbs.Edit">**Edit**</td><td>2</td><td>Opens the default text editor on the item.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ItemVerbs.Explore">**Explore**</td><td>3</td><td>Opens the Windows Explorer in the item Folder.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ItemVerbs.Properties">**Properties**</td><td>4</td><td>Opens the properties window of the item.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ItemVerbs.Find">**Find**</td><td>5</td><td>Starts a search.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ItemVerbs.Print">**Print**</td><td>6</td><td>Start printing the file with the default application.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ItemVerbs.RunAs">**RunAs**</td><td>7</td><td>Opens the run UAC dialog in the file.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ItemVerbs.Copy">**Copy**</td><td>8</td><td>Copies the item.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ItemVerbs.Cut">**Cut**</td><td>9</td><td>Cuts the item.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ItemVerbs.Paste">**Paste**</td><td>10</td><td>Pastes the item.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ItemVerbs.Delete">**Delete**</td><td>11</td><td>Deletes an item. If the Item is inside the recycle bin, it will be permanently deleted.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ItemVerbs.Undelete">**Undelete**</td><td>12</td><td>Undeletes an item from the recycle bin.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />