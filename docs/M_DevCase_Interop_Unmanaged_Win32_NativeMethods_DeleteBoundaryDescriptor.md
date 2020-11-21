# NativeMethods.DeleteBoundaryDescriptor Method 
 

Deletes the specified boundary descriptor.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static void DeleteBoundaryDescriptor(
	IntPtr boundaryDescriptor
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Sub DeleteBoundaryDescriptor ( 
	boundaryDescriptor As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim boundaryDescriptor As IntPtrNativeMethods.DeleteBoundaryDescriptor(boundaryDescriptor)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, SetLastError = true)]
static void DeleteBoundaryDescriptor(
	[InAttribute] IntPtr boundaryDescriptor
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member DeleteBoundaryDescriptor : 
        boundaryDescriptor : IntPtr -> unit 

```


#### Parameters
&nbsp;<dl><dt>boundaryDescriptor</dt><dd>Type: System.IntPtr<br />A handle to the boundary descriptor. The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateBoundaryDescriptor">CreateBoundaryDescriptor(String, UInt32)</a> function returns this handle.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-createboundarydescriptora" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-createboundarydescriptora</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />