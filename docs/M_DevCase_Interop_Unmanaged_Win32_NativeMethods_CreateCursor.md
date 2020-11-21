# NativeMethods.CreateCursor Method 
 

Creates a cursor having the specified size, bit patterns, and hot spot.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static IntPtr CreateCursor(
	IntPtr hInst,
	int xHotSpot,
	int yHotSpot,
	int width,
	int height,
	IntPtr planeAND,
	IntPtr planeXOR
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function CreateCursor ( 
	hInst As IntPtr,
	xHotSpot As Integer,
	yHotSpot As Integer,
	width As Integer,
	height As Integer,
	planeAND As IntPtr,
	planeXOR As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hInst As IntPtr
Dim xHotSpot As Integer
Dim yHotSpot As Integer
Dim width As Integer
Dim height As Integer
Dim planeAND As IntPtr
Dim planeXOR As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateCursor(hInst, 
	xHotSpot, yHotSpot, width, height, 
	planeAND, planeXOR)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static IntPtr CreateCursor(
	IntPtr hInst, 
	int xHotSpot, 
	int yHotSpot, 
	int width, 
	int height, 
	IntPtr planeAND, 
	IntPtr planeXOR
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member CreateCursor : 
        hInst : IntPtr * 
        xHotSpot : int * 
        yHotSpot : int * 
        width : int * 
        height : int * 
        planeAND : IntPtr * 
        planeXOR : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hInst</dt><dd>Type: System.IntPtr<br />A handle to the current instance of the application creating the cursor.</dd><dt>xHotSpot</dt><dd>Type: System.Int32<br />The horizontal position of the cursor's hot spot.</dd><dt>yHotSpot</dt><dd>Type: System.Int32<br />The vertical position of the cursor's hot spot.</dd><dt>width</dt><dd>Type: System.Int32<br />The width of the cursor, in pixels.</dd><dt>height</dt><dd>Type: System.Int32<br />The height of the cursor, in pixels.</dd><dt>planeAND</dt><dd>Type: System.IntPtr<br />An array of bytes that contains the bit values for the AND mask of the cursor, as in a device-dependent monochrome bitmap.</dd><dt>planeXOR</dt><dd>Type: System.IntPtr<br />An array of bytes that contains the bit values for the XOR mask of the cursor, as in a device-dependent monochrome bitmap.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the cursor. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-createcursor" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-createcursor</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />