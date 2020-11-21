# NativeMethods.MultiByteToWideChar Method 
 


## Overload List
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MultiByteToWideChar_2">MultiByteToWideChar(UInt32, MultiByteCharConversionType, Byte[], Int32, Char[], Int32)</a></td><td>
Maps a character string to a UTF-16 (wide character) string. The character string is not necessarily from a multibyte character set. 

 Caution: Using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MultiByteToWideChar">MultiByteToWideChar(CodePage, MultiByteCharConversionType, Byte[], Int32, Char[], Int32)</a> function incorrectly can compromise the security of your application. 

 Calling this function can easily cause a buffer overrun because the size of the input buffer indicated by *multiByteStr* equals the number of bytes in the string, while the size of the output buffer indicated by *wideCharStr* equals the number of characters. 

 To avoid a buffer overrun, your application must specify a buffer size appropriate for the data type the buffer receives.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MultiByteToWideChar_3">MultiByteToWideChar(UInt32, MultiByteCharConversionType, String, Int32, StringBuilder, Int32)</a></td><td>
Maps a character string to a UTF-16 (wide character) string. The character string is not necessarily from a multibyte character set. 

 Caution: Using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MultiByteToWideChar">MultiByteToWideChar(CodePage, MultiByteCharConversionType, Byte[], Int32, Char[], Int32)</a> function incorrectly can compromise the security of your application. 

 Calling this function can easily cause a buffer overrun because the size of the input buffer indicated by *multiByteStr* equals the number of bytes in the string, while the size of the output buffer indicated by *wideCharStr* equals the number of characters. 

 To avoid a buffer overrun, your application must specify a buffer size appropriate for the data type the buffer receives.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MultiByteToWideChar">MultiByteToWideChar(CodePage, MultiByteCharConversionType, Byte[], Int32, Char[], Int32)</a></td><td>
Maps a character string to a UTF-16 (wide character) string. The character string is not necessarily from a multibyte character set. 

 Caution: Using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MultiByteToWideChar">MultiByteToWideChar(CodePage, MultiByteCharConversionType, Byte[], Int32, Char[], Int32)</a> function incorrectly can compromise the security of your application. 

 Calling this function can easily cause a buffer overrun because the size of the input buffer indicated by *multiByteStr* equals the number of bytes in the string, while the size of the output buffer indicated by *wideCharStr* equals the number of characters. 

 To avoid a buffer overrun, your application must specify a buffer size appropriate for the data type the buffer receives.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MultiByteToWideChar_1">MultiByteToWideChar(CodePage, MultiByteCharConversionType, String, Int32, StringBuilder, Int32)</a></td><td>
Maps a character string to a UTF-16 (wide character) string. The character string is not necessarily from a multibyte character set. 

 Caution: Using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MultiByteToWideChar">MultiByteToWideChar(CodePage, MultiByteCharConversionType, Byte[], Int32, Char[], Int32)</a> function incorrectly can compromise the security of your application. 

 Calling this function can easily cause a buffer overrun because the size of the input buffer indicated by *multiByteStr* equals the number of bytes in the string, while the size of the output buffer indicated by *wideCharStr* equals the number of characters. 

 To avoid a buffer overrun, your application must specify a buffer size appropriate for the data type the buffer receives.</td></tr></table>&nbsp;
<a href="#nativemethods.multibytetowidechar-method">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />