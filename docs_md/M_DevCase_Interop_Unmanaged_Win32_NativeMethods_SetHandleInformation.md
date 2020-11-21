# NativeMethods.SetHandleInformation Method 
 

Sets certain properties of an object handle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool SetHandleInformation(
	IntPtr hObject,
	HandleFlags mask,
	HandleFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function SetHandleInformation ( 
	hObject As IntPtr,
	mask As HandleFlags,
	flags As HandleFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hObject As IntPtr
Dim mask As HandleFlags
Dim flags As HandleFlags
Dim returnValue As Boolean

returnValue = NativeMethods.SetHandleInformation(hObject, 
	mask, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool SetHandleInformation(
	[InAttribute] IntPtr hObject, 
	HandleFlags mask, 
	HandleFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member SetHandleInformation : 
        hObject : IntPtr * 
        mask : HandleFlags * 
        flags : HandleFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>hObject</dt><dd>Type: System.IntPtr<br />A handle to an object whose information is to be set. 

 You can specify a handle to one of the following types of objects: access token, console input buffer, console screen buffer, event, file, file mapping, job, mailslot, mutex, pipe, printer, process, registry key, semaphore, serial communication device, socket, thread, or waitable timer.</dd><dt>mask</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HandleFlags">DevCase.Interop.Unmanaged.Win32.Enums.HandleFlags</a><br />A mask that specifies the flags to be changed.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HandleFlags">DevCase.Interop.Unmanaged.Win32.Enums.HandleFlags</a><br />Flags that specifies properties of the object handle.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/handleapi/nf-handleapi-sethandleinformation" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/handleapi/nf-handleapi-sethandleinformation</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />