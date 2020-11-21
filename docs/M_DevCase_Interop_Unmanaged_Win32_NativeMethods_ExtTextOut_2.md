# NativeMethods.ExtTextOut Method (SafeHandle, Int32, Int32, ExtTextOutOptions, NativeRectangle, String, UInt32, Int32[])
 

Draws text using the currently selected font, background color, and text color. 

 You can optionally provide dimensions to be used for clipping, opaquing, or both.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", EntryPoint = "ExtTextOutW")]
public static bool ExtTextOut(
	SafeHandle hdc,
	int x,
	int y,
	ExtTextOutOptions options,
	in NativeRectangle rect,
	string text,
	uint count,
	int[] dx
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", EntryPoint := "ExtTextOutW">]
Public Shared Function ExtTextOut ( 
	hdc As SafeHandle,
	x As Integer,
	y As Integer,
	options As ExtTextOutOptions,
	ByRef rect As NativeRectangle,
	text As String,
	count As UInteger,
	dx As Integer()
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hdc As SafeHandle
Dim x As Integer
Dim y As Integer
Dim options As ExtTextOutOptions
Dim rect As NativeRectangle
Dim text As String
Dim count As UInteger
Dim dx As Integer()
Dim returnValue As Boolean

returnValue = NativeMethods.ExtTextOut(hdc, 
	x, y, options, rect, text, count, dx)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", EntryPoint = L"ExtTextOutW")]
static bool ExtTextOut(
	SafeHandle^ hdc, 
	int x, 
	int y, 
	ExtTextOutOptions options, 
	[InAttribute] NativeRectangle% rect, 
	String^ text, 
	unsigned int count, 
	[InAttribute] array<int>^ dx
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", EntryPoint = "ExtTextOutW")>]
static member ExtTextOut : 
        hdc : SafeHandle * 
        x : int * 
        y : int * 
        options : ExtTextOutOptions * 
        rect : NativeRectangle byref * 
        text : string * 
        count : uint32 * 
        dx : int[] -> bool 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the device context.</dd><dt>x</dt><dd>Type: System.Int32<br />The x-coordinate, in logical coordinates, of the reference point used to position the string.</dd><dt>y</dt><dd>Type: System.Int32<br />The y-coordinate, in logical coordinates, of the reference point used to position the string.</dd><dt>options</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ExtTextOutOptions">DevCase.Interop.Unmanaged.Win32.Enums.ExtTextOutOptions</a><br />Specifies how to use the application-defined rectangle.</dd><dt>rect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A pointer to an optional <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that specifies the dimensions, in logical coordinates, of a rectangle that is used for clipping, opaquing, or both.</dd><dt>text</dt><dd>Type: System.String<br />A pointer to a string that specifies the text to be drawn. 

 The string does not need to be zero-terminated, since cbCount specifies the length of the string.</dd><dt>count</dt><dd>Type: System.UInt32<br />The length of the string pointed to by *text* parameter. 

 This value may not exceed `8192`.</dd><dt>dx</dt><dd>Type: System.Int32[]<br />A pointer to an optional array of values that indicate the distance between origins of adjacent character cells. 

 For example, `dx[i]` logical units separate the origins of character cell `i` and character cell `i + 1`.</dd></dl>

#### Return Value
Type: Boolean<br />If the string is drawn, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/dd162713(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/dd162713(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ExtTextOut">ExtTextOut Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />