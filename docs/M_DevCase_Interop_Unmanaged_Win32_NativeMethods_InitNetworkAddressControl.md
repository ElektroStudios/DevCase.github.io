# NativeMethods.InitNetworkAddressControl Method 
 

Initializes the network address control window class.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll")]
public static bool InitNetworkAddressControl()
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll">]
Public Shared Function InitNetworkAddressControl As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = NativeMethods.InitNetworkAddressControl()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll")]
static bool InitNetworkAddressControl()
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll")>]
static member InitNetworkAddressControl : unit -> bool 

```


#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the initialization succeeded; or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shellapi/nf-shellapi-initnetworkaddresscontrol" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shellapi/nf-shellapi-initnetworkaddresscontrol</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />