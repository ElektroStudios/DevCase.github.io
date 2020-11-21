# NativeMethods.ColorHLSToRGB Method 
 

Converts colors from hue-luminance-saturation (HLS) to RGB format.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", ExactSpelling = true, SetLastError = true)]
public static int ColorHLSToRGB(
	ushort hue,
	ushort luminance,
	ushort saturation
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ColorHLSToRGB ( 
	hue As UShort,
	luminance As UShort,
	saturation As UShort
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hue As UShort
Dim luminance As UShort
Dim saturation As UShort
Dim returnValue As Integer

returnValue = NativeMethods.ColorHLSToRGB(hue, 
	luminance, saturation)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", ExactSpelling = true, SetLastError = true)]
static int ColorHLSToRGB(
	unsigned short hue, 
	unsigned short luminance, 
	unsigned short saturation
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", ExactSpelling = true, SetLastError = true)>]
static member ColorHLSToRGB : 
        hue : uint16 * 
        luminance : uint16 * 
        saturation : uint16 -> int 

```


#### Parameters
&nbsp;<dl><dt>hue</dt><dd>Type: System.UInt16<br />The original HLS hue value.</dd><dt>luminance</dt><dd>Type: System.UInt16<br />The original HLS luminance value.</dd><dt>saturation</dt><dd>Type: System.UInt16<br />The original HLS saturation value.</dd></dl>

#### Return Value
Type: Int32<br />Returns the RGB value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-colorhlstorgb" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-colorhlstorgb</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />