# NativeMethods.MouseEvent Method 
 

**Note: This API is now obsolete.**

Synthesizes mouse motion and button clicks.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", EntryPoint = "mouse_event")]
[ObsoleteAttribute]
public static void MouseEvent(
	MouseEventFlags flags,
	int x,
	int y,
	int data,
	UIntPtr extraInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", EntryPoint := "mouse_event">]
<ObsoleteAttribute>
Public Shared Sub MouseEvent ( 
	flags As MouseEventFlags,
	x As Integer,
	y As Integer,
	data As Integer,
	extraInfo As UIntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim flags As MouseEventFlags
Dim x As Integer
Dim y As Integer
Dim data As Integer
Dim extraInfo As UIntPtrNativeMethods.MouseEvent(flags, x, y, data, 
	extraInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", EntryPoint = L"mouse_event")]
[ObsoleteAttribute]
static void MouseEvent(
	MouseEventFlags flags, 
	int x, 
	int y, 
	int data, 
	UIntPtr extraInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", EntryPoint = "mouse_event")>]
[<ObsoleteAttribute>]
static member MouseEvent : 
        flags : MouseEventFlags * 
        x : int * 
        y : int * 
        data : int * 
        extraInfo : UIntPtr -> unit 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseEventFlags">DevCase.Interop.Unmanaged.Win32.Enums.MouseEventFlags</a><br />Controls various aspects of mouse motion and button clicking.</dd><dt>x</dt><dd>Type: System.Int32<br />The mouse's absolute position along the x-axis or its amount of motion since the last mouse event was generated, depending on the setting of <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseEventFlags">Absolute</a>. 

 Absolute data is specified as the mouse's actual x-coordinate; relative data is specified as the number of mickeys moved. 

 A mickey is the amount that a mouse has to move for it to report that it has moved.</dd><dt>y</dt><dd>Type: System.Int32<br />The mouse's absolute position along the y-axis or its amount of motion since the last mouse event was generated, depending on the setting of <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MouseEventFlags">Absolute</a>. 

 Absolute data is specified as the mouse's actual y-coordinate; relative data is specified as the number of mickeys moved. 

 A mickey is the amount that a mouse has to move for it to report that it has moved.</dd><dt>data</dt><dd>Type: System.Int32<br />Specifies additional info for *flags* parameter.</dd><dt>extraInfo</dt><dd>Type: System.UIntPtr<br />An additional value associated with the mouse event. An application calls GetMessageExtraInfo function to obtain this extra information.</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646260%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646260%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />