# NativeMethods.SendInput Method 
 

Synthesizes keystrokes, mouse motions, and button clicks.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static int SendInput(
	int nInputs,
	Input[] pInputs,
	int cbSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SendInput ( 
	nInputs As Integer,
	pInputs As Input(),
	cbSize As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim nInputs As Integer
Dim pInputs As Input()
Dim cbSize As Integer
Dim returnValue As Integer

returnValue = NativeMethods.SendInput(nInputs, 
	pInputs, cbSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static int SendInput(
	int nInputs, 
	[InAttribute] array<Input>^ pInputs, 
	int cbSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SendInput : 
        nInputs : int * 
        pInputs : Input[] * 
        cbSize : int -> int 

```


#### Parameters
&nbsp;<dl><dt>nInputs</dt><dd>Type: System.Int32<br />The number of structures in the pInputs array.</dd><dt>pInputs</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Input">DevCase.Interop.Unmanaged.Win32.Structures.Input</a>[]<br />An array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Input">Input</a> structures. 

 Each structure represents an event to be inserted into the keyboard or mouse input stream.</dd><dt>cbSize</dt><dd>Type: System.Int32<br />The size, in bytes, of an <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Input">Input</a> structure. 

 If *cbSize* is not the size of an <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Input">Input</a> structure, the function fails.</dd></dl>

#### Return Value
Type: Int32<br />The function returns the number of events that it successfully inserted into the keyboard or mouse input stream. 

 If the function returns zero, the input was already blocked by another thread.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646310%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646310%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />