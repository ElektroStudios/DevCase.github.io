# NativeMethods.RegRenameKey Method (RegistryHive, String, String)
 

**Note: This API is now obsolete.**

Renames a registry subkey.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute]
public static Win32ErrorCode RegRenameKey(
	RegistryHive hive,
	string srcSubKeyPathOrName,
	string dstSubkeyName
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
<ObsoleteAttribute>
Public Shared Function RegRenameKey ( 
	hive As RegistryHive,
	srcSubKeyPathOrName As String,
	dstSubkeyName As String
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim hive As RegistryHive
Dim srcSubKeyPathOrName As String
Dim dstSubkeyName As String
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.RegRenameKey(hive, 
	srcSubKeyPathOrName, dstSubkeyName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute]
static Win32ErrorCode RegRenameKey(
	RegistryHive hive, 
	String^ srcSubKeyPathOrName, 
	String^ dstSubkeyName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
[<ObsoleteAttribute>]
static member RegRenameKey : 
        hive : RegistryHive * 
        srcSubKeyPathOrName : string * 
        dstSubkeyName : string -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>hive</dt><dd>Type: Microsoft.Win32.RegistryHive<br />A handle to the source registry rootkey or subkey.</dd><dt>srcSubKeyPathOrName</dt><dd>Type: System.String<br />The relative path or the name of the source subkey. (eg. "SOFTWARE\My Old SubKey" or "My Old SubKey")</dd><dt>dstSubkeyName</dt><dd>Type: System.String<br />The destination name of the subkey. (eg. "My New SubKey")</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />Returns `0` (zero) if successful; otherwise, a Win32 system error code.

## Remarks
This function is not documented, but it internaly calls `NtRenameKey` function: 

<a href="https://msdn.microsoft.com/en-us/library/cc512138.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/cc512138.aspx</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using regKey As RegistryKey =
    RegistryKey.OpenBaseKey(RegistryHive.LocalMachine, RegistryView.Registry64).
                OpenSubKey("SOFTWARE", RegistryKeyPermissionCheck.ReadWriteSubTree)

    Dim result As Integer = NativeMethods.RegRenameKey(regKey.Handle, "Old SubKey Name", "New SubKey Name")

    If (result <> 0) Then
        Throw New Win32Exception(result)
    End If

End Using
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegRenameKey">RegRenameKey Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />