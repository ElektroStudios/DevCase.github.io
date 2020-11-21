# NativeMethods.BlockInput Method 
 

Blocks keyboard and mouse input events from reaching applications. 

 Note that only the thread that blocked input can successfully unblock input.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool BlockInput(
	bool blockIt
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function BlockInput ( 
	blockIt As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim blockIt As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.BlockInput(blockIt)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool BlockInput(
	bool blockIt
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member BlockInput : 
        blockIt : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>blockIt</dt><dd>Type: System.Boolean<br />The function's purpose. 

 If this parameter is `true` (`True` in Visual Basic), keyboard and mouse input events are blocked. 

 If this parameter is `false` (`False` in Visual Basic), keyboard and mouse events are unblocked.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If input is already blocked, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646290%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646290%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />