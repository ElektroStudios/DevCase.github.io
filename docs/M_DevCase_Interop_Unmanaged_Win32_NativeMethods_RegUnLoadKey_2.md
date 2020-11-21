# NativeMethods.RegUnLoadKey Method (IntPtr, String)
 

Unloads the specified registry key and its subkeys from the registry. 

 Applications that back up or restore system state including system files and registry hives should use the `Volume Shadow Copy` service instead of the registry functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static Win32ErrorCode RegUnLoadKey(
	IntPtr hKey,
	string subKey
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function RegUnLoadKey ( 
	hKey As IntPtr,
	subKey As String
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim hKey As IntPtr
Dim subKey As String
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.RegUnLoadKey(hKey, 
	subKey)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static Win32ErrorCode RegUnLoadKey(
	IntPtr hKey, 
	String^ subKey
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member RegUnLoadKey : 
        hKey : IntPtr * 
        subKey : string -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>hKey</dt><dd>Type: System.IntPtr<br />A handle to the key where the subkey will be unloaded.</dd><dt>subKey</dt><dd>Type: System.String<br />The name of the subkey to be unloaded. 

 The key referred to by the *subKey* parameter must have been created by using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegLoadKey">RegLoadKey(RegistryHive, String, String)</a> function. 

 Key names are not case sensitive.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If the function succeeds, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. 

 If the function fails, the return value is other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms724924%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms724924%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegUnLoadKey">RegUnLoadKey Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />