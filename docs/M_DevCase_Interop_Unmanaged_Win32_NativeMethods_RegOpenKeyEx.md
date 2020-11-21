# NativeMethods.RegOpenKeyEx Method (SafeRegistryHandle, String, UInt32, Int32, IntPtr)
 

Opens the specified registry key. Note that key names are not case sensitive.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static Win32ErrorCode RegOpenKeyEx(
	SafeRegistryHandle hKey,
	string subKey,
	uint options,
	int samDesired,
	ref IntPtr refResult
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function RegOpenKeyEx ( 
	hKey As SafeRegistryHandle,
	subKey As String,
	options As UInteger,
	samDesired As Integer,
	ByRef refResult As IntPtr
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim hKey As SafeRegistryHandle
Dim subKey As String
Dim options As UInteger
Dim samDesired As Integer
Dim refResult As IntPtr
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.RegOpenKeyEx(hKey, 
	subKey, options, samDesired, refResult)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static Win32ErrorCode RegOpenKeyEx(
	SafeRegistryHandle^ hKey, 
	String^ subKey, 
	unsigned int options, 
	int samDesired, 
	IntPtr% refResult
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member RegOpenKeyEx : 
        hKey : SafeRegistryHandle * 
        subKey : string * 
        options : uint32 * 
        samDesired : int * 
        refResult : IntPtr byref -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>hKey</dt><dd>Type: Microsoft.Win32.SafeHandles.SafeRegistryHandle<br />A handle to an open registry key. 

 This handle is returned by the RegCreateKeyEx or RegOpenKeyEx(SafeRegistryHandle, String, UInt32, Int32, IntPtr) function.</dd><dt>subKey</dt><dd>Type: System.String<br />The name of the registry subkey to be opened. 

 Key names are not case sensitive. 

 The *subKey* parameter can be a pointer to an empty string. 

 If *subKey* is a pointer to an empty string and *hKey* is ClassesRoot, *refResult* receives the same hKey handle passed into the function. Otherwise, *refResult* receives a new handle to the key specified by *hKey*. 

 The *subKey* parameter can be a null reference (`Nothing` in Visual Basic) only if *hKey* is one of the predefined keys. 

 If *subKey* is a null reference (`Nothing` in Visual Basic) and *hKey* is ClassesRoot, *refResult* receives a new handle to the key specified by *hKey*. Otherwise, *refResult* receives the same hKey handle passed in to the function.</dd><dt>options</dt><dd>Type: System.UInt32<br />Specifies the option to apply when opening the key.</dd><dt>samDesired</dt><dd>Type: System.Int32<br />A mask that specifies the desired access rights to the key to be opened. 

 The function fails if the security descriptor of the key does not permit the requested access for the calling process.</dd><dt>refResult</dt><dd>Type: System.IntPtr<br />A pointer to a variable that receives a handle to the opened key. 

 If the key is not one of the predefined registry keys, call the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegCloseKey">RegCloseKey(SafeRegistryHandle)</a> function after you have finished using the handle.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If the function succeeds, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. 

 If the function fails, the return value is other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> error code. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winreg/nf-winreg-regopenkeyexa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winreg/nf-winreg-regopenkeyexa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegOpenKeyEx">RegOpenKeyEx Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />