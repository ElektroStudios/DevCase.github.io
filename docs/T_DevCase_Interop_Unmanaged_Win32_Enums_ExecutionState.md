# ExecutionState Enumeration
 

Enables an application to inform the system that it is in use, thereby preventing the system from entering sleep or turning off the display while the application is running.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ExecutionState
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ExecutionState
```

**VB Usage**<br />
``` VB Usage
Dim instance As ExecutionState
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ExecutionState
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ExecutionState
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExecutionState.None">**None**</td><td>0</td><td>Any state. 

 Don't use this value. This value is used to detect a ExecutionState function fail.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExecutionState.AwaymodeRequired">**AwaymodeRequired**</td><td>64</td><td>Enables away mode. This value must be specified with Continuous. 

 Away mode should be used only by media-recording and media-distribution applications that must perform critical background processing on desktop computers while the computer appears to be sleeping. 

 Windows Server 2003: AwaymodeRequired is not supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExecutionState.Continuous">**Continuous**</td><td>2147483648</td><td>Informs the system that the state being set should remain in effect until the next call that uses Continuous and one of the other ExecutionState flags is cleared.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExecutionState.DisplayRequired">**DisplayRequired**</td><td>2</td><td>Forces the display to be on by resetting the display idle timer. 

 Windows 8: This flag can only keep a display turned on, it can't turn on a display that's currently off.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExecutionState.SystemRequired">**SystemRequired**</td><td>1</td><td>Forces the system to be in the working state by resetting the system idle timer.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExecutionState.UserPresent">**UserPresent**</td><td>4</td><td>This value is not supported. 

 If UserPresent is combined with other ExecutionState values, the call will fail and none of the specified states will be set.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/aa373208%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/aa373208%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />