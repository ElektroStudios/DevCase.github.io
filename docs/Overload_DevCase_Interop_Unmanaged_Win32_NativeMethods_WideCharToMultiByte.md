# NativeMethods.WideCharToMultiByte Method 
 


## Overload List
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WideCharToMultiByte_1">WideCharToMultiByte(UInt32, WideCharConversionType, String, Int32, StringBuilder, Int32, String, Boolean)</a></td><td>
Maps a UTF-16 (wide character) string to a new character string. The new character string is not necessarily from a multibyte character set. 

 Caution: Using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WideCharToMultiByte">WideCharToMultiByte(CodePage, WideCharConversionType, String, Int32, StringBuilder, Int32, String, Boolean)</a> function incorrectly can compromise the security of your application. Calling this function can easily cause a buffer overrun because the size of the input buffer indicated by *wideCharStr* equals the number of characters in the Unicode string, while the size of the output buffer indicated by *multiByteStr* equals the number of bytes. 

 To avoid a buffer overrun, your application must specify a buffer size appropriate for the data type the buffer receives. 

 Data converted from UTF-16 to non-Unicode encodings is subject to data loss, because a code page might not be able to represent every character used in the specific Unicode data.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WideCharToMultiByte">WideCharToMultiByte(CodePage, WideCharConversionType, String, Int32, StringBuilder, Int32, String, Boolean)</a></td><td>
Maps a UTF-16 (wide character) string to a new character string. The new character string is not necessarily from a multibyte character set. 

 Caution: Using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WideCharToMultiByte">WideCharToMultiByte(CodePage, WideCharConversionType, String, Int32, StringBuilder, Int32, String, Boolean)</a> function incorrectly can compromise the security of your application. Calling this function can easily cause a buffer overrun because the size of the input buffer indicated by *wideCharStr* equals the number of characters in the Unicode string, while the size of the output buffer indicated by *multiByteStr* equals the number of bytes. 

 To avoid a buffer overrun, your application must specify a buffer size appropriate for the data type the buffer receives. 

 Data converted from UTF-16 to non-Unicode encodings is subject to data loss, because a code page might not be able to represent every character used in the specific Unicode data.</td></tr></table>&nbsp;
<a href="#nativemethods.widechartomultibyte-method">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />