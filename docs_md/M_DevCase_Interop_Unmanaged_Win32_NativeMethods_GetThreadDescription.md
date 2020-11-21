# NativeMethods.GetThreadDescription Method 
 

Retrieves the description that was assigned to a thread by calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetThreadDescription">SetThreadDescription(IntPtr, String)</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true)]
public static HResult GetThreadDescription(
	IntPtr hThread,
	out string refThreadDescription
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Unicode, ExactSpelling := true>]
Public Shared Function GetThreadDescription ( 
	hThread As IntPtr,
	<OutAttribute> ByRef refThreadDescription As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim hThread As IntPtr
Dim refThreadDescription As String
Dim returnValue As HResult

returnValue = NativeMethods.GetThreadDescription(hThread, 
	refThreadDescription)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Unicode, ExactSpelling = true)]
static HResult GetThreadDescription(
	IntPtr hThread, 
	[OutAttribute] String^% refThreadDescription
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true)>]
static member GetThreadDescription : 
        hThread : IntPtr * 
        refThreadDescription : string byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hThread</dt><dd>Type: System.IntPtr<br />A handle to the thread for which to retrieve the description. The handle must have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadAccessRights">QueryLimitedInformation</a> access.</dd><dt>refThreadDescription</dt><dd>Type: System.String<br />A Unicode string that contains the description of the thread.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the function succeeds, the return value is the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> that denotes a successful operation. 

 If the function fails, the return value is an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> that denotes the error.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getthreaddescription" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getthreaddescription</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />