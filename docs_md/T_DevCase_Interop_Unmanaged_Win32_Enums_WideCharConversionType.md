# WideCharConversionType Enumeration
 

Flags indicating the conversion type when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WideCharToMultiByte">WideCharToMultiByte(CodePage, WideCharConversionType, String, Int32, StringBuilder, Int32, String, Boolean)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum WideCharConversionType
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration WideCharConversionType
```

**VB Usage**<br />
``` VB Usage
Dim instance As WideCharConversionType
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class WideCharConversionType
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type WideCharConversionType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WideCharConversionType.CompositeCheck">**CompositeCheck**</td><td>512</td><td>Convert composite characters, consisting of a base character and a nonspacing character, each with different character values. 

 Translate these characters to precomposed characters, which have a single character value for a base-nonspacing character combination. For example, in the character &#232;, the e is the base character and the accent grave mark is the nonspacing character. 

 Your application can combine CompositeCheck with any one of the following flags: 

Defaultchar, DiscardNonSpacingChars and SeparateChars

 These flags determine the behavior of the function when no precomposed mapping for a base-nonspacing character combination in a Unicode string is available. If none of these flags is supplied, the function behaves as if the SeparateChars flag is set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WideCharConversionType.DiscardNonSpacingChars">**DiscardNonSpacingChars**</td><td>16</td><td>Discard non-spacing characters during conversion.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WideCharConversionType.SeparateChars">**SeparateChars**</td><td>32</td><td>Default. Generate separate characters during conversion.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WideCharConversionType.Defaultchar">**Defaultchar**</td><td>64</td><td>Replace exceptions with the default character during conversion.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WideCharConversionType.ErrorInvalidChars">**ErrorInvalidChars**</td><td>128</td><td>Fail (by returning 0 and setting the last-error code to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_NO_UNICODE_TRANSLATION</a>) if an invalid input character is encountered. 

 If this flag is not set, the function replaces illegal sequences with U+FFFD (encoded as appropriate for the specified codepage) and succeeds by returning the length of the converted string. 

 Note that this flag only applies when `codePage` parameter is specified as <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CodePage">UTF8</a> or 54936. It cannot be used with other code page values.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WideCharConversionType.NoBestFitChars">**NoBestFitChars**</td><td>1024</td><td>Translate any Unicode characters that do not translate directly to multibyte equivalents to the default character specified by `defaultChar` parameter. 

 In other words, if translating from Unicode to multibyte and back to Unicode again does not yield the same Unicode character, the function uses the default character. 

 This flag can be used by itself or in combination with the other defined flags. 

 For strings that require validation, such as file, resource, and user names, the application should always use the NoBestFitChars flag. 

 This flag prevents the function from mapping characters to characters that appear similar but have very different semantics. 

 In some cases, the semantic change can be extreme. For example, the symbol for &quot;∞&quot; (infinity) maps to 8 (eight) in some code pages.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/stringapiset/nf-stringapiset-multibytetowidechar" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/stringapiset/nf-stringapiset-multibytetowidechar</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />