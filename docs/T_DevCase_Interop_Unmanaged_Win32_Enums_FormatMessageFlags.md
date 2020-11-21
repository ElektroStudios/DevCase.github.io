# FormatMessageFlags Enumeration
 

Specifies the formatting options for a message. 

 For <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FormatMessage">FormatMessage(FormatMessageFlags, IntPtr, UInt32, UInt32, IntPtr, UInt32, String[])</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum FormatMessageFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration FormatMessageFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As FormatMessageFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class FormatMessageFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type FormatMessageFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FormatMessageFlags.AllocateBuffer">**AllocateBuffer**</td><td>256</td><td>The function allocates a buffer large enough to hold the formatted message, and places a pointer to the allocated buffer at the address specified by buffer parameter. 

 The size parameter specifies the minimum number of characters to allocate for an output message buffer. 

 The caller should use the LocalFree function to free the buffer when it is no longer needed. 

 If the length of the formatted message exceeds 128K bytes, then <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FormatMessage">FormatMessage(FormatMessageFlags, IntPtr, UInt32, UInt32, IntPtr, UInt32, String[])</a> will fail and a subsequent call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetLastError">GetLastError()</a> will return <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_MORE_DATA</a>. 

 In previous versions of Windows, this value was not available for use when compiling Windows Store apps. As of Windows 10 this value can be used. 

 Windows 10: LocalFree is not in the modern SDK, so it cannot be used to free the result buffer. Instead, use HeapFree (GetProcessHeap(), allocatedMessage). In this case, this is the same as calling LocalFree on memory. 

 Important: LocalAlloc() has different options: LMEM_FIXED, and LMEM_MOVABLE. <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FormatMessage">FormatMessage(FormatMessageFlags, IntPtr, UInt32, UInt32, IntPtr, UInt32, String[])</a> uses LMEM_FIXED, so HeapFree can be used. If LMEM_MOVABLE is used, HeapFree cannot be used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FormatMessageFlags.ArgumentArray">**ArgumentArray**</td><td>8192</td><td>The Arguments parameter is not a va_list structure, but is a pointer to an array of values that represent the arguments. 

 This flag cannot be used with 64-bit integer values. If you are using a 64-bit integer, you must use the va_list structure.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FormatMessageFlags.FromHModule">**FromHModule**</td><td>2048</td><td>The source parameter is a module handle containing the message-table resource(s) to search. 

 If this source handle is NULL, the current process's application image file will be searched. 

 This flag cannot be used with FromString. 

 If the module has no message table resource, the function fails with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_RESOURCE_TYPE_NOT_FOUND</a>.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FormatMessageFlags.FromString">**FromString**</td><td>1024</td><td>The source parameter is a pointer to a null-terminated string that contains a message definition. 

 The message definition may contain insert sequences, just as the message text in a message table resource may. 

This flag cannot be used with FromHModule or FromSystem.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FormatMessageFlags.FromSystem">**FromSystem**</td><td>4096</td><td>The function should search the system message-table resource(s) for the requested message. 

 If this flag is specified with FromHModule, the function searches the system message table if the message is not found in the module specified by source parameter. 

 This flag cannot be used with FromString. 
If this flag is specified, an application can pass the result of the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetLastError">GetLastError()</a> function to retrieve the message text for a system-defined error.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FormatMessageFlags.IgnoreInserts">**IgnoreInserts**</td><td>512</td><td>Insert sequences in the message definition are to be ignored and passed through to the output buffer unchanged. 

 This flag is useful for fetching a message for later formatting. 

 If this flag is set, the arguments parameter is ignored.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FormatMessageFlags.MaxWidthMask">**MaxWidthMask**</td><td>255</td><td>With this flag set: 

 The function ignores regular line breaks in the message definition text. The function stores hard-coded line breaks in the message definition text into the output buffer. The function generates no new line breaks. 

 Without this flag set: 

 There are no output line width restrictions. The function stores line breaks that are in the message definition text into the output buffer. It specifies the maximum number of characters in an output line. The function ignores regular line breaks in the message definition text. The function never splits a string delimited by white space across a line break. The function stores hard-coded line breaks in the message definition text into the output buffer. Hard-coded line breaks are coded with the %n escape sequence.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-formatmessage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-formatmessage</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />