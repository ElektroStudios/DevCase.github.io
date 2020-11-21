# NativeMethods.SetWindowsHookEx Method 
 

Installs an application-defined hook procedure into a hook chain. 

 You would install a hook procedure to monitor the system for certain types of events. 

 These events are associated either with a specific thread or with all threads in the same desktop as the calling thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr SetWindowsHookEx(
	HookType hookType,
	Delegates.HookProc hookProc,
	IntPtr hInstance,
	uint threadId
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SetWindowsHookEx ( 
	hookType As HookType,
	hookProc As Delegates.HookProc,
	hInstance As IntPtr,
	threadId As UInteger
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hookType As HookType
Dim hookProc As Delegates.HookProc
Dim hInstance As IntPtr
Dim threadId As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.SetWindowsHookEx(hookType, 
	hookProc, hInstance, threadId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr SetWindowsHookEx(
	HookType hookType, 
	Delegates.HookProc^ hookProc, 
	IntPtr hInstance, 
	unsigned int threadId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SetWindowsHookEx : 
        hookType : HookType * 
        hookProc : Delegates.HookProc * 
        hInstance : IntPtr * 
        threadId : uint32 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hookType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HookType">DevCase.Interop.Unmanaged.Win32.Enums.HookType</a><br />The type of hook procedure to be installed.</dd><dt>hookProc</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_HookProc">DevCase.Interop.Unmanaged.Win32.Delegates.HookProc</a><br />A pointer to the hook procedure. 

 If the *threadId* parameter is zero or specifies the identifier of a thread created by a different process, the *HookProc* parameter must point to a hook procedure in a DLL. Otherwise, *HookProc* can point to a hook procedure in the code associated with the current process.</dd><dt>hInstance</dt><dd>Type: System.IntPtr<br />A handle to the DLL containing the hook procedure pointed to by the lpfn parameter. 

 The *hInstance* parameter must be set to Zero if the *threadId* parameter specifies a thread created by the current process and if the hook procedure is within the code associated with the current process.</dd><dt>threadId</dt><dd>Type: System.UInt32<br />The identifier of the thread with which the hook procedure is to be associated. 

 For desktop apps, if this parameter is zero, the hook procedure is associated with all existing threads running in the same desktop as the calling thread.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the handle to the hook procedure. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644990%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644990%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />