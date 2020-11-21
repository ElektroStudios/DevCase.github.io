# ProgressBarMessages Enumeration
 

The system sends or posts a system-defined message when it communicates with an application. 

 It uses these messages to control the operations of applications and to provide input and other information for applications to process. 

 An application can also send or post system-defined messages. 

 Applications generally use these messages to control the operation of control windows created by using preregistered window classes.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ProgressBarMessages
```

**VB**<br />
``` VB
Public Enumeration ProgressBarMessages
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProgressBarMessages
```

**C++**<br />
``` C++
public enum class ProgressBarMessages
```

**F#**<br />
``` F#
type ProgressBarMessages
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProgressBarMessages.Null">**Null**</td><td>0</td><td>The Null message performs no operation. 

 An application sends the Null message if it wants to post a message that the recipient window will ignore.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProgressBarMessages.SetState">**SetState**</td><td>1040</td><td>Sets the state of the progress bar. 

`wParam` State of the progress bar that is being set. 

`lParam` Must be zero.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ff485990(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ff485990(v=vs.85).aspx</a>

 The definitions can be found in the Windows SDK file: WinUser.h

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />