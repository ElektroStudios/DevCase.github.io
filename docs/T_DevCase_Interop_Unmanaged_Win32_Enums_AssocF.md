# AssocF Enumeration
 

Provides information to the `IQueryAssociations` interface methods.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum AssocF
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration AssocF
```

**VB Usage**<br />
``` VB Usage
Dim instance As AssocF
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class AssocF
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type AssocF
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocF.None">**None**</td><td>0</td><td>None of the following options are set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocF.InitNoRemapClsid">**InitNoRemapClsid**</td><td>1</td><td>Instructs `IQueryAssociations` interface methods not to map CLSID values to ProgID values.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocF.InitByExeName">**InitByExeName**</td><td>2</td><td>Identifies the value of the pwszAssoc parameter of `IQueryAssociations::Init` as an executable file name. 

 If this flag is not set, the root key will be set to the ProgID associated with the .exe key instead of the executable file's ProgID.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocF.InitDefaultToStar">**InitDefaultToStar**</td><td>4</td><td>Specifies that when an `IQueryAssociations` method does not find the requested value under the root key, it should attempt to retrieve the comparable value from the * subkey.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocF.InitDefaultToFolder">**InitDefaultToFolder**</td><td>8</td><td>Specifies that when a `IQueryAssociations` method does not find the requested value under the root key, it should attempt to retrieve the comparable value from the Folder subkey.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocF.NoUserSettings">**NoUserSettings**</td><td>16</td><td>Specifies that only HKEY_CLASSES_ROOT should be searched, and that HKEY_CURRENT_USER should be ignored.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocF.NoTruncate">**NoTruncate**</td><td>32</td><td>Specifies that the return string should not be truncated. 

 Instead, return an error value and the required size for the complete string.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocF.Verify">**Verify**</td><td>64</td><td>Instructs `IQueryAssociations` methods to verify that data is accurate. 

 This setting allows `IQueryAssociations` methods to read data from the user's hard disk for verification. 

 For example, they can check the friendly name in the registry against the one stored in the .exe file. 

 Setting this flag typically reduces the efficiency of the method.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocF.RemapRunDll">**RemapRunDll**</td><td>128</td><td>Instructs IQueryAssociations methods to ignore Rundll.exe and return information about its target. 

 Typically IQueryAssociations methods return information about the first .exe or .dll in a command string. 

 If a command uses Rundll.exe, setting this flag tells the method to ignore Rundll.exe and return information about its target.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocF.NoFixUps">**NoFixUps**</td><td>256</td><td>Instructs IQueryAssociations methods not to fix errors in the registry, such as the friendly name of a function not matching the one found in the .exe file.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocF.IgnoreBaseClass">**IgnoreBaseClass**</td><td>512</td><td>Specifies that the BaseClass value should be ignored.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocF.IgnoreUnknown">**IgnoreUnknown**</td><td>1024</td><td>(Introduced in Windows 7) 

 Specifies that the "Unknown" ProgID should be ignored; instead, fail.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocF.InitFixedProgId">**InitFixedProgId**</td><td>2048</td><td>(Introduced in Windows 8) 

 Specifies that the supplied ProgID should be mapped using the system defaults, rather than the current user defaults.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocF.IsProtocol">**IsProtocol**</td><td>4096</td><td>(Introduced in Windows 8) 

 Specifies that the value is a protocol, and should be mapped using the current user defaults.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AssocF.InitForFile">**InitForFile**</td><td>8192</td><td>(Introduced in Windows 8.1) 

 Specifies that the ProgID corresponds with a file extension based association. 

 Use this flag together with InitFixedProgId.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762471%28v=vs.85%29.asp" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762471%28v=vs.85%29.asp</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />