# NativeMethods.GetAsyncKeyState Method (Int32)
 

Determines whether a key is up or down at the time the function is called, and whether the key was pressed after a previous call to GetAsyncKeyState(Int32).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static short GetAsyncKeyState(
	int vKey
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function GetAsyncKeyState ( 
	vKey As Integer
) As Short
```

**VB Usage**<br />
``` VB Usage
Dim vKey As Integer
Dim returnValue As Short

returnValue = NativeMethods.GetAsyncKeyState(vKey)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static short GetAsyncKeyState(
	int vKey
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member GetAsyncKeyState : 
        vKey : int -> int16 

```


#### Parameters
&nbsp;<dl><dt>vKey</dt><dd>Type: System.Int32<br />The virtual-key code. 

 You can use left- and right-distinguishing constants to specify certain keys. 

 See Virtual-Key Codes: <a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd375731%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd375731%28v=vs.85%29.aspx</a></dd></dl>

#### Return Value
Type: Int16<br />If the function succeeds, the return value specifies whether the key was pressed since the last call to GetAsyncKeyState(Int32), and whether the key is currently up or down. 

 If the most significant bit is set, the key is down, and if the least significant bit is set, the key was pressed after the previous call to GetAsyncKeyState(Int32). 

 However, you should not rely on this last behavior. 



 The return value is zero for the following cases: 

 The current desktop is not the active desktop. 

 The foreground thread belongs to another process and the desktop does not allow the hook or the journal record.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646310%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646310%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetAsyncKeyState">GetAsyncKeyState Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />