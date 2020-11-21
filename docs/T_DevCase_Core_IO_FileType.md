# FileType Class
 

Represents a file type with basic info and its file signatures.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.FileType<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("FileType")]
public sealed class FileType : AestheticObject
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("FileType")>
Public NotInheritable Class FileType
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileType
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"FileType")]
public ref class FileType sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("FileType")>]
type FileType =  
    class
        inherit AestheticObject
    end
```

The FileType type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileType__ctor">FileType(FileSignature, String, String)</a></td><td>
Initializes a new instance of the FileType class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileType__ctor_3">FileType(FileSignature[], String, String)</a></td><td>
Initializes a new instance of the FileType class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileType__ctor_1">FileType(FileSignature, String, String, String)</a></td><td>
Initializes a new instance of the FileType class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileType__ctor_4">FileType(FileSignature[], String, String, String)</a></td><td>
Initializes a new instance of the FileType class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileType__ctor_2">FileType(FileSignature, String, String, String, String)</a></td><td>
Initializes a new instance of the FileType class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileType__ctor_5">FileType(FileSignature[], String, String, String, String)</a></td><td>
Initializes a new instance of the FileType class.</td></tr></table>&nbsp;
<a href="#filetype-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileType_Description">Description</a></td><td>
Gets or sets the description for this filetype.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileType_Extension">Extension</a></td><td>
Gets or sets the filetype extension (e.g: exe, jpg, zip).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileType_Mime">Mime</a></td><td>
Gets or sets the `MIME` name that identifies the content type of the filetype.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileType_Name">Name</a></td><td>
Gets or sets the filetype name.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileType_Signatures">Signatures</a></td><td>
Gets or sets the filetype signatures. 

 A signature is data used to identify or verify the format (content) of a file.</td></tr></table>&nbsp;
<a href="#filetype-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileType_Equals_1">Equals(Object)</a></td><td>
Determines whether the specified Object is equal to this instance.
 (Overrides AestheticObject.Equals(Object).)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileType_Equals">Equals(FileType)</a></td><td>
Determines whether the specified FileType is equal to this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileType_GetHashCode">GetHashCode</a></td><td>
Returns a hash code for this instance.
 (Overrides AestheticObject.GetHashCode().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileType_ToString">ToString</a></td><td>
Returns a String that represents this instance.
 (Overrides AestheticObject.ToString().)</td></tr></table>&nbsp;
<a href="#filetype-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_FileType_op_Equality">Equality</a></td><td>
Implements the operator =</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_FileType_op_Inequality">Inequality</a></td><td>
Implements the operator <></td></tr></table>&nbsp;
<a href="#filetype-class">Back to Top</a>

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
<a href="#filetype-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim signature As New FileSignature({26, 69, 223, 163}, offset:=0, description:="Matroska - Magic Number")
Dim filetype As New FileType(signature, "Matroska stream (generic)", "mkv", "video/x-matroska", "Matroska is an extensible opensource A/V container.")

Dim sb As New Global.System.Text.StringBuilder()
With sb
    .AppendLine(String.Format("Name : {0}", filetype.Name))
    .AppendLine(String.Format("Ext. : {0}", filetype.Extension))
    .AppendLine(String.Format("MIME : {0}", filetype.Mime))
    .AppendLine(String.Format("Desc.: {0}", filetype.Description))

    For Each sig As FileSignature In filetype.Signatures
        .AppendLine()
        .AppendLine(String.Format("Signature Desc.: {0}", sig.Description))
        .AppendLine(String.Format("Signature Hex. : {0}", sig.Hex))
        .AppendLine(String.Format("Signature ASCII: {0}", sig.ASCII))
    Next

End With

Console.WriteLine(sb.ToString())
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />