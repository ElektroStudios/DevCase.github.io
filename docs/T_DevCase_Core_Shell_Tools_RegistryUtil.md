# RegistryUtil Class
 

Contains registry related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.Tools.RegistryUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class RegistryUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class RegistryUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As RegistryUtil
```

**C++**<br />
``` C++
public ref class RegistryUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type RegistryUtil =  
    class
        inherit AestheticObject
    end
```

The RegistryUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_CopyKeyTree">CopyKeyTree(RegistryView, String, RegistryView, String)</a></td><td>
Copies a registry key tree to another registry path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_CopyKeyTree_1">CopyKeyTree(RegistryView, String, String, RegistryView, String, String)</a></td><td>
Copies a registry key tree to another registry path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_CopySubKeys">CopySubKeys(RegistryView, String, RegistryView, String)</a></td><td>
Copies the sub-keys of the specified registry key.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_CopySubKeys_1">CopySubKeys(RegistryView, String, String, RegistryView, String, String)</a></td><td>
Copies the sub-keys of the specified registry key.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_CopyValue">CopyValue(RegistryView, String, String, RegistryView, String, String)</a></td><td>
Copies a registry value (with its data) to another subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_CopyValue_1">CopyValue(RegistryView, String, String, String, RegistryView, String, String, String)</a></td><td>
Copies a registry value (with its data) to another subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_CreateSubKey">CreateSubKey(RegInfo, RegistryKeyPermissionCheck, RegistryOptions)</a></td><td>
Creates a new registry subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_CreateSubKey_1">CreateSubKey(RegistryView, String, RegistryKeyPermissionCheck, RegistryOptions)</a></td><td>
Creates a new registry subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_CreateSubKey_2">CreateSubKey(RegistryView, String, String, RegistryKeyPermissionCheck, RegistryOptions)</a></td><td>
Creates a new registry subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_CreateSubKey__1">CreateSubKey(T)(RegInfo(T), RegistryKeyPermissionCheck, RegistryOptions)</a></td><td>
Creates a new registry subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_CreateSubKey__1_1">CreateSubKey(T)(RegistryView, String, RegistryKeyPermissionCheck, RegistryOptions)</a></td><td>
Creates a new registry subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_CreateSubKey__1_2">CreateSubKey(T)(RegistryView, String, String, RegistryKeyPermissionCheck, RegistryOptions)</a></td><td>
Creates a new registry subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_CreateValue__1">CreateValue(T)(RegInfo(T))</a></td><td>
Creates or replaces a registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_CreateValue__1_2">CreateValue(T)(RegistryView, String, String, T, RegistryValueKind)</a></td><td>
Creates or replaces a registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_CreateValue__1_1">CreateValue(T)(RegistryView, String, String, String, T, RegistryValueKind)</a></td><td>
Creates or replaces a registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_DeleteSubKey">DeleteSubKey(RegistryView, String, Boolean)</a></td><td>
Deletes a registry subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_DeleteSubKey_1">DeleteSubKey(RegistryView, String, String, Boolean)</a></td><td>
Deletes a registry subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_DeleteSubKey__1">DeleteSubKey(T)(RegInfo(T), Boolean)</a></td><td>
Deletes a registry subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_DeleteValue">DeleteValue(RegistryView, String, String, Boolean)</a></td><td>
Deletes a registry subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_DeleteValue_1">DeleteValue(RegistryView, String, String, String, Boolean)</a></td><td>
Deletes a registry subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_DeleteValue__1">DeleteValue(T)(RegInfo(T), Boolean)</a></td><td>
Deletes a registry subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_ExistSubKey">ExistSubKey(RegistryView, String)</a></td><td>
Determines whether a registry subkey exists.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_ExistSubKey_1">ExistSubKey(RegistryView, String, String)</a></td><td>
Determines whether a registry subkey exists.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_ExistSubKey__1">ExistSubKey(T)(RegInfo(T))</a></td><td>
Determines whether a registry subkey exists.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_ExistValue">ExistValue(RegistryView, String, String)</a></td><td>
Determines whether a registry subkey exists.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_ExistValue_1">ExistValue(RegistryView, String, String, String)</a></td><td>
Determines whether a registry value exists.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_ExistValue__1">ExistValue(T)(RegInfo(T))</a></td><td>
Determines whether a registry value exists.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_ExportKey">ExportKey(RegistryView, String, String)</a></td><td>
Exports a key to a registry file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_ExportKey_1">ExportKey(RegistryView, String, String, String)</a></td><td>
Exports a key to a registry file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_FindSubKey">FindSubKey(RegistryView, String, String, Boolean, Boolean, SearchOption)</a></td><td>
Finds on a registry path all the subkey names that matches the specified criteria.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_FindSubKey_1">FindSubKey(RegistryView, String, String, String, Boolean, Boolean, SearchOption)</a></td><td>
Finds on a registry path all the subkey names that matches the specified criteria.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_FindValue">FindValue(RegistryView, String, String, Boolean, Boolean, SearchOption)</a></td><td>
Finds on a registry path all the value names that matches the specified criteria.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_FindValue_1">FindValue(RegistryView, String, String, String, Boolean, Boolean, SearchOption)</a></td><td>
Finds on a registry path all the value names that matches the specified criteria.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_FindValueData">FindValueData</a></td><td>
Finds on a registry path all the values that contains data that matches the specified criteria.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_GetRootKey">GetRootKey</a></td><td>
Gets the root RegistryKey of a registry path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_GetRootKeyName">GetRootKeyName</a></td><td>
Gets the root key name of a registry path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_GetSubKeyPath">GetSubKeyPath</a></td><td>
Gets the subkey path of a registry path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_GetValueData">GetValueData(RegInfo, RegistryValueOptions)</a></td><td>
Gets the data of a registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_GetValueData_1">GetValueData(RegInfo, Object, RegistryValueOptions)</a></td><td>
Gets the data of a registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_GetValueData_2">GetValueData(RegistryView, String, String, RegistryValueOptions)</a></td><td>
Gets the data of a registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_GetValueData_3">GetValueData(RegistryView, String, String, Object, RegistryValueOptions)</a></td><td>
Gets the data of a registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_GetValueData_4">GetValueData(RegistryView, String, String, String, RegistryValueOptions)</a></td><td>
Gets the data of a registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_GetValueData_5">GetValueData(RegistryView, String, String, String, Object, RegistryValueOptions)</a></td><td>
Gets the data of a registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_GetValueData__1">GetValueData(T)(RegInfo(T), RegistryValueOptions)</a></td><td>
Gets the data of a registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_GetValueData__1_1">GetValueData(T)(RegInfo(T), T, RegistryValueOptions)</a></td><td>
Gets the data of a registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_GetValueData__1_2">GetValueData(T)(RegistryView, String, String, RegistryValueOptions)</a></td><td>
Gets the data of a registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_GetValueData__1_3">GetValueData(T)(RegistryView, String, String, String, RegistryValueOptions)</a></td><td>
Gets the data of a registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_GetValueData__1_5">GetValueData(T)(RegistryView, String, String, T, RegistryValueOptions)</a></td><td>
Gets the data of a registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_GetValueData__1_4">GetValueData(T)(RegistryView, String, String, String, T, RegistryValueOptions)</a></td><td>
Gets the data of a registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_ImportRegFile">ImportRegFile</a></td><td>
Imports a registry file into the current registry Hive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_IsRegistryFile">IsRegistryFile</a></td><td>
Determines whether a file is a valid Registry script file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_JumpToKey">JumpToKey(RegistryView, String)</a></td><td>
Runs Registry.exe process to jump at the specified key.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_JumpToKey_1">JumpToKey(RegistryView, String, String)</a></td><td>
Runs Regedit.exe process to jump at the specified key.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_LoadHive">LoadHive</a></td><td>
Loads the subkeys of a hive file, creating a subkey with the specified name into `HKEY_LOCAL_MACHINE` root key.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_MoveKeyTree">MoveKeyTree(RegistryView, String, RegistryView, String)</a></td><td>
Moves a registry key tree to another registry path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_MoveKeyTree_1">MoveKeyTree(RegistryView, String, String, RegistryView, String, String)</a></td><td>
Moves a registry key tree to another registry path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_MoveSubKeys">MoveSubKeys(RegistryView, String, RegistryView, String)</a></td><td>
Moves the sub-keys of the specified registry key.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_MoveSubKeys_1">MoveSubKeys(RegistryView, String, String, RegistryView, String, String)</a></td><td>
Moves the sub-keys of the specified registry key.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_MoveValue">MoveValue(RegistryView, String, String, RegistryView, String, String)</a></td><td>
Moves a registry value (with its data) to another subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_MoveValue_1">MoveValue(RegistryView, String, String, String, RegistryView, String, String, String)</a></td><td>
Moves a registry value (with its data) to another subkey.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_UnloadHive">UnloadHive</a></td><td>
Unloads a previously hive file that has been loaded into `HKEY_LOCAL_MACHINE` root key.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_ValueIsEmpty">ValueIsEmpty(RegistryView, String, String)</a></td><td>
Determines whether a registry value is empty.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_RegistryUtil_ValueIsEmpty_1">ValueIsEmpty(RegistryView, String, String, String)</a></td><td>
Determines whether a registry value is empty.</td></tr></table>&nbsp;
<a href="#registryutil-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#registryutil-class">Back to Top</a>

## Examples
This is a code example that demonstrates various functionalities. 
**VB**<br />
``` VB
' ----------------
' Instance RegInfo
' ----------------

Dim regInfo As New RegInfo
With regInfo
    .RootKeyName = "HKCU"
    .SubKeyPath = "Subkey Path"
    .ValueName = "Value Name"
    .ValueType = Microsoft.Win32.RegistryValueKind.String
    .ValueData = "Hello World!"
End With

Dim regInfoByte As New RegInfo(Of Byte())
With regInfoByte
    .RootKeyName = "HKCU"
    .SubKeyPath = "Subkey Path"
    .ValueName = "Value Name"
    .ValueType = Microsoft.Win32.RegistryValueKind.Binary
    .ValueData = Global.System.Text.Encoding.ASCII.GetBytes("Hello World!")
End With

' ----------------
' Create SubKey
' ----------------

RegistryUtil.CreateSubKey(fullKeyPath:="HKCU\Subkey Path\")
RegistryUtil.CreateSubKey(rootKeyName:="HKCU",
                     subKeyPath:="Subkey Path")
RegistryUtil.CreateSubKey(regInfo:=regInfoByte)

Dim regKey1 As Microsoft.Win32.RegistryKey =
    RegistryUtil.CreateSubKey(fullKeyPath:="HKCU\Subkey Path\",
                         registryKeyPermissionCheck:=Microsoft.Win32.RegistryKeyPermissionCheck.Default,
                         registryOptions:=Microsoft.Win32.RegistryOptions.None)

Dim regKey2 As Microsoft.Win32.RegistryKey =
    RegistryUtil.CreateSubKey(rootKeyName:="HKCU",
                         subKeyPath:="Subkey Path",
                         registryKeyPermissionCheck:=Microsoft.Win32.RegistryKeyPermissionCheck.Default,
                         registryOptions:=Microsoft.Win32.RegistryOptions.None)

Dim regInfo2 As Registry.RegInfo(Of String) = RegistryUtil.CreateSubKey(Of String)(fullKeyPath:="HKCU\Subkey Path\")
Dim regInfo3 As Registry.RegInfo(Of String) = RegistryUtil.CreateSubKey(Of String)(rootKeyName:="HKCU",
                                                                             subKeyPath:="Subkey Path")

' ----------------
' Create Value
' ----------------

RegistryUtil.CreateValue(fullKeyPath:="HKCU\Subkey Path\",
                    valueName:="Value Name",
                    valueData:="Value Data",
                    valueType:=Microsoft.Win32.RegistryValueKind.String)

RegistryUtil.CreateValue(rootKeyName:="HKCU",
                    subKeyPath:="Subkey Path",
                    valueName:="Value Name",
                    valueData:="Value Data",
                    valueType:=Microsoft.Win32.RegistryValueKind.String)

RegistryUtil.CreateValue(regInfo:=regInfoByte)

RegistryUtil.CreateValue(Of String)(fullKeyPath:="HKCU\Subkey Path\",
                               valueName:="Value Name",
                               valueData:="Value Data",
                               valueType:=Microsoft.Win32.RegistryValueKind.String)

RegistryUtil.CreateValue(Of String)(rootKeyName:="HKCU",
                               subKeyPath:="Subkey Path",
                               valueName:="Value Name",
                               valueData:="Value Data",
                               valueType:=Microsoft.Win32.RegistryValueKind.String)

RegistryUtil.CreateValue(Of Byte())(regInfo:=regInfoByte)

' ----------------
' Copy KeyTree
' ----------------

RegistryUtil.CopyKeyTree(srcFullKeyPath:="HKCU\Source Subkey Path\",
                    dstFullKeyPath:="HKCU\Target Subkey Path\")

RegistryUtil.CopyKeyTree(srcRootKeyName:="HKCU",
                    srcSubKeyPath:="Source Subkey Path\",
                    dstRootKeyName:="HKCU",
                    dstSubKeyPath:="Target Subkey Path\")

' ----------------
' Move KeyTree
' ----------------

RegistryUtil.MoveKeyTree(srcFullKeyPath:="HKCU\Source Subkey Path\",
                    dstFullKeyPath:="HKCU\Target Subkey Path\")

RegistryUtil.MoveKeyTree(srcRootKeyName:="HKCU",
                    srcSubKeyPath:="Source Subkey Path\",
                    dstRootKeyName:="HKCU",
                    dstSubKeyPath:="Target Subkey Path\")

' ----------------
' Copy SubKeys
' ----------------

RegistryUtil.CopySubKeys(srcFullKeyPath:="HKCU\Source Subkey Path\",
                    dstFullKeyPath:="HKCU\Target Subkey Path\")

RegistryUtil.CopySubKeys(srcRootKeyName:="HKCU",
                    srcSubKeyPath:="Source Subkey Path\",
                    dstRootKeyName:="HKCU",
                    dstSubKeyPath:="Target Subkey Path\")

' ----------------
' Move SubKeys
' ----------------

RegistryUtil.MoveSubKeys(srcFullKeyPath:="HKCU\Source Subkey Path\",
                    dstFullKeyPath:="HKCU\Target Subkey Path\")

RegistryUtil.MoveSubKeys(srcRootKeyName:="HKCU",
                    srcSubKeyPath:="Source Subkey Path\",
                    dstRootKeyName:="HKCU",
                    dstSubKeyPath:="Target Subkey Path\")

' ----------------
' Copy Value
' ----------------

Registry.CopyValue(srcFullKeyPath:="HKCU\Source Subkey Path\",
                  sourceValueName:="Value Name",
                  dstFullKeyPath:="HKCU\Target Subkey Path\",
                  targetValueName:="Value Name")

Registry.CopyValue(srcRootKeyName:="HKCU",
                  srcSubKeyPath:="Source Subkey Path\",
                  sourceValueName:="Value Name",
                  dstRootKeyName:="HKCU",
                  dstSubKeyPath:="Target Subkey Path\",
                  targetValueName:="Value Name")

' ----------------
' Move Value
' ----------------

Registry.MoveValue(srcFullKeyPath:="HKCU\Source Subkey Path\",
                  sourceValueName:="Value Name",
                  dstFullKeyPath:="HKCU\Target Subkey Path\",
                  targetValueName:="Value Name")

Registry.MoveValue(srcRootKeyName:="HKCU",
                  srcSubKeyPath:="Source Subkey Path\",
                  sourceValueName:="Value Name",
                  dstRootKeyName:="HKCU",
                  dstSubKeyPath:="Target Subkey Path\",
                  targetValueName:="Value Name")

' ----------------
' DeleteValue
' ----------------

RegistryUtil.DeleteValue(fullKeyPath:="HKCU\Subkey Path\",
                    valueName:="Value Name",
                    throwOnMissingValue:=True)

RegistryUtil.DeleteValue(rootKeyName:="HKCU",
                    subKeyPath:="Subkey Path",
                    valueName:="Value Name",
                    throwOnMissingValue:=True)

RegistryUtil.DeleteValue(regInfo:=regInfoByte,
                    throwOnMissingValue:=True)

' ----------------
' Delete SubKey
' ----------------

RegistryUtil.DeleteSubKey(fullKeyPath:="HKCU\Subkey Path\",
                     throwOnMissingSubKey:=False)

RegistryUtil.DeleteSubKey(rootKeyName:="HKCU",
                     subKeyPath:="Subkey Path",
                     throwOnMissingSubKey:=False)

RegistryUtil.DeleteSubKey(regInfo:=regInfoByte,
                     throwOnMissingSubKey:=False)

' ----------------
' Exist SubKey?
' ----------------

Dim exist1 As Boolean = RegistryUtil.ExistSubKey(fullKeyPath:="HKCU\Subkey Path\")

Dim exist2 As Boolean = RegistryUtil.ExistSubKey(rootKeyName:="HKCU",
                                            subKeyPath:="Subkey Path")

' ----------------
' Exist Value?
' ----------------

Dim exist3 As Boolean = RegistryUtil.ExistValue(fullKeyPath:="HKCU\Subkey Path\",
                                           valueName:="Value Name")

Dim exist4 As Boolean = RegistryUtil.ExistValue(rootKeyName:="HKCU",
                                           subKeyPath:="Subkey Path",
                                           valueName:="Value Name")

' ----------------
' Value Is Empty?
' ----------------

Dim isEmpty1 As Boolean = RegistryUtil.ValueIsEmpty(fullKeyPath:="HKCU\Subkey Path\",
                                               valueName:="Value Name")

Dim isEmpty2 As Boolean = RegistryUtil.ValueIsEmpty(rootKeyName:="HKCU",
                                               subKeyPath:="Subkey Path",
                                               valueName:="Value Name")

' ----------------
' Export Key
' ----------------

RegistryUtil.ExportKey(fullKeyPath:="HKCU\Subkey Path\",
                  outputFile:="C:\Backup.reg")

RegistryUtil.ExportKey(rootKeyName:="HKCU",
                  subKeyPath:="Subkey Path",
                  outputFile:="C:\Backup.reg")

' ----------------
' Import RegFile
' ----------------

Registry.ImportRegFile(regFilePath:="C:\Backup.reg")

' ----------------
' Jump To Key
' ----------------

RegistryUtil.JumpToKey(fullKeyPath:="HKCU\Subkey Path\")

RegistryUtil.JumpToKey(rootKeyName:="HKCU",
                  subKeyPath:="Subkey Path")

' ----------------
' Find SubKey
' ----------------

Dim regInfoSubkeyCol As IEnumerable(Of Registry.Reginfo) =
    RegistryUtil.FindSubKey(rootKeyName:="HKCU",
                       subKeyPath:="Subkey Path",
                       subKeyName:="Subkey Name",
                       matchFullSubKeyName:=False,
                       ignoreCase:=True,
                       searchOption:=IO.SearchOption.AllDirectories)

For Each reg As Registry.RegInfo In regInfoSubkeyCol
    Debug.WriteLine(reg.RootKeyName)
    Debug.WriteLine(reg.SubKeyPath)
    Debug.WriteLine(reg.ValueName)
    Debug.WriteLine(reg.ValueData.ToString())
    Debug.WriteLine("")
Next reg

' ----------------
' Find Value
' ----------------

Dim regInfoValueNameCol As IEnumerable(Of Registry.Reginfo) =
    RegistryUtil.FindValue(rootKeyName:="HKCU",
                          subKeyPath:="Subkey Path",
                          valueName:="Value Name",
                          matchFullValueName:=False,
                          ignoreCase:=True,
                          searchOption:=IO.SearchOption.AllDirectories)

For Each reg As Registry.RegInfo In regInfoValueNameCol
    Debug.WriteLine(reg.RootKeyName)
    Debug.WriteLine(reg.SubKeyPath)
    Debug.WriteLine(reg.ValueName)
    Debug.WriteLine(reg.ValueData.ToString())
    Debug.WriteLine("")
Next reg

' ----------------
' Find Value Data
' ----------------

Dim regInfoValueDataCol As IEnumerable(Of Registry.Reginfo) =
    RegistryUtil.FindValueData(rootKeyName:="HKCU",
                          subKeyPath:="Subkey Path",
                          valueData:="Value Data",
                          matchFullData:=False,
                          ignoreCase:=True,
                          searchOption:=IO.SearchOption.AllDirectories)

For Each reg As Registry.RegInfo In regInfoValueDataCol
    Debug.WriteLine(reg.RootKeyName)
    Debug.WriteLine(reg.SubKeyPath)
    Debug.WriteLine(reg.ValueName)
    Debug.WriteLine(reg.ValueData.ToString())
    Debug.WriteLine("")
Next reg

' ----------------
' Get...
' ----------------

Dim rootKeyName As String = RegistryUtil.GetRootKeyName(registryPath:="HKCU\Subkey Path\")
Dim subKeyPath As String = RegistryUtil.GetSubKeyPath(registryPath:="HKCU\Subkey Path\")
Dim rootKey As Microsoft.Win32.RegistryKey = RegistryUtil.GetRootKey(registryPath:="HKCU\Subkey Path\")

' ----------------
' Get Value Data
' ----------------

Dim dataObject As Object = RegistryUtil.GetValueData(rootKeyName:="HKCU",
                                                subKeyPath:="Subkey Path",
                                                valueName:="Value Name")

Dim dataString As String = RegistryUtil.GetValueData(Of String)(fullKeyPath:="HKCU\Subkey Path\",
                                                           valueName:="Value Name",
                                                           registryValueOptions:=Microsoft.Win32.RegistryValueOptions.DoNotExpandEnvironmentNames)

Dim dataByte As Byte() = RegistryUtil.GetValueData(Of Byte())(regInfo:=regInfoByte,
                                                         registryValueOptions:=Microsoft.Win32.RegistryValueOptions.None)
Debug.WriteLine("dataByte=" & String.Join(",", dataByte))

' -----------------
 Set UserAccessKey
' -----------------

Registry.SetUserAccessKey(fullKeyPath:="HKCU\Subkey Path",
                         userAccess:={Registry.ReginiUserAccess.AdministratorsFullAccess})

Registry.SetUserAccessKey(rootKeyName:="HKCU",
                         subKeyPath:="Subkey Path",
                         userAccess:={Registry.ReginiUserAccess.AdministratorsFullAccess,
                                      Registry.ReginiUserAccess.CreatorFullAccess,
                                      Registry.ReginiUserAccess.SystemFullAccess})
```


## See Also


#### Reference
<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />