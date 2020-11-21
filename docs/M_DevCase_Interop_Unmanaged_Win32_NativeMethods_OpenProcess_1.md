# NativeMethods.OpenProcess Method (ProcessAccessRights, Boolean, Int32)
 

Opens an existing local process object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static SafeProcessHandle OpenProcess(
	ProcessAccessRights desiredAccess,
	bool inheritHandle,
	int pid
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Unicode, SetLastError := true>]
Public Shared Function OpenProcess ( 
	desiredAccess As ProcessAccessRights,
	inheritHandle As Boolean,
	pid As Integer
) As SafeProcessHandle
```

**VB Usage**<br />
``` VB Usage
Dim desiredAccess As ProcessAccessRights
Dim inheritHandle As Boolean
Dim pid As Integer
Dim returnValue As SafeProcessHandle

returnValue = NativeMethods.OpenProcess(desiredAccess, 
	inheritHandle, pid)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Unicode, SetLastError = true)]
static SafeProcessHandle^ OpenProcess(
	ProcessAccessRights desiredAccess, 
	bool inheritHandle, 
	int pid
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)>]
static member OpenProcess : 
        desiredAccess : ProcessAccessRights * 
        inheritHandle : bool * 
        pid : int -> SafeProcessHandle 

```


#### Parameters
&nbsp;<dl><dt>desiredAccess</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">DevCase.Interop.Unmanaged.Win32.Enums.ProcessAccessRights</a><br />The access to the process object. 

 This access right is checked against the security descriptor for the process.</dd><dt>inheritHandle</dt><dd>Type: System.Boolean<br />If this value is `true` (`True` in Visual Basic), processes created by this process will inherit the handle. Otherwise, the processes do not inherit this handle.</dd><dt>pid</dt><dd>Type: System.Int32<br />The identifier of the local process to be opened</dd></dl>

#### Return Value
Type: SafeProcessHandle<br />If the function succeeds, the return value is an open handle to the specified process. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms684320(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms684320(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenProcess">OpenProcess Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />