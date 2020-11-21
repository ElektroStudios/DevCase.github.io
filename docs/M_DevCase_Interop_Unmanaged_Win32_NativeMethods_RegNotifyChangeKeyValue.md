# NativeMethods.RegNotifyChangeKeyValue Method (SafeRegistryHandle, Boolean, RegNotifyChangeFilter, IntPtr, Boolean)
 

Notifies the caller about changes to the attributes or contents of a specified registry key.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", SetLastError = true)]
public static Win32ErrorCode RegNotifyChangeKeyValue(
	SafeRegistryHandle hKey,
	bool watchSubtree,
	RegNotifyChangeFilter notifyFilter,
	IntPtr hEvent,
	bool asynchronous
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", SetLastError := true>]
Public Shared Function RegNotifyChangeKeyValue ( 
	hKey As SafeRegistryHandle,
	watchSubtree As Boolean,
	notifyFilter As RegNotifyChangeFilter,
	hEvent As IntPtr,
	asynchronous As Boolean
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim hKey As SafeRegistryHandle
Dim watchSubtree As Boolean
Dim notifyFilter As RegNotifyChangeFilter
Dim hEvent As IntPtr
Dim asynchronous As Boolean
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.RegNotifyChangeKeyValue(hKey, 
	watchSubtree, notifyFilter, hEvent, 
	asynchronous)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", SetLastError = true)]
static Win32ErrorCode RegNotifyChangeKeyValue(
	SafeRegistryHandle^ hKey, 
	bool watchSubtree, 
	RegNotifyChangeFilter notifyFilter, 
	IntPtr hEvent, 
	bool asynchronous
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", SetLastError = true)>]
static member RegNotifyChangeKeyValue : 
        hKey : SafeRegistryHandle * 
        watchSubtree : bool * 
        notifyFilter : RegNotifyChangeFilter * 
        hEvent : IntPtr * 
        asynchronous : bool -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>hKey</dt><dd>Type: Microsoft.Win32.SafeHandles.SafeRegistryHandle<br />A handle to an open registry key. 

 This handle is returned by the RegCreateKeyEx or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegOpenKeyEx">RegOpenKeyEx(SafeRegistryHandle, String, UInt32, Int32, IntPtr)</a> function.</dd><dt>watchSubtree</dt><dd>Type: System.Boolean<br />If this parameter is `true` (`True` in Visual Basic), the function reports changes in the specified key and its subkeys. 

 If the parameter is `false` (`False` in Visual Basic), the function reports changes only in the specified key.</dd><dt>notifyFilter</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RegNotifyChangeFilter">DevCase.Interop.Unmanaged.Win32.Enums.RegNotifyChangeFilter</a><br />A value that indicates the changes that should be reported.</dd><dt>hEvent</dt><dd>Type: System.IntPtr<br />A handle to an event. 

 If the *asynchronous* parameter is `true` (`True` in Visual Basic), the function returns immediately and changes are reported by signaling this event. 

 If *asynchronous* is `false` (`False` in Visual Basic), *hEvent* is ignored.</dd><dt>asynchronous</dt><dd>Type: System.Boolean<br />If this parameter is `true` (`True` in Visual Basic), the function returns immediately and reports changes by signaling the specified event. 

 If this parameter is `false` (`False` in Visual Basic), the function does not return until a change has occurred. 

 If *hEvent* does not specify a valid event, the *asynchronous* parameter cannot be `true` (`True` in Visual Basic).</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If the function succeeds, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. 

 If the function fails, the return value is other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winreg/nf-winreg-regnotifychangekeyvalue" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winreg/nf-winreg-regnotifychangekeyvalue</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegNotifyChangeKeyValue">RegNotifyChangeKeyValue Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />