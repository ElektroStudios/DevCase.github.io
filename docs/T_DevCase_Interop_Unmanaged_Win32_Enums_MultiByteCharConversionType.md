# MultiByteCharConversionType Enumeration
 

Flags indicating the conversion type when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MultiByteToWideChar">MultiByteToWideChar(CodePage, MultiByteCharConversionType, Byte[], Int32, Char[], Int32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum MultiByteCharConversionType
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration MultiByteCharConversionType
```

**VB Usage**<br />
``` VB Usage
Dim instance As MultiByteCharConversionType
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class MultiByteCharConversionType
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type MultiByteCharConversionType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MultiByteCharConversionType.PreComposed">**PreComposed**</td><td>1</td><td>Default; do not use with Composite. 

 Always use precomposed characters, that is, characters having a single character value for a base or nonspacing character combination. 

 For example, in the character &#232;, the e is the base character and the accent grave mark is the non-spacing character. 

 If a single Unicode code point is defined for a character, the application should use it instead of a separate base character and a nonspacing character. For example, &#196; is represented by the single Unicode code point LATIN CAPITAL LETTER A WITH DIAERESIS (U+00C4).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MultiByteCharConversionType.Composite">**Composite**</td><td>2</td><td>Always use decomposed characters, that is, characters in which a base character and one or more nonspacing characters each have distinct code point values. 

 For example, &#196; is represented by A + &#168;: LATIN CAPITAL LETTER A (U+0041) + COMBINING DIAERESIS (U+0308). 

 Note that this flag cannot be used with PreComposed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MultiByteCharConversionType.UseGlyphChars">**UseGlyphChars**</td><td>4</td><td>Use glyph characters instead of control characters.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MultiByteCharConversionType.ErrorInvalidChars">**ErrorInvalidChars**</td><td>8</td><td>Fail if an invalid input character is encountered. 

 The function does not drop illegal code points if the application does not set this flag, but instead replaces illegal sequences with U+FFFD (encoded as appropriate for the specified codepage).</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/stringapiset/nf-stringapiset-multibytetowidechar" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/stringapiset/nf-stringapiset-multibytetowidechar</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />