# NativeMethods.GetRoleText Method 
 

Retrieves the localized string that describes the object's role for the specified role value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("OleAcc.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GetRoleText(
	uint role,
	StringBuilder roleText,
	uint roleTextMax
)
```

**VB**<br />
``` VB
<DllImportAttribute("OleAcc.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetRoleText ( 
	role As UInteger,
	<OutAttribute> roleText As StringBuilder,
	roleTextMax As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim role As UInteger
Dim roleText As StringBuilder
Dim roleTextMax As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetRoleText(role, 
	roleText, roleTextMax)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"OleAcc.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GetRoleText(
	unsigned int role, 
	[OutAttribute] StringBuilder^ roleText, 
	unsigned int roleTextMax
)
```

**F#**<br />
``` F#
[<DllImportAttribute("OleAcc.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetRoleText : 
        role : uint32 * 
        roleText : StringBuilder byref * 
        roleTextMax : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>role</dt><dd>Type: System.UInt32<br />One of the object role constants.</dd><dt>roleText</dt><dd>Type: System.Text.StringBuilder<br />Address of a buffer that receives the role text string. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the function returns the role string's length, not including the null character.</dd><dt>roleTextMax</dt><dd>Type: System.UInt32<br />The size of the buffer that is pointed to by the *roleText* parameter. 

 For ANSI strings, this value is measured in bytes; for Unicode strings, it is measured in characters.</dd></dl>

#### Return Value
Type: UInt32<br />If successful, and if *roleText* is non-a null reference (`Nothing` in Visual Basic), the return value is the number of bytes (ANSI strings) or characters (Unicode strings) copied into the buffer, not including the terminating null character. 

 If *roleText* is a null reference (`Nothing` in Visual Basic), the return value represents the string's length, not including the null character. 

 If the string resource does not exist, or if the *roleText* parameter is not a valid pointer, the return value is zero (0). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/oleacc/nf-oleacc-getroletexta" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/oleacc/nf-oleacc-getroletexta</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />