# NativeMethods.ColorRGBToHLS Method 
 

Converts colors from RGB to hue-luminance-saturation (HLS) format

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", ExactSpelling = true, SetLastError = true)]
public static void ColorRGBToHLS(
	int rgb,
	out ushort refHUE,
	out ushort refLuminance,
	out ushort refSaturation
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Sub ColorRGBToHLS ( 
	rgb As Integer,
	<OutAttribute> ByRef refHUE As UShort,
	<OutAttribute> ByRef refLuminance As UShort,
	<OutAttribute> ByRef refSaturation As UShort
)
```

**VB Usage**<br />
``` VB Usage
Dim rgb As Integer
Dim refHUE As UShort
Dim refLuminance As UShort
Dim refSaturation As UShort

NativeMethods.ColorRGBToHLS(rgb, refHUE, refLuminance, 
	refSaturation)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", ExactSpelling = true, SetLastError = true)]
static void ColorRGBToHLS(
	int rgb, 
	[OutAttribute] unsigned short% refHUE, 
	[OutAttribute] unsigned short% refLuminance, 
	[OutAttribute] unsigned short% refSaturation
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", ExactSpelling = true, SetLastError = true)>]
static member ColorRGBToHLS : 
        rgb : int * 
        refHUE : uint16 byref * 
        refLuminance : uint16 byref * 
        refSaturation : uint16 byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>rgb</dt><dd>Type: System.Int32<br />The original RGB color.</dd><dt>refHUE</dt><dd>Type: System.UInt16<br />A pointer to a value that, when this method returns successfully, receives the HLS hue value.</dd><dt>refLuminance</dt><dd>Type: System.UInt16<br />A pointer to a value that, when this method returns successfully, receives the HLS luminance value.</dd><dt>refSaturation</dt><dd>Type: System.UInt16<br />A pointer to a value that, when this method returns successfully, receives the HLS saturation value.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-colorrgbtohls" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-colorrgbtohls</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />