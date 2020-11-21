# NativeMethods.DuplicateHandle Method (IntPtr, IntPtr, IntPtr, IntPtr, ThreadAccessRights, Boolean, DuplicateHandleOptions)
 

Duplicates an object handle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool DuplicateHandle(
	IntPtr srcProcHandle,
	IntPtr srcHandle,
	IntPtr dstProcHandle,
	ref IntPtr refDstHandle,
	ThreadAccessRights desiredAccess,
	bool inheritHandle,
	DuplicateHandleOptions options
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function DuplicateHandle ( 
	srcProcHandle As IntPtr,
	srcHandle As IntPtr,
	dstProcHandle As IntPtr,
	ByRef refDstHandle As IntPtr,
	desiredAccess As ThreadAccessRights,
	inheritHandle As Boolean,
	options As DuplicateHandleOptions
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim srcProcHandle As IntPtr
Dim srcHandle As IntPtr
Dim dstProcHandle As IntPtr
Dim refDstHandle As IntPtr
Dim desiredAccess As ThreadAccessRights
Dim inheritHandle As Boolean
Dim options As DuplicateHandleOptions
Dim returnValue As Boolean

returnValue = NativeMethods.DuplicateHandle(srcProcHandle, 
	srcHandle, dstProcHandle, refDstHandle, 
	desiredAccess, inheritHandle, options)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool DuplicateHandle(
	IntPtr srcProcHandle, 
	IntPtr srcHandle, 
	IntPtr dstProcHandle, 
	IntPtr% refDstHandle, 
	ThreadAccessRights desiredAccess, 
	bool inheritHandle, 
	DuplicateHandleOptions options
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member DuplicateHandle : 
        srcProcHandle : IntPtr * 
        srcHandle : IntPtr * 
        dstProcHandle : IntPtr * 
        refDstHandle : IntPtr byref * 
        desiredAccess : ThreadAccessRights * 
        inheritHandle : bool * 
        options : DuplicateHandleOptions -> bool 

```


#### Parameters
&nbsp;<dl><dt>srcProcHandle</dt><dd>Type: System.IntPtr<br />A handle to the process with the handle to be duplicated. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">DuplicateHandle</a> access right.</dd><dt>srcHandle</dt><dd>Type: System.IntPtr<br />The handle to be duplicated. 

 This is an open object handle that is valid in the context of the source process.</dd><dt>dstProcHandle</dt><dd>Type: System.IntPtr<br />A handle to the process that is to receive the duplicated handle. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">DuplicateHandle</a> access right.</dd><dt>refDstHandle</dt><dd>Type: System.IntPtr<br />A pointer to a variable that receives the duplicate handle. 

 This handle value is valid in the context of the target process. 

 If *srcHandle* is a pseudo handle returned by `GetCurrentProcess` or `GetCurrentThread`, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DuplicateHandle">DuplicateHandle(IntPtr, IntPtr, IntPtr, IntPtr, GenericAccessRights, Boolean, DuplicateHandleOptions)</a> converts it to a real handle to a process or thread, respectively. 

 If *refDstHandle* is Zero, the function duplicates the handle, but does not return the duplicate handle value to the caller. This behavior exists only for backward compatibility with previous versions of this function. You should not use this feature, as you will lose system resources until the target process terminates.</dd><dt>desiredAccess</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadAccessRights">DevCase.Interop.Unmanaged.Win32.Enums.ThreadAccessRights</a><br />The access requested for the new handle.</dd><dt>inheritHandle</dt><dd>Type: System.Boolean<br />A variable that indicates whether the handle is inheritable. 

 If `true` (`True` in Visual Basic), the duplicate handle can be inherited by new processes created by the target process. 

 If `false` (`False` in Visual Basic), the new handle cannot be inherited.</dd><dt>options</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DuplicateHandleOptions">DevCase.Interop.Unmanaged.Win32.Enums.DuplicateHandleOptions</a><br />Optional actions. This parameter can be zero.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/aa365461(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/aa365461(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_DuplicateHandle">DuplicateHandle Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />