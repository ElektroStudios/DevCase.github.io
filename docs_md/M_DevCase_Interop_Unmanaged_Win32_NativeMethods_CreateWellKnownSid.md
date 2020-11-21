# NativeMethods.CreateWellKnownSid Method 
 

Creates a SID for predefined aliases.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", SetLastError = true)]
public static bool CreateWellKnownSid(
	WellKnownSidType wellKnownSidType,
	IntPtr domainSid,
	IntPtr sid,
	ref uint refSidSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", SetLastError := true>]
Public Shared Function CreateWellKnownSid ( 
	wellKnownSidType As WellKnownSidType,
	domainSid As IntPtr,
	sid As IntPtr,
	ByRef refSidSize As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim wellKnownSidType As WellKnownSidType
Dim domainSid As IntPtr
Dim sid As IntPtr
Dim refSidSize As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.CreateWellKnownSid(wellKnownSidType, 
	domainSid, sid, refSidSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", SetLastError = true)]
static bool CreateWellKnownSid(
	[InAttribute] WellKnownSidType wellKnownSidType, 
	[InAttribute] IntPtr domainSid, 
	[InAttribute] IntPtr sid, 
	unsigned int% refSidSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", SetLastError = true)>]
static member CreateWellKnownSid : 
        wellKnownSidType : WellKnownSidType * 
        domainSid : IntPtr * 
        sid : IntPtr * 
        refSidSize : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>wellKnownSidType</dt><dd>Type: System.Security.Principal.WellKnownSidType<br />Member of the WellKnownSidType enumeration that specifies what the SID will identify.</dd><dt>domainSid</dt><dd>Type: System.IntPtr<br />A pointer to a SID that identifies the domain to use when creating the SID. Pass Zero to use the local computer.</dd><dt>sid</dt><dd>Type: System.IntPtr<br />A pointer to memory where CreateWellKnownSid will store the new SID.</dd><dt>refSidSize</dt><dd>Type: System.UInt32<br />A pointer to a variable that contains the number of bytes available at *sid* parameter. 

 The CreateWellKnownSid(WellKnownSidType, IntPtr, IntPtr, UInt32) function stores the number of bytes actually used at this location.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/securitybaseapi/nf-securitybaseapi-createwellknownsid" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/securitybaseapi/nf-securitybaseapi-createwellknownsid</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />