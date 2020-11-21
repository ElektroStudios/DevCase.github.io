# NativeMethods.SetSysColors Method 
 

Sets the colors for the specified display elements. 

 Display elements are the various parts of a window and the display that appear on the system display screen.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool SetSysColors(
	int amount,
	int[] elements,
	uint[] rgbValues
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SetSysColors ( 
	amount As Integer,
	elements As Integer(),
	rgbValues As UInteger()
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim amount As Integer
Dim elements As Integer()
Dim rgbValues As UInteger()
Dim returnValue As Boolean

returnValue = NativeMethods.SetSysColors(amount, 
	elements, rgbValues)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool SetSysColors(
	int amount, 
	array<int>^ elements, 
	array<unsigned int>^ rgbValues
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SetSysColors : 
        amount : int * 
        elements : int[] * 
        rgbValues : uint32[] -> bool 

```


#### Parameters
&nbsp;<dl><dt>amount</dt><dd>Type: System.Int32<br />The number of display elements in the *elements* array.</dd><dt>elements</dt><dd>Type: System.Int32[]<br />An array of integers that specify the display elements to be changed.</dd><dt>rgbValues</dt><dd>Type: System.UInt32[]<br />An array of COLORREF values that contain the new RGB color values for the display elements in the array pointed to by the *elements* parameter.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic); If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms724940%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms724940%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />