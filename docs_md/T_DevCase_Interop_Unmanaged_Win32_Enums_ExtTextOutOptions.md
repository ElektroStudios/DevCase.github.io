# ExtTextOutOptions Enumeration
 

Specifies how to use the application-defined rectangle. 

 For <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ExtTextOut">ExtTextOut(IntPtr, Int32, Int32, ExtTextOutOptions, NativeRectangle, String, UInt32, Int32[])</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ExtTextOutOptions
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ExtTextOutOptions
```

**VB Usage**<br />
``` VB Usage
Dim instance As ExtTextOutOptions
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ExtTextOutOptions
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ExtTextOutOptions
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExtTextOutOptions.Clipped">**Clipped**</td><td>4</td><td>The text will be clipped to the rectangle.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExtTextOutOptions.GlyphIndex">**GlyphIndex**</td><td>16</td><td>The text array refers to an array returned from `GetCharacterPlacement` function and should be parsed directly by GDI as no further language-specific processing is required. 

 Glyph indexing only applies to TrueType fonts, but the flag can be used for bitmap and vector fonts to indicate that no further language processing is necessary and GDI should process the string directly. 

 Note that all glyph indices are 16-bit values even though the string is assumed to be an array of 8-bit values for raster fonts. 

 For the Unicode version (`ExtTextOutW`), the glyph indices are saved to a metafile. 

 However, to display the correct characters the metafile must be played back using the same font. 

 For the ANSI version (`ExtTextOutA`), the glyph indices are not saved</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExtTextOutOptions.IgnoreLanguage">**IgnoreLanguage**</td><td>4096</td><td>Reserved for system use. 

 If an application sets this flag, it loses international scripting support and in some cases it may display no text at all.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExtTextOutOptions.NumericsLatin">**NumericsLatin**</td><td>2048</td><td>To display numbers, use European digits.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExtTextOutOptions.NumericsLocal">**NumericsLocal**</td><td>1024</td><td>To display numbers, use digits appropriate to the locale.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExtTextOutOptions.Opaque">**Opaque**</td><td>2</td><td>The current background color should be used to fill the rectangle.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExtTextOutOptions.PDY">**PDY**</td><td>8192</td><td>When this is set, the array pointed to by lpDx contains pairs of values. 

 The first value of each pair is, as usual, the distance between origins of adjacent character cells, but the second value is the displacement along the vertical direction of the font.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExtTextOutOptions.RtlReading">**RtlReading**</td><td>2048</td><td>Middle East language edition of Windows: 

 If this value is specified and a Hebrew or Arabic font is selected into the device context, the string is output using right-to-left reading order. 

 If this value is not specified, the string is output in left-to-right order. 

 The same effect can be achieved by setting the `TA_RTLREADING` value in `SetTextAlign`. 

 This value is preserved for backward compatibility.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/dd162713(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/dd162713(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />