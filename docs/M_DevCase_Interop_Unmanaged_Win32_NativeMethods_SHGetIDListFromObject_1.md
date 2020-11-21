# NativeMethods.SHGetIDListFromObject Method (Object, IntPtr)
 

Retrieves the pointer to an item identifier list (PIDL) of an object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)]
public static HResult SHGetIDListFromObject(
	Object iUnknown,
	out IntPtr refPidl
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SHGetIDListFromObject ( 
	iUnknown As Object,
	<OutAttribute> ByRef refPidl As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim iUnknown As Object
Dim refPidl As IntPtr
Dim returnValue As HResult

returnValue = NativeMethods.SHGetIDListFromObject(iUnknown, 
	refPidl)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", ExactSpelling = true, SetLastError = true)]
static HResult SHGetIDListFromObject(
	Object^ iUnknown, 
	[OutAttribute] IntPtr% refPidl
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)>]
static member SHGetIDListFromObject : 
        iUnknown : Object * 
        refPidl : IntPtr byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>iUnknown</dt><dd>Type: System.Object<br />A pointer to the IUnknown of the object from which to get the PIDL.</dd><dt>refPidl</dt><dd>Type: System.IntPtr<br />When this function returns, contains a pointer to the PIDL of the given object.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shgetidlistfromobject" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shgetidlistfromobject</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHGetIDListFromObject">SHGetIDListFromObject Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />