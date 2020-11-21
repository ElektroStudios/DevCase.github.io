# NativeMethods.DwmGetColorizationColor Method 
 

Retrieves the current color used for Desktop Window Manager (DWM) glass composition. 

 This value is based on the current color scheme and can be modified by the user. 

 Applications can listen for color changes by handling the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_DwmColorizationColorChanged</a> message.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll")]
public static HResult DwmGetColorizationColor(
	out uint refColor,
	out bool refOpaqueBlend
)
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll">]
Public Shared Function DwmGetColorizationColor ( 
	<OutAttribute> ByRef refColor As UInteger,
	<OutAttribute> ByRef refOpaqueBlend As Boolean
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim refColor As UInteger
Dim refOpaqueBlend As Boolean
Dim returnValue As HResult

returnValue = NativeMethods.DwmGetColorizationColor(refColor, 
	refOpaqueBlend)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll")]
static HResult DwmGetColorizationColor(
	[OutAttribute] unsigned int% refColor, 
	[OutAttribute] bool% refOpaqueBlend
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll")>]
static member DwmGetColorizationColor : 
        refColor : uint32 byref * 
        refOpaqueBlend : bool byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refColor</dt><dd>Type: System.UInt32<br />A pointer to a value that, when this function returns successfully, receives the current color used for glass composition. 

 The color format of the value is `0xAARRGGBB`.</dd><dt>refOpaqueBlend</dt><dd>Type: System.Boolean<br />A pointer to a value that, when this function returns successfully, indicates whether the color is an opaque blend. 

`true` (`True` in Visual Basic) if the color is an opaque blend; otherwise, `false` (`False` in Visual Basic).</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa969513%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa969513%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />