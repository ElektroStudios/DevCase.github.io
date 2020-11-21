# NativeMethods.GetStateText Method 
 

Retrieves a localized string that describes an object's state for a single predefined state bit flag. 

 Because state values are a combination of one or more bit flags, clients call this function more than once to retrieve all the state strings.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("OleAcc.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GetStateText(
	uint stateBit,
	StringBuilder stateText,
	uint stateTextMax
)
```

**VB**<br />
``` VB
<DllImportAttribute("OleAcc.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetStateText ( 
	stateBit As UInteger,
	<OutAttribute> stateText As StringBuilder,
	stateTextMax As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim stateBit As UInteger
Dim stateText As StringBuilder
Dim stateTextMax As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetStateText(stateBit, 
	stateText, stateTextMax)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"OleAcc.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GetStateText(
	unsigned int stateBit, 
	[OutAttribute] StringBuilder^ stateText, 
	unsigned int stateTextMax
)
```

**F#**<br />
``` F#
[<DllImportAttribute("OleAcc.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetStateText : 
        stateBit : uint32 * 
        stateText : StringBuilder byref * 
        stateTextMax : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>stateBit</dt><dd>Type: System.UInt32<br />One of the object state constants.</dd><dt>stateText</dt><dd>Type: System.Text.StringBuilder<br />Address of a buffer that receives the state text string. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the function returns the state string's length, not including the null character</dd><dt>stateTextMax</dt><dd>Type: System.UInt32<br />The size of the buffer pointed to by the *stateText* parameter. 

 For ANSI strings, this value is measured in bytes. For Unicode strings, it is measured in characters</dd></dl>

#### Return Value
Type: UInt32<br />If successful, and *stateText* is non-a null reference (`Nothing` in Visual Basic), the return value is the number of bytes (ANSI version) or characters (Unicode version) copied into the buffer, not including the null-terminated character. 

 If *stateText* is a null reference (`Nothing` in Visual Basic), then the return value represents the string's length, not including the null character. 

 If the string resource does not exist, or if the *stateText* parameter is not a valid pointer, the return value is zero (0). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/ms696116(v%3Dvs.85)" target="_blank">https://docs.microsoft.com/en-us/previous-versions/ms696116(v%3Dvs.85)</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />