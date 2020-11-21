# GenericAccessRights Enumeration
 

Specifies the generic access rights that correspond to operations specific to a securable object type. 

 Securable objects use an access mask format in which the four high-order bits specify generic access rights. Each type of securable object maps these bits to a set of its standard and object-specific access rights. For example, a Windows file object maps the Read bit to the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">ReadControl</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">Synchronize</a> standard access rights and to the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_FileAccessRights">ReadData</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_FileAccessRights">ReadExtendedAttributes</a>, and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_FileAccessRights">ReadAttributes</a> object-specific access rights. 

 Other types of objects map the Read bit to whatever set of access rights is appropriate for that type of object. 

 You can use generic access rights to specify the type of access you need when you are opening a handle to an object. This is typically simpler than specifying all the corresponding standard and specific rights.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum GenericAccessRights
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration GenericAccessRights
```

**VB Usage**<br />
``` VB Usage
Dim instance As GenericAccessRights
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class GenericAccessRights
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type GenericAccessRights
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GenericAccessRights.All">**All**</td><td>268435456</td><td>Specifies all defined access control on the object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GenericAccessRights.Execute">**Execute**</td><td>536870912</td><td>Specifies access control suitable for executing an action on the object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GenericAccessRights.Read">**Read**</td><td>-2147483648</td><td>Specifies access control suitable for reading the object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GenericAccessRights.Write">**Write**</td><td>1073741824</td><td>Specifies access control suitable for updating attributes on the object.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/secauthz/generic-access-rights" target="_blank">https://docs.microsoft.com/en-us/windows/win32/secauthz/generic-access-rights</a><a href="https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-samr/262970b7-cd4a-41f4-8c4d-5a27f0092aaa" target="_blank">https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-samr/262970b7-cd4a-41f4-8c4d-5a27f0092aaa</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />