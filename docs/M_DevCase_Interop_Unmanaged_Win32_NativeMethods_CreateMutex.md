# NativeMethods.CreateMutex Method 
 

Creates or opens a named or unnamed mutex object. 

 To specify an access mask for the object, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateMutexEx">CreateMutexEx(SecurityAttributes, String, CreateMutexFlags, StandardAccessRights)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr CreateMutex(
	[OptionalAttribute] SecurityAttributes mutexAttributes,
	bool initialOwner,
	[OptionalAttribute] string name
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function CreateMutex ( 
	<OptionalAttribute> mutexAttributes As SecurityAttributes,
	initialOwner As Boolean,
	<OptionalAttribute> name As String
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim mutexAttributes As SecurityAttributes
Dim initialOwner As Boolean
Dim name As String
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateMutex(mutexAttributes, 
	initialOwner, name)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr CreateMutex(
	[OptionalAttribute] [InAttribute] SecurityAttributes mutexAttributes, 
	bool initialOwner, 
	[OptionalAttribute] [InAttribute] String^ name
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member CreateMutex : 
        [<OptionalAttribute>] mutexAttributes : SecurityAttributes * 
        initialOwner : bool * 
        [<OptionalAttribute>] name : string -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>mutexAttributes (Optional)</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">DevCase.Interop.Unmanaged.Win32.Structures.SecurityAttributes</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">SecurityAttributes</a> structure. 

 If this parameter is NULL, the mutex handle cannot be inherited by child processes. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes_SecurityDescriptor">SecurityDescriptor</a> member specifies a security descriptor for the new mutex. 

 If *mutexAttributes* is NULL, the mutex gets a default security descriptor. 

 The ACLs in the default security descriptor for a mutex come from the primary or impersonation token of the creator.</dd><dt>initialOwner</dt><dd>Type: System.Boolean<br />If this value is `true` (`True` in Visual Basic) and the caller created the mutex, the calling thread obtains initial ownership of the mutex object. Otherwise, the calling thread does not obtain ownership of the mutex. 

 To determine if the caller created the mutex, see the return value section.</dd><dt>name (Optional)</dt><dd>Type: System.String<br />The name of the mutex object. The name is limited to MAX_PATH characters. Name comparison is case sensitive. 

 If *name* is NULL, the mutex object is created without a name. 

 If *name* matches the name of an existing event, semaphore, waitable timer, job, or file-mapping object, the function fails and the GetLastError function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_INVALID_HANDLE</a>. This occurs because these objects share the same namespace. 

 The name can have a "Global" or "Local" prefix to explicitly create the object in the global or session namespace. The remainder of the name can contain any character except the backslash character ().</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the newly created mutex object. 

 If the function fails, the return value is Zero. 

 If the mutex is a named mutex and the object existed before this function call, the return value is a handle to the existing object, GetLastError returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_ALREADY_EXISTS</a>., *initialOwner* is ignored, and the calling thread is not granted ownership. 

 However, if the caller has limited access rights, the function will fail with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_ACCESS_DENIED</a> and the caller should use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenMutex">OpenMutex(UInt32, Boolean, String)</a> function.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/synchapi/nf-synchapi-createmutexexa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/synchapi/nf-synchapi-createmutexexa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />