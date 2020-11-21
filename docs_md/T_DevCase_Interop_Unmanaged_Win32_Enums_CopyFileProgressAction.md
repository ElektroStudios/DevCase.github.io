# CopyFileProgressAction Enumeration
 

Specifies the action to take during a copy file progress when using <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_CopyProgressRoutine">Delegates.CopyProgressRoutine</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum CopyFileProgressAction
```

**VB**<br />
``` VB
Public Enumeration CopyFileProgressAction
```

**VB Usage**<br />
``` VB Usage
Dim instance As CopyFileProgressAction
```

**C++**<br />
``` C++
public enum class CopyFileProgressAction
```

**F#**<br />
``` F#
type CopyFileProgressAction
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CopyFileProgressAction.Continue">**Continue**</td><td>0</td><td>Indicates that CopyFileEx should continue the copy operation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CopyFileProgressAction.Cancel">**Cancel**</td><td>1</td><td>Indicates that CopyFileEx should cancel the copy operation and delete the destination file.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CopyFileProgressAction.Stop">**Stop**</td><td>2</td><td>Indicates that CopyFileEx should stop the copy operation. It can be restarted at a later time.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CopyFileProgressAction.Quiet">**Quiet**</td><td>3</td><td>Indicates that CopyFileEx should continue the copy operation, but stop invoking CopyProgressRoutine to report progress.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa363854(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa363854(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />