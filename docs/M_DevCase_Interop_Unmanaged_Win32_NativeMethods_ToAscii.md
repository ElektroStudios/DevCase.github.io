# NativeMethods.ToAscii Method 
 

Translates the specified virtual-key code and keyboard state to the corresponding character or characters. 

 The function translates the code using the input language and physical keyboard layout identified by the keyboard layout handle. 

 To specify a handle to the keyboard layout to use to translate the specified code, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ToAsciiEx">ToAsciiEx(UInt32, UInt32, Byte[], UInt32, UInt32, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static int ToAscii(
	uint vkey,
	uint scanCode,
	byte[] keyState,
	ref uint refChar,
	uint flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function ToAscii ( 
	vkey As UInteger,
	scanCode As UInteger,
	keyState As Byte(),
	ByRef refChar As UInteger,
	flags As UInteger
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim vkey As UInteger
Dim scanCode As UInteger
Dim keyState As Byte()
Dim refChar As UInteger
Dim flags As UInteger
Dim returnValue As Integer

returnValue = NativeMethods.ToAscii(vkey, 
	scanCode, keyState, refChar, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static int ToAscii(
	unsigned int vkey, 
	unsigned int scanCode, 
	array<unsigned char>^ keyState, 
	unsigned int% refChar, 
	unsigned int flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member ToAscii : 
        vkey : uint32 * 
        scanCode : uint32 * 
        keyState : byte[] * 
        refChar : uint32 byref * 
        flags : uint32 -> int 

```


#### Parameters
&nbsp;<dl><dt>vkey</dt><dd>Type: System.UInt32<br />The virtual-key code to be translated</dd><dt>scanCode</dt><dd>Type: System.UInt32<br />The hardware scan code of the key to be translated. 

 The high-order bit of this value is set if the key is up (not pressed).</dd><dt>keyState</dt><dd>Type: System.Byte[]<br />A pointer to a 256-byte array that contains the current keyboard state. Each element (byte) in the array contains the state of one key. 

 If the high-order bit of a byte is set, the key is down (pressed). 

 The low bit, if set, indicates that the key is toggled on. In this function, only the toggle bit of the CAPS LOCK key is relevant. 

 The toggle state of the NUM LOCK and SCROLL LOCK keys is ignored.</dd><dt>refChar</dt><dd>Type: System.UInt32<br />The buffer that receives the translated character or characters.</dd><dt>flags</dt><dd>Type: System.UInt32<br />This parameter must be `1` if a menu is active, or `0` otherwise.</dd></dl>

#### Return Value
Type: Int32<br />If the specified key is a dead key, the return value is negative. Otherwise, it is one of the following values: 

 0 = The specified virtual key has no translation for the current state of the keyboard. 

 1 = One character was copied to the buffer 

 2 = Two characters were copied to the buffer. This usually happens when a dead-key character (accent or diacritic) stored in the keyboard layout cannot be composed with the specified virtual key to form a single character

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646316%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646316%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />