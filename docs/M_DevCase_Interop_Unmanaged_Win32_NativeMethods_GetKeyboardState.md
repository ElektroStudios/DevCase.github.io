# NativeMethods.GetKeyboardState Method 
 

Copies the status of the 256 virtual keys to the specified buffer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool GetKeyboardState(
	byte[] keyState
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetKeyboardState ( 
	keyState As Byte()
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim keyState As Byte()
Dim returnValue As Boolean

returnValue = NativeMethods.GetKeyboardState(keyState)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool GetKeyboardState(
	array<unsigned char>^ keyState
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetKeyboardState : 
        keyState : byte[] -> bool 

```


#### Parameters
&nbsp;<dl><dt>keyState</dt><dd>Type: System.Byte[]<br />The 256-byte array that receives the status data for each virtual key.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getkeyboardstate" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getkeyboardstate</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />