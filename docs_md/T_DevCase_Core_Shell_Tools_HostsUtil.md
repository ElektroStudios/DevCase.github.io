# HostsUtil Class
 

Contains Windows Hosts-file related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.Tools.HostsUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class HostsUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class HostsUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As HostsUtil
```

**C++**<br />
``` C++
public ref class HostsUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type HostsUtil =  
    class
        inherit AestheticObject
    end
```

The HostsUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_HostsUtil_Filepath">Filepath</a></td><td>
Gets the Hosts filepath.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_HostsUtil_Mappings">Mappings</a></td><td>
Gets the Hosts mappings.</td></tr></table>&nbsp;
<a href="#hostsutil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_Add">Add(HostsMappingInfo)</a></td><td>
Adds a new mapping.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_Add_1">Add(Boolean, String, String, String)</a></td><td>
Adds a new mapping in the Hosts file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_Disable_1">Disable(String)</a></td><td>
Disables an existing mapping.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_Disable">Disable(HostsMappingInfo)</a></td><td>
Disables an existing mapping.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_FileClear">FileClear</a></td><td>
Clears all the mappings in the Hosts file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_FileCreate">FileCreate</a></td><td>
Creates the Hosts file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_FileDelete">FileDelete</a></td><td>
Deletes the Hosts file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_FileExists">FileExists</a></td><td>
Checks whether the Hosts file exists.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_GetMappingFromHostname">GetMappingFromHostname</a></td><td>
Gets a <a href="T_DevCase_Core_Shell_HostsMappingInfo">HostsMappingInfo</a> instance containing the mapping info of a hostname.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_GetMappingsFromIP">GetMappingsFromIP</a></td><td>
Gets a List(T) instance containing the mapping info of all mappings matching the specified IP address.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_IsDisabled_1">IsDisabled(String)</a></td><td>
Checks whether a HostName is already disabled.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_IsDisabled">IsDisabled(HostsMappingInfo)</a></td><td>
Checks whether a HostName is already disabled.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_IsMapped_1">IsMapped(String)</a></td><td>
Checks whether a HostName is already mapped.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_IsMapped">IsMapped(HostsMappingInfo)</a></td><td>
Checks whether a HostName is already mapped.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_Remove_1">Remove(String)</a></td><td>
Removes a mapping.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_HostsUtil_Remove">Remove(HostsMappingInfo)</a></td><td>
Removes a mapping.</td></tr></table>&nbsp;
<a href="#hostsutil-class">Back to Top</a>

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
<a href="#hostsutil-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
' Set a new mapping.
Dim mapping As New HostsMappingInfo
With mapping
    .HostName = "cuantodanio.es"
    .Ip = "127.0.0.1"
    .Comment = "Test mapping comment."
End With

' Delete the Host file.
If HostsUtil.FileExists Then
    HostsUtil.FileDelete()
End If

' Create a new one Hosts file.
HostsUtil.FileCreate(overwrite:=True)

' Add some new mappings.
HostsUtil.Add(mapping)
HostsUtil.Add(enabled:=True, hostName:="www.youtube.com", ip:="127.0.0.1", comment:="Test mapping comment")

' Check whether a mapping exists.
If HostsUtil.IsMapped(mapping) Then
    ' Disable the mapping.
    HostsUtil.Disable(mapping)
End If

' Check whether an existing mapping is disabled.
If HostsUtil.IsDisabled("www.youtube.com") Then
    ' Remove the mapping.
    HostsUtil.Remove("www.youtube.com")
End If

' Get the IP of a mapped Hostname.
MessageBox.Show("cuantodanio.es: " & HostsUtil.GetMappingFromHostname("cuantodanio.es").Ip)

' Get all the hostname mappings
Dim mappings As List(Of HostsMappingInfo) = HostsUtil.Mappings()
For Each mappingInfo As HostsMappingInfo In mappings

    Dim sb As New Global.System.Text.StringBuilder
    With sb
        .AppendLine(String.Format("Hostname...: {0}", mappingInfo.HostName))
        .AppendLine(String.Format("IP Address.: {0}", mappingInfo.Ip))
        .AppendLine(String.Format("Comment....: {0}", mappingInfo.Comment))
        .AppendLine(String.Format("Is Enabled?: {0}", Not mappingInfo.IsDisabled))
    End With

    MessageBox.Show(sb.ToString(), "HostsFile Mappings", MessageBoxButtons.OK, MessageBoxIcon.Information)

Next mappingInfo

' Get all the hostname mappings that matches an ip address
Dim mappingMatches As List(Of HostsMappingInfo) = HostsUtil.GetMappingsFromIP("127.0.0.1")
```


## See Also


#### Reference
<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />