# GraphicalUtil.ShowSaveFileDialog Method 
 

Opens a SaveFileDialog dialog and returns the selected filepath.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ShowSaveFileDialog(
	string fileExtension,
	string defaultFilename,
	string filter,
	string dialogTitle = "Save File...",
	string initialDirectory = ""
)
```

**VB**<br />
``` VB
Public Shared Function ShowSaveFileDialog ( 
	fileExtension As String,
	defaultFilename As String,
	filter As String,
	Optional dialogTitle As String = "Save File...",
	Optional initialDirectory As String = ""
) As String
```

**VB Usage**<br />
``` VB Usage
Dim fileExtension As String
Dim defaultFilename As String
Dim filter As String
Dim dialogTitle As String
Dim initialDirectory As String
Dim returnValue As String

returnValue = GraphicalUtil.ShowSaveFileDialog(fileExtension, 
	defaultFilename, filter, dialogTitle, 
	initialDirectory)
```

**C++**<br />
``` C++
public:
static String^ ShowSaveFileDialog(
	String^ fileExtension, 
	String^ defaultFilename, 
	String^ filter, 
	String^ dialogTitle = L"Save File...", 
	String^ initialDirectory = L""
)
```

**F#**<br />
``` F#
static member ShowSaveFileDialog : 
        fileExtension : string * 
        defaultFilename : string * 
        filter : string * 
        ?dialogTitle : string * 
        ?initialDirectory : string 
(* Defaults:
        let _dialogTitle = defaultArg dialogTitle "Save File..."
        let _initialDirectory = defaultArg initialDirectory ""
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>fileExtension</dt><dd>Type: System.String<br />The file extension.</dd><dt>defaultFilename</dt><dd>Type: System.String<br />The default filename.</dd><dt>filter</dt><dd>Type: System.String<br />The file filter.</dd><dt>dialogTitle (Optional)</dt><dd>Type: System.String<br />The dialog title.</dd><dt>initialDirectory (Optional)</dt><dd>Type: System.String<br />The dialog's initial directory.</dd></dl>

#### Return Value
Type: String<br />If the dialog succeed, the return value is the selected filepath of the SaveFileDialog, if the dialog is canceled, the return value is String.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim filePath As String =
   ShowSaveFileDialog(defaultFilename:="My TextFile",
                      fileExtension:="*.txt",
                      filter:="Text File|*.txt",
                      dialogTitle:="Save Text File As...",
                      initialDirectory:=My.Application.Info.DirectoryPath)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />