# NativeMethods.RegLoadKey Method (IntPtr, String, String)
 

Creates a subkey under `HKEY_USERS` or `HKEY_LOCAL_MACHINE` and loads the data from the specified registry hive into that subkey. 

 Applications that back up or restore system state including system files and registry hives should use the `Volume Shadow Copy` service instead of the registry functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static Win32ErrorCode RegLoadKey(
	IntPtr hKey,
	string subKey,
	string file
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function RegLoadKey ( 
	hKey As IntPtr,
	subKey As String,
	file As String
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim hKey As IntPtr
Dim subKey As String
Dim file As String
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.RegLoadKey(hKey, 
	subKey, file)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static Win32ErrorCode RegLoadKey(
	IntPtr hKey, 
	String^ subKey, 
	String^ file
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member RegLoadKey : 
        hKey : IntPtr * 
        subKey : string * 
        file : string -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>hKey</dt><dd>Type: System.IntPtr<br />A handle to the key where the subkey will be created. 

 This can be a handle returned by a call to `RegConnectRegistry` function.</dd><dt>subKey</dt><dd>Type: System.String<br />The name of the key to be created under *hKey* parameter. 

 This subkey is where the registration information from the file will be loaded. 

 Key names are not case sensitive.</dd><dt>file</dt><dd>Type: System.String<br />The name of the file containing the registry data. 

 This file must be a local file that was created with the `RegSaveKey` function. 

 If this file does not exist, a file is created with the specified name.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If the function succeeds, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. 

 If the function fails, the return value is other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms724889%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms724889%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegLoadKey">RegLoadKey Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />