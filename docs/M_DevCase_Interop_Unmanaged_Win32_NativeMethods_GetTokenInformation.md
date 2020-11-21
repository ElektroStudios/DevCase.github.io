# NativeMethods.GetTokenInformation Method 
 

Retrieves a specified type of information about an access token. 

 The calling process must have appropriate access rights to obtain the information.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", SetLastError = true)]
public static bool GetTokenInformation(
	IntPtr tokenHandle,
	TokenInformationClass tokenInformationClass,
	IntPtr tokenInformation,
	int tokenInformationLength,
	ref int refReturnLength
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", SetLastError := true>]
Public Shared Function GetTokenInformation ( 
	tokenHandle As IntPtr,
	tokenInformationClass As TokenInformationClass,
	tokenInformation As IntPtr,
	tokenInformationLength As Integer,
	ByRef refReturnLength As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim tokenHandle As IntPtr
Dim tokenInformationClass As TokenInformationClass
Dim tokenInformation As IntPtr
Dim tokenInformationLength As Integer
Dim refReturnLength As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.GetTokenInformation(tokenHandle, 
	tokenInformationClass, tokenInformation, 
	tokenInformationLength, refReturnLength)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", SetLastError = true)]
static bool GetTokenInformation(
	IntPtr tokenHandle, 
	TokenInformationClass tokenInformationClass, 
	IntPtr tokenInformation, 
	int tokenInformationLength, 
	int% refReturnLength
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", SetLastError = true)>]
static member GetTokenInformation : 
        tokenHandle : IntPtr * 
        tokenInformationClass : TokenInformationClass * 
        tokenInformation : IntPtr * 
        tokenInformationLength : int * 
        refReturnLength : int byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>tokenHandle</dt><dd>Type: System.IntPtr<br />A handle to an access token from which information is retrieved. 

 If *tokenInformationClass* specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenInformationClass">TokenSource</a>, the handle must have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">QuerySource</a> access. 

 For all other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenInformationClass">TokenInformationClass</a> values, the handle must have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Query</a> access.</dd><dt>tokenInformationClass</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenInformationClass">DevCase.Interop.Unmanaged.Win32.Enums.TokenInformationClass</a><br />Specifies a value from the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenInformationClass">TokenInformationClass</a> enumeration to identify the type of information the function retrieves. 

 Any callers who check the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenInformationClass">TokenIsAppContainer</a>`TokenIsAppContainer` and have it return `0` should also verify that the caller token is not an identify level impersonation token. 

 If the current token is not an app container but is an identity level token, you should return `AccessDenied`.</dd><dt>tokenInformation</dt><dd>Type: System.IntPtr<br />A pointer to a buffer the function fills with the requested information. 

 The structure put into this buffer depends upon the type of information specified by the *tokenInformationClass* parameter.</dd><dt>tokenInformationLength</dt><dd>Type: System.Int32<br />Specifies the size, in bytes, of the buffer pointed to by the TokenInformation parameter. 

 If *tokenInformation* is `IntPtr.Zero`, this parameter must be `0`.</dd><dt>refReturnLength</dt><dd>Type: System.Int32<br />A pointer to a variable that receives the number of bytes needed for the buffer pointed to by the *tokenInformation* parameter. 

 If this value is larger than the value specified in the *tokenInformationLength* parameter, the function fails and stores no data in the buffer.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error(). 



## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa446671%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa446671%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />