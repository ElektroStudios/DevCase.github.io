# NativeMethods.DebugSetProcessKillOnExit Method 
 

Sets the action to be performed when the calling thread exits.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool DebugSetProcessKillOnExit(
	bool killOnExit
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function DebugSetProcessKillOnExit ( 
	killOnExit As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim killOnExit As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.DebugSetProcessKillOnExit(killOnExit)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool DebugSetProcessKillOnExit(
	bool killOnExit
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member DebugSetProcessKillOnExit : 
        killOnExit : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>killOnExit</dt><dd>Type: System.Boolean<br />If this parameter is `true` (`True` in Visual Basic), the thread terminates all attached processes on exit (note that this is the default). Otherwise, the thread detaches from all processes being debugged on exit.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-debugsetprocesskillonexit" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-debugsetprocesskillonexit</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />