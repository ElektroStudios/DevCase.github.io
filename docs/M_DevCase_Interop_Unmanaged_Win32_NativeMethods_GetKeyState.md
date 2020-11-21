# NativeMethods.GetKeyState Method (VirtualKeys)
 

Retrieves the status of the specified virtual key. 

 The status specifies whether the key is up, down, or toggled (on, off—alternating each time the key is pressed).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static short GetKeyState(
	VirtualKeys vKey
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetKeyState ( 
	vKey As VirtualKeys
) As Short
```

**VB Usage**<br />
``` VB Usage
Dim vKey As VirtualKeys
Dim returnValue As Short

returnValue = NativeMethods.GetKeyState(vKey)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static short GetKeyState(
	VirtualKeys vKey
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetKeyState : 
        vKey : VirtualKeys -> int16 

```


#### Parameters
&nbsp;<dl><dt>vKey</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_VirtualKeys">DevCase.Interop.Unmanaged.Win32.Enums.VirtualKeys</a><br />The virtual-key code. 

 You can use left- and right-distinguishing constants to specify certain keys. 

 See Virtual-Key Codes: <a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd375731%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd375731%28v=vs.85%29.aspx</a></dd></dl>

#### Return Value
Type: Int16<br />If the high-order bit is `1`, the key is down; otherwise, it is up. 

 If the low-order bit is `1`, the key is toggled. 

 A key, such as the `CAPS LOCK` key, is toggled if it is turned on. The key is off and untoggled if the low-order bit is `0`. 

 A toggle key's indicator light (if any) on the keyboard will be on when the key is toggled, and off when the key is untoggled.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646301%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646301%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetKeyState">GetKeyState Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />