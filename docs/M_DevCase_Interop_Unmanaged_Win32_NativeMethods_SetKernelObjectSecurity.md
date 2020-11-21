# NativeMethods.SetKernelObjectSecurity Method 
 

Sets the security of a kernel object. For example, this can be a process, thread, or event.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", SetLastError = true)]
public static bool SetKernelObjectSecurity(
	IntPtr handle,
	SecurityInformation securityInformation,
	byte[] securityDescriptor
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", SetLastError := true>]
Public Shared Function SetKernelObjectSecurity ( 
	handle As IntPtr,
	securityInformation As SecurityInformation,
	securityDescriptor As Byte()
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim handle As IntPtr
Dim securityInformation As SecurityInformation
Dim securityDescriptor As Byte()
Dim returnValue As Boolean

returnValue = NativeMethods.SetKernelObjectSecurity(handle, 
	securityInformation, securityDescriptor)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", SetLastError = true)]
static bool SetKernelObjectSecurity(
	IntPtr handle, 
	SecurityInformation securityInformation, 
	[InAttribute] array<unsigned char>^ securityDescriptor
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", SetLastError = true)>]
static member SetKernelObjectSecurity : 
        handle : IntPtr * 
        securityInformation : SecurityInformation * 
        securityDescriptor : byte[] -> bool 

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: System.IntPtr<br />A handle to a kernel object for which security information is set.</dd><dt>securityInformation</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SecurityInformation">DevCase.Interop.Unmanaged.Win32.Enums.SecurityInformation</a><br />A set of flags that indicate the type of security information to set. 

 This parameter can be a combination of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SecurityInformation">SecurityInformation</a> flags.</dd><dt>securityDescriptor</dt><dd>Type: System.Byte[]<br />A pointer to a `SECURITY_DESCRIPTOR` structure that contains the new security information.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic)

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa379578%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa379578%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />