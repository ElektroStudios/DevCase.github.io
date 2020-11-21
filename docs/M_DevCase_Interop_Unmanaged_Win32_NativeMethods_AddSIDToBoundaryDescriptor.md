# NativeMethods.AddSIDToBoundaryDescriptor Method 
 

Adds a security identifier (SID) to the specified boundary descriptor.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool AddSIDToBoundaryDescriptor(
	ref IntPtr refBoundaryDescriptor,
	IntPtr requiredSid
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function AddSIDToBoundaryDescriptor ( 
	ByRef refBoundaryDescriptor As IntPtr,
	requiredSid As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refBoundaryDescriptor As IntPtr
Dim requiredSid As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.AddSIDToBoundaryDescriptor(refBoundaryDescriptor, 
	requiredSid)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool AddSIDToBoundaryDescriptor(
	IntPtr% refBoundaryDescriptor, 
	[InAttribute] IntPtr requiredSid
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member AddSIDToBoundaryDescriptor : 
        refBoundaryDescriptor : IntPtr byref * 
        requiredSid : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>refBoundaryDescriptor</dt><dd>Type: System.IntPtr<br />A handle to the boundary descriptor. The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateBoundaryDescriptor">CreateBoundaryDescriptor(String, UInt32)</a> function returns this handle.</dd><dt>requiredSid</dt><dd>Type: System.IntPtr<br />A pointer to a SID structure.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms681937(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms681937(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />