# NativeMethods.OpenMutex Method 
 

Opens an existing named mutex object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr OpenMutex(
	uint desiredAccess,
	bool inheritHandle,
	string name
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function OpenMutex ( 
	desiredAccess As UInteger,
	inheritHandle As Boolean,
	name As String
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim desiredAccess As UInteger
Dim inheritHandle As Boolean
Dim name As String
Dim returnValue As IntPtr

returnValue = NativeMethods.OpenMutex(desiredAccess, 
	inheritHandle, name)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr OpenMutex(
	unsigned int desiredAccess, 
	bool inheritHandle, 
	String^ name
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member OpenMutex : 
        desiredAccess : uint32 * 
        inheritHandle : bool * 
        name : string -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>desiredAccess</dt><dd>Type: System.UInt32<br />The access To the mutex Object. 

 Only the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">Synchronize</a> access right Is required To use a mutex; To change the mutex's security, specify MUTEX_ALL_ACCESS. 

 The function fails if the security descriptor of the specified object does not permit the requested access for the calling process.</dd><dt>inheritHandle</dt><dd>Type: System.Boolean<br />If this value Is `true` (`True` in Visual Basic), processes created by this process will inherit the handle. Otherwise, the processes Do Not inherit this handle.</dd><dt>name</dt><dd>Type: System.String<br />The name of the mutex to be opened. Name comparisons are case sensitive. 

 This function can open objects in a private namespace.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the mutex object. 

 If the function fails, the return value is Zero. 



## Remarks
<a href="https://msdn.microsoft.com/en-us/windows/desktop/ms684315" target="_blank">https://msdn.microsoft.com/en-us/windows/desktop/ms684315</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />