# NativeMethods.FlashWindowEx Method 
 

Flashes the specified window. 

 It does not change the active state of the window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool FlashWindowEx(
	ref FlashWindowInfo refInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function FlashWindowEx ( 
	ByRef refInfo As FlashWindowInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refInfo As FlashWindowInfo
Dim returnValue As Boolean

returnValue = NativeMethods.FlashWindowEx(refInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool FlashWindowEx(
	FlashWindowInfo% refInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member FlashWindowEx : 
        refInfo : FlashWindowInfo byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_FlashWindowInfo">DevCase.Interop.Unmanaged.Win32.Structures.FlashWindowInfo</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_FlashWindowInfo">FlashWindowInfo</a> structure.</dd></dl>

#### Return Value
Type: Boolean<br />The return value specifies the window's state before the call to the FlashWindowEx(FlashWindowInfo) function. 

 If the window caption was drawn as active before the call, the return value is `true` (`True` in Visual Basic). Otherwise, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms679347%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms679347%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />