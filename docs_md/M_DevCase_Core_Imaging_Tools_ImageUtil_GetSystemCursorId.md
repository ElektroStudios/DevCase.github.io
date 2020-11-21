# ImageUtil.GetSystemCursorId Method 
 

Gets the (handle)identifier of the current system cursor.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static SystemCursorId GetSystemCursorId()
```

**VB**<br />
``` VB
Public Shared Function GetSystemCursorId As SystemCursorId
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As SystemCursorId

returnValue = ImageUtil.GetSystemCursorId()
```

**C++**<br />
``` C++
public:
static SystemCursorId GetSystemCursorId()
```

**F#**<br />
``` F#
static member GetSystemCursorId : unit -> SystemCursorId 

```


#### Return Value
Type: <a href="T_DevCase_Core_Imaging_SystemCursorId">SystemCursorId</a><br />The (handle)identifier of the current system cursor.

## Examples
This is a code example. 
**VB**<br />
``` VB
Me.Cursor = Cursors.Cross
Dim cursorId As SystemCursorId = GetSystemCursorId()
Console.WriteLine(cursorId.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />