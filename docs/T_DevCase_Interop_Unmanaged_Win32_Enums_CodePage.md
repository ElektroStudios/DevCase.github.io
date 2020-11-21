# CodePage Enumeration
 

Indicate the code page to use in performing a character conversion when calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MultiByteToWideChar">MultiByteToWideChar(CodePage, MultiByteCharConversionType, Byte[], Int32, Char[], Int32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WideCharToMultiByte">WideCharToMultiByte(CodePage, WideCharConversionType, String, Int32, StringBuilder, Int32, String, Boolean)</a> functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum CodePage
```

**VB**<br />
``` VB
Public Enumeration CodePage
```

**VB Usage**<br />
``` VB Usage
Dim instance As CodePage
```

**C++**<br />
``` C++
public enum class CodePage
```

**F#**<br />
``` F#
type CodePage
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CodePage.Ansi">**Ansi**</td><td>0</td><td>The system default Windows ANSI code page.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CodePage.OEM">**OEM**</td><td>1</td><td>The current system OEM code page.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CodePage.Macintosh">**Macintosh**</td><td>2</td><td>The current system Macintosh code page.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CodePage.ThreadANSI">**ThreadANSI**</td><td>3</td><td>The Windows ANSI code page for the current thread.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CodePage.Symbol">**Symbol**</td><td>42</td><td>Symbol code page (42).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CodePage.UTF7">**UTF7**</td><td>65000</td><td>UTF-7. 

 Use this value only when forced by a 7-bit transport mechanism. Use of UTF-8 is preferred.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CodePage.UTF8">**UTF8**</td><td>65001</td><td>UTF-8.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/stringapiset/nf-stringapiset-multibytetowidechar" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/stringapiset/nf-stringapiset-multibytetowidechar</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />