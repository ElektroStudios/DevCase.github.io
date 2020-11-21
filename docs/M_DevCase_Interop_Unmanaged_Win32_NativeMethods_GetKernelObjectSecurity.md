# NativeMethods.GetKernelObjectSecurity Method 
 

Retrieves a copy of the security descriptor that protects a kernel object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", SetLastError = true)]
public static bool GetKernelObjectSecurity(
	IntPtr handle,
	SecurityInformation securityInformation,
	byte[] securityDescriptor,
	uint length,
	ref uint refLengthNeeded
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", SetLastError := true>]
Public Shared Function GetKernelObjectSecurity ( 
	handle As IntPtr,
	securityInformation As SecurityInformation,
	<OutAttribute> securityDescriptor As Byte(),
	length As UInteger,
	ByRef refLengthNeeded As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim handle As IntPtr
Dim securityInformation As SecurityInformation
Dim securityDescriptor As Byte()
Dim length As UInteger
Dim refLengthNeeded As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.GetKernelObjectSecurity(handle, 
	securityInformation, securityDescriptor, 
	length, refLengthNeeded)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", SetLastError = true)]
static bool GetKernelObjectSecurity(
	IntPtr handle, 
	SecurityInformation securityInformation, 
	[OutAttribute] array<unsigned char>^ securityDescriptor, 
	unsigned int length, 
	unsigned int% refLengthNeeded
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", SetLastError = true)>]
static member GetKernelObjectSecurity : 
        handle : IntPtr * 
        securityInformation : SecurityInformation * 
        securityDescriptor : byte[] byref * 
        length : uint32 * 
        refLengthNeeded : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: System.IntPtr<br />A handle to a kernel object.</dd><dt>securityInformation</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SecurityInformation">DevCase.Interop.Unmanaged.Win32.Enums.SecurityInformation</a><br />Specifies a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SecurityInformation">SecurityInformation</a> value that identifies the security information being requested.</dd><dt>securityDescriptor</dt><dd>Type: System.Byte[]<br />A pointer to a buffer the function fills with a copy of the security descriptor of the specified object. 

 The calling process must have the right to view the specified aspects of the object's security status. 

 The `SECURITY_DESCRIPTOR` structure is returned in self-relative format.</dd><dt>length</dt><dd>Type: System.UInt32<br />Specifies the size, in bytes, of the buffer pointed to by the *securityDescriptor* parameter.</dd><dt>refLengthNeeded</dt><dd>Type: System.UInt32<br />A pointer to a variable that receives the number of bytes required for the buffer pointed to by the *securityDescriptor* parameter. 

 If this variable's value is greater than the value of the nLength parameter when the function returns, none of the security descriptor is copied to the buffer.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic)

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa446641%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa446641%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />