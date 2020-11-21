# NativeMethods.GetMouseMovePointsEx Method 
 

Retrieves a history of up to 64 previous coordinates of the mouse or pen.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static int GetMouseMovePointsEx(
	uint mouseMovePointSize,
	ref MouseMovePoint refMouseMovePoint,
	MouseMovePoint[] buffer,
	int bufferPoints,
	GetMouseMovePointsResolution resolution
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetMouseMovePointsEx ( 
	mouseMovePointSize As UInteger,
	ByRef refMouseMovePoint As MouseMovePoint,
	<OutAttribute> buffer As MouseMovePoint(),
	bufferPoints As Integer,
	resolution As GetMouseMovePointsResolution
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim mouseMovePointSize As UInteger
Dim refMouseMovePoint As MouseMovePoint
Dim buffer As MouseMovePoint()
Dim bufferPoints As Integer
Dim resolution As GetMouseMovePointsResolution
Dim returnValue As Integer

returnValue = NativeMethods.GetMouseMovePointsEx(mouseMovePointSize, 
	refMouseMovePoint, buffer, bufferPoints, 
	resolution)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static int GetMouseMovePointsEx(
	unsigned int mouseMovePointSize, 
	MouseMovePoint% refMouseMovePoint, 
	[InAttribute] [OutAttribute] array<MouseMovePoint>^ buffer, 
	int bufferPoints, 
	GetMouseMovePointsResolution resolution
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetMouseMovePointsEx : 
        mouseMovePointSize : uint32 * 
        refMouseMovePoint : MouseMovePoint byref * 
        buffer : MouseMovePoint[] byref * 
        bufferPoints : int * 
        resolution : GetMouseMovePointsResolution -> int 

```


#### Parameters
&nbsp;<dl><dt>mouseMovePointSize</dt><dd>Type: System.UInt32<br />The size, in bytes, of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MouseMovePoint">MouseMovePoint</a> structure.</dd><dt>refMouseMovePoint</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MouseMovePoint">DevCase.Interop.Unmanaged.Win32.Structures.MouseMovePoint</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MouseMovePoint">MouseMovePoint</a> structure containing valid mouse coordinates (in screen coordinates). It may also contain a time stamp. 

 The GetMouseMovePointsEx(UInt32, MouseMovePoint, MouseMovePoint[], Int32, GetMouseMovePointsResolution) function searches for the point in the mouse coordinates history. 

 If the function finds the point, it returns the last *bufferPoints* prior to and including the supplied point. 

 If your application supplies a time stamp, the GetMouseMovePointsEx(UInt32, MouseMovePoint, MouseMovePoint[], Int32, GetMouseMovePointsResolution) function will use it to differentiate between two equal points that were recorded at different times. 

 An application should call this function using the mouse coordinates received from the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_MouseMove</a> message and convert them to screen coordinates.</dd><dt>buffer</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MouseMovePoint">DevCase.Interop.Unmanaged.Win32.Structures.MouseMovePoint</a>[]<br />A pointer to a buffer that will receive the points. It should be at least `mouseMovePointSize * bufferPoints` in size.</dd><dt>bufferPoints</dt><dd>Type: System.Int32<br />The number of points to be retrieved.</dd><dt>resolution</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_GetMouseMovePointsResolution">DevCase.Interop.Unmanaged.Win32.Enums.GetMouseMovePointsResolution</a><br />The resolution desired.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value is the number of points in the buffer. Otherwise, the function returns –1.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getmousemovepointsex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getmousemovepointsex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />