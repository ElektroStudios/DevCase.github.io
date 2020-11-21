# NativeMethods.GetThreadIOPendingFlag Method 
 

Determines whether a specified thread has any I/O requests pending.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool GetThreadIOPendingFlag(
	IntPtr hThread,
	out bool refIoIsPending
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetThreadIOPendingFlag ( 
	hThread As IntPtr,
	<OutAttribute> ByRef refIoIsPending As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hThread As IntPtr
Dim refIoIsPending As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.GetThreadIOPendingFlag(hThread, 
	refIoIsPending)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool GetThreadIOPendingFlag(
	[InAttribute] IntPtr hThread, 
	[OutAttribute] bool% refIoIsPending
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetThreadIOPendingFlag : 
        hThread : IntPtr * 
        refIoIsPending : bool byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hThread</dt><dd>Type: System.IntPtr<br />A handle to the thread in question. 

 This handle must have been created with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadAccessRights">QueryInformation</a> access right.</dd><dt>refIoIsPending</dt><dd>Type: System.Boolean<br />A pointer to a variable which the function sets to `true` (`True` in Visual Basic) if the specified thread has one or more I/O requests pending, or to `false` (`False` in Visual Basic) otherwise.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getthreadiopendingflag" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getthreadiopendingflag</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />