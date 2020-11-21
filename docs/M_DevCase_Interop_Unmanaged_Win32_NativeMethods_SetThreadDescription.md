# NativeMethods.SetThreadDescription Method 
 

Assigns a description to a thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true)]
public static HResult SetThreadDescription(
	IntPtr hThread,
	string threadDescription
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Unicode, ExactSpelling := true>]
Public Shared Function SetThreadDescription ( 
	hThread As IntPtr,
	threadDescription As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim hThread As IntPtr
Dim threadDescription As String
Dim returnValue As HResult

returnValue = NativeMethods.SetThreadDescription(hThread, 
	threadDescription)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Unicode, ExactSpelling = true)]
static HResult SetThreadDescription(
	IntPtr hThread, 
	String^ threadDescription
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true)>]
static member SetThreadDescription : 
        hThread : IntPtr * 
        threadDescription : string -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hThread</dt><dd>Type: System.IntPtr<br />A handle for the thread for which you want to set the description. The handle must have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadAccessRights">SetLimitedInformation</a> access.</dd><dt>threadDescription</dt><dd>Type: System.String<br />A Unicode string that specifies the description of the thread.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the function succeeds, the return value is the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> that denotes a successful operation. 

 If the function fails, the return value is an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> that denotes the error.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-setthreaddescription" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-setthreaddescription</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />