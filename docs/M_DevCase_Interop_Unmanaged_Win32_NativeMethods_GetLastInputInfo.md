# NativeMethods.GetLastInputInfo Method 
 

Retrieves the time of the last input (mouse or keyboard) event. 

 This function is useful for input idle detection. However, GetLastInputInfo(LastInputInfo) does not provide system-wide user input information across all running sessions. Rather, GetLastInputInfo(LastInputInfo) provides session-specific user input information for only the session that invoked the function

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool GetLastInputInfo(
	ref LastInputInfo refInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetLastInputInfo ( 
	ByRef refInfo As LastInputInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refInfo As LastInputInfo
Dim returnValue As Boolean

returnValue = NativeMethods.GetLastInputInfo(refInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool GetLastInputInfo(
	LastInputInfo% refInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetLastInputInfo : 
        refInfo : LastInputInfo byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_LastInputInfo">DevCase.Interop.Unmanaged.Win32.Structures.LastInputInfo</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_LastInputInfo">LastInputInfo</a> structure that receives the time of the last input event..</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic); otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646302%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646302%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />