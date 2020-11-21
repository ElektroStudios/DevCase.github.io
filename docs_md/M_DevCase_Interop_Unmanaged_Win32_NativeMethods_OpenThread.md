# NativeMethods.OpenThread Method (GenericAccessRights, Boolean, UInt32)
 

Opens an existing thread object. 

 When done, don't forget to call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CloseHandle">CloseHandle(IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static SafeAccessTokenHandle OpenThread(
	GenericAccessRights desiredAccess,
	bool inheritHandle,
	uint threadId
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function OpenThread ( 
	desiredAccess As GenericAccessRights,
	inheritHandle As Boolean,
	threadId As UInteger
) As SafeAccessTokenHandle
```

**VB Usage**<br />
``` VB Usage
Dim desiredAccess As GenericAccessRights
Dim inheritHandle As Boolean
Dim threadId As UInteger
Dim returnValue As SafeAccessTokenHandle

returnValue = NativeMethods.OpenThread(desiredAccess, 
	inheritHandle, threadId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static SafeAccessTokenHandle^ OpenThread(
	GenericAccessRights desiredAccess, 
	bool inheritHandle, 
	unsigned int threadId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member OpenThread : 
        desiredAccess : GenericAccessRights * 
        inheritHandle : bool * 
        threadId : uint32 -> SafeAccessTokenHandle 

```


#### Parameters
&nbsp;<dl><dt>desiredAccess</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_GenericAccessRights">DevCase.Interop.Unmanaged.Win32.Enums.GenericAccessRights</a><br />The access to the thread object. 

 This access right is checked against the security descriptor for the thread.</dd><dt>inheritHandle</dt><dd>Type: System.Boolean<br />If this value is `true` (`True` in Visual Basic), processes created by this process will inherit the handle. 

 Otherwise, the processes do not inherit this handle.</dd><dt>threadId</dt><dd>Type: System.UInt32<br />The identifier of the thread to be opened.</dd></dl>

#### Return Value
Type: SafeAccessTokenHandle<br />If the function succeeds, the return value is an open handle to the specified thread. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms684335%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms684335%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenThread">OpenThread Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />