# NativeMethods.SetKeyboardState Method 
 

Copies an array of keyboard key states into the calling thread's keyboard input-state table. 

 This is the same table accessed by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetKeyboardState">GetKeyboardState(Byte[])</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetKeyState">GetKeyState(VirtualKeys)</a> functions. 

 Changes made to this table do not affect keyboard input to any other thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool SetKeyboardState(
	byte[] keyState
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetKeyboardState ( 
	keyState As Byte()
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim keyState As Byte()
Dim returnValue As Boolean

returnValue = NativeMethods.SetKeyboardState(keyState)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool SetKeyboardState(
	[InAttribute] array<unsigned char>^ keyState
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetKeyboardState : 
        keyState : byte[] -> bool 

```


#### Parameters
&nbsp;<dl><dt>keyState</dt><dd>Type: System.Byte[]<br />A pointer to a 256-byte array that contains keyboard key states.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setkeyboardstate" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setkeyboardstate</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />