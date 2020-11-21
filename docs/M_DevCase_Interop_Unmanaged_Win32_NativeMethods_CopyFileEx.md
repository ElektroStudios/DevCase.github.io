# NativeMethods.CopyFileEx Method 
 

Copies an existing file to a new file, notifying the application of its progress through a callback function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static bool CopyFileEx(
	string existingFileName,
	string newFileName,
	Delegates.CopyProgressRoutine progressRoutine,
	IntPtr data,
	ref bool refCancel,
	CopyFileFlags copyFlags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Unicode, SetLastError := true>]
Public Shared Function CopyFileEx ( 
	existingFileName As String,
	newFileName As String,
	progressRoutine As Delegates.CopyProgressRoutine,
	data As IntPtr,
	ByRef refCancel As Boolean,
	copyFlags As CopyFileFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim existingFileName As String
Dim newFileName As String
Dim progressRoutine As Delegates.CopyProgressRoutine
Dim data As IntPtr
Dim refCancel As Boolean
Dim copyFlags As CopyFileFlags
Dim returnValue As Boolean

returnValue = NativeMethods.CopyFileEx(existingFileName, 
	newFileName, progressRoutine, data, 
	refCancel, copyFlags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Unicode, SetLastError = true)]
static bool CopyFileEx(
	String^ existingFileName, 
	String^ newFileName, 
	Delegates.CopyProgressRoutine^ progressRoutine, 
	IntPtr data, 
	bool% refCancel, 
	CopyFileFlags copyFlags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)>]
static member CopyFileEx : 
        existingFileName : string * 
        newFileName : string * 
        progressRoutine : Delegates.CopyProgressRoutine * 
        data : IntPtr * 
        refCancel : bool byref * 
        copyFlags : CopyFileFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>existingFileName</dt><dd>Type: System.String<br />The name of an existing file.</dd><dt>newFileName</dt><dd>Type: System.String<br />The name of the new file.</dd><dt>progressRoutine</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_CopyProgressRoutine">DevCase.Interop.Unmanaged.Win32.Delegates.CopyProgressRoutine</a><br />The address of a callback function of type `LPPROGRESS_ROUTINE` that is called each time another portion of the file has been copied. 

 This parameter can be NULL.</dd><dt>data</dt><dd>Type: System.IntPtr<br />The argument to be passed to the callback function.</dd><dt>refCancel</dt><dd>Type: System.Boolean<br />If this flag is set to TRUE during the copy operation, the operation is canceled. 

 Otherwise, the copy operation will continue to completion.</dd><dt>copyFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CopyFileFlags">DevCase.Interop.Unmanaged.Win32.Enums.CopyFileFlags</a><br />Flags that specify how the file is to be copied.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is nonzero. 

 If the function fails, the return value is zero. 

 To get extended error information call GetLastWin32Error(). 

 If *progressRoutine* returns PROGRESS_CANCEL due to the user canceling the operation, CopyFileEx(String, String, Delegates.CopyProgressRoutine, IntPtr, Boolean, CopyFileFlags) will return zero and GetLastWin32Error() will return <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_REQUEST_ABORTED</a>. In this case, the partially copied destination file is deleted. 

 If *progressRoutine* returns PROGRESS_STOP due to the user stopping the operation, CopyFileEx(String, String, Delegates.CopyProgressRoutine, IntPtr, Boolean, CopyFileFlags) will return zero and GetLastWin32Error() will return <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_REQUEST_ABORTED</a>. In this case, the partially copied destination file is left intact.

## Remarks
<a href="https://msdn.microsoft.com/da-dk/library/windows/desktop/aa363852(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/da-dk/library/windows/desktop/aa363852(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />