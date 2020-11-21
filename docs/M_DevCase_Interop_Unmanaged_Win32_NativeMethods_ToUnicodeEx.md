# NativeMethods.ToUnicodeEx Method 
 

Translates the specified virtual-key code and keyboard state to the corresponding Unicode character or characters.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, ExactSpelling = true)]
public static int ToUnicodeEx(
	uint wVirtKey,
	uint wScanCode,
	byte[] lpKeyState,
	StringBuilder pwszBuff,
	int cchBuff,
	uint wFlags,
	IntPtr dwhkl
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, ExactSpelling := true>]
Public Shared Function ToUnicodeEx ( 
	wVirtKey As UInteger,
	wScanCode As UInteger,
	lpKeyState As Byte(),
	<OutAttribute> pwszBuff As StringBuilder,
	cchBuff As Integer,
	wFlags As UInteger,
	dwhkl As IntPtr
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim wVirtKey As UInteger
Dim wScanCode As UInteger
Dim lpKeyState As Byte()
Dim pwszBuff As StringBuilder
Dim cchBuff As Integer
Dim wFlags As UInteger
Dim dwhkl As IntPtr
Dim returnValue As Integer

returnValue = NativeMethods.ToUnicodeEx(wVirtKey, 
	wScanCode, lpKeyState, pwszBuff, 
	cchBuff, wFlags, dwhkl)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, ExactSpelling = true)]
static int ToUnicodeEx(
	unsigned int wVirtKey, 
	unsigned int wScanCode, 
	array<unsigned char>^ lpKeyState, 
	[OutAttribute] StringBuilder^ pwszBuff, 
	int cchBuff, 
	unsigned int wFlags, 
	IntPtr dwhkl
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, ExactSpelling = true)>]
static member ToUnicodeEx : 
        wVirtKey : uint32 * 
        wScanCode : uint32 * 
        lpKeyState : byte[] * 
        pwszBuff : StringBuilder byref * 
        cchBuff : int * 
        wFlags : uint32 * 
        dwhkl : IntPtr -> int 

```


#### Parameters
&nbsp;<dl><dt>wVirtKey</dt><dd>Type: System.UInt32<br />The virtual-key code to be translated. 

 See Virtual-Key Codes: <a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd375731%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd375731%28v=vs.85%29.aspx</a></dd><dt>wScanCode</dt><dd>Type: System.UInt32<br />The hardware scan code of the key to be translated. 

 The high-order bit of this value is set if the key is up.</dd><dt>lpKeyState</dt><dd>Type: System.Byte[]<br />A pointer to a 256-byte array that contains the current keyboard state. 

 Each element (byte) in the array contains the state of one key. 

 If the high-order bit of a byte is set, the key is down.</dd><dt>pwszBuff</dt><dd>Type: System.Text.StringBuilder<br />The buffer that receives the translated Unicode character or characters. 

 However, this buffer may be returned without being null-terminated even though the variable name suggests that it is null-terminated.</dd><dt>cchBuff</dt><dd>Type: System.Int32<br />The size, in characters, of the buffer pointed to by the *pwszBuff* parameter.</dd><dt>wFlags</dt><dd>Type: System.UInt32<br />The behavior of the function. 

 If bit 0 is set, a menu is active. 

 Bits 1 through 31 are reserved.</dd><dt>dwhkl</dt><dd>Type: System.IntPtr<br />The input locale identifier used to translate the specified code. 

 This parameter can be any input locale identifier previously returned by the `LoadKeyboardLayout` function.</dd></dl>

#### Return Value
Type: Int32<br />The function returns one of the following values. 





 -1: 

 The specified virtual key is a dead-key character (accent or diacritic). 

 This value is returned regardless of the keyboard layout, even if several characters have been typed and are stored in the keyboard state. 

 If possible, even with Unicode keyboard layouts, the function has written a spacing version of the dead-key character to the buffer specified by *pwszBuff*. 

 For example, the function writes the character SPACING ACUTE (`0x00B4`), rather than the character `NON_SPACING` ACUTE (`0x0301`). 





 0: 

 The specified virtual key has no translation for the current state of the keyboard. 

 Nothing was written to the buffer specified by *pwszBuff*. 





 1: 

 One character was written to the buffer specified by *pwszBuff*. 





 2 ≤: 

 Two or more characters were written to the buffer specified by *pwszBuff*. 

 The most common cause for this is that a dead-key character (accent or diacritic) stored in the keyboard layout could not be combined with the specified virtual key to form a single character. 

 However, the buffer may contain more characters than the return value specifies. 

 When this happens, any extra characters are invalid and should be ignored.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646322%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646322%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />