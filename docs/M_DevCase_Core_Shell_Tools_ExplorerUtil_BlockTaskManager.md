# ExplorerUtil.BlockTaskManager Method 
 

Prevents any attempt for the current user from reading and running the 'taskmgr.exe' file and any defined hijack in the system (if any). 

 Note that the file blocking is not permanent. 

 This function will return a FileStream Array that contains the 'taskmgr.exe' file stream(s) opened with Read access and None sharing. 

 So in order to unblock the access to the file(s), just dispose the opened stream(s) or terminate the calling aplication.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static FileStream[] BlockTaskManager()
```

**VB**<br />
``` VB
Public Shared Function BlockTaskManager As FileStream()
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As FileStream()

returnValue = ExplorerUtil.BlockTaskManager()
```

**C++**<br />
``` C++
public:
static array<FileStream^>^ BlockTaskManager()
```

**F#**<br />
``` F#
static member BlockTaskManager : unit -> FileStream[] 

```


#### Return Value
Type: FileStream[]<br />A FileStream Array that contains the 'taskmgr.exe' file stream(s) opened with Read access and None sharing.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim tskmgrFiles As FileStream() = BlockWindowsTaskManager()
For Each fs As FileStream In tskmgrFiles
    Debug.WriteLine(fs.Name)
    ' fs.Close() ' Call this to unblock file access.
Next fs
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ExplorerUtil">ExplorerUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />