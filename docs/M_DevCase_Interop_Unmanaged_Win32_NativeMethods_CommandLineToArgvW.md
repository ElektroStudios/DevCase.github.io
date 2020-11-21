# NativeMethods.CommandLineToArgvW Method 
 

Parses a Unicode command line string and returns an array of pointers to the command line arguments, along with a count of such arguments, in a way that is similar to the standard C run-time argv and argc values.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Unicode, ExactSpelling = true, 
	SetLastError = true)]
public static string[] CommandLineToArgvW(
	string cmdLine,
	out int refNumArgs
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Unicode, ExactSpelling := true, 
	SetLastError := true>]
Public Shared Function CommandLineToArgvW ( 
	cmdLine As String,
	<OutAttribute> ByRef refNumArgs As Integer
) As String()
```

**VB Usage**<br />
``` VB Usage
Dim cmdLine As String
Dim refNumArgs As Integer
Dim returnValue As String()

returnValue = NativeMethods.CommandLineToArgvW(cmdLine, 
	refNumArgs)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Unicode, ExactSpelling = true, 
	SetLastError = true)]
static array<String^>^ CommandLineToArgvW(
	String^ cmdLine, 
	[OutAttribute] int% refNumArgs
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Unicode, ExactSpelling = true, 
	SetLastError = true)>]
static member CommandLineToArgvW : 
        cmdLine : string * 
        refNumArgs : int byref -> string[] 

```


#### Parameters
&nbsp;<dl><dt>cmdLine</dt><dd>Type: System.String<br />Pointer to a null-terminated Unicode string that contains the full command line. 

 If this parameter is an empty string the function returns the path to the current executable file</dd><dt>refNumArgs</dt><dd>Type: System.Int32<br />Pointer to an integer that receives the number of array elements returned, similar to argc.</dd></dl>

#### Return Value
Type: String[]<br />A pointer to an array of LPWSTR values, similar to argv. 

 If the function fails, the return value is a null reference (`Nothing` in Visual Basic). 

 To get extended error information, call GetLastWin32Error()) function.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shellapi/nf-shellapi-commandlinetoargvw" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shellapi/nf-shellapi-commandlinetoargvw</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />