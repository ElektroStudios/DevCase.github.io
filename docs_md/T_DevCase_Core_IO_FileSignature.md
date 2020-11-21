# FileSignature Class
 

Represents a file signature. 

 A file signature is data used to identify or verify the format (content) of a file.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.FileSignature<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("FileSignature")]
public sealed class FileSignature : AestheticObject
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("FileSignature")>
Public NotInheritable Class FileSignature
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileSignature
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"FileSignature")]
public ref class FileSignature sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("FileSignature")>]
type FileSignature =  
    class
        inherit AestheticObject
    end
```

The FileSignature type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileSignature__ctor">FileSignature()</a></td><td>
Initializes a new instance of the FileSignature class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileSignature__ctor_1">FileSignature(Nullable(Byte)[], Int32)</a></td><td>
Initializes a new instance of the FileSignature class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileSignature__ctor_2">FileSignature(Nullable(Byte)[], Int32, String)</a></td><td>
Initializes a new instance of the FileSignature class.</td></tr></table>&nbsp;
<a href="#filesignature-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileSignature_ASCII">ASCII</a></td><td>
Gets the ASCII representation of the signature.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileSignature_Description">Description</a></td><td>
Gets or sets the description for this signature.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileSignature_Hex">Hex</a></td><td>
Gets the Hexadecimal representation of the signature.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileSignature_Offset">Offset</a></td><td>
Gets or sets the offset position of the signature.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_FileSignature_Signature">Signature</a></td><td>
Gets or sets the signature.</td></tr></table>&nbsp;
<a href="#filesignature-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileSignature_Equals_1">Equals(Object)</a></td><td>
Determines whether the specified Object is equal to this instance.
 (Overrides AestheticObject.Equals(Object).)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileSignature_Equals">Equals(FileSignature)</a></td><td>
Determines whether the specified FileSignature is equal to this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_FileSignature_ToString">ToString</a></td><td>
Returns a String that represents this instance.
 (Overrides AestheticObject.ToString().)</td></tr></table>&nbsp;
<a href="#filesignature-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_FileSignature_op_Equality">Equality</a></td><td>
Implements the operator =</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_FileSignature_op_Inequality">Inequality</a></td><td>
Implements the operator <></td></tr></table>&nbsp;
<a href="#filesignature-class">Back to Top</a>

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
<a href="#filesignature-class">Back to Top</a>

## Remarks
Wikipedia: <a href="http://en.wikipedia.org/wiki/File_signature" target="_blank">http://en.wikipedia.org/wiki/File_signature</a>

 File signatures table: <a href="http://www.garykessler.net/library/file_sigs.html" target="_blank">http://www.garykessler.net/library/file_sigs.html</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim sig As New FileSignature({26, 69, 223, 163}, offset:=0, description:="Matroska (mkv) - Magic Number") 

Dim sb As New Global.System.Text.StringBuilder()
With sb
    .AppendLine(String.Format("Desc.: {0}", sig.Description))
    .AppendLine(String.Format("Hex. : {0}", sig.Hex))
    .AppendLine(String.Format("ASCII: {0}", sig.ASCII))
End With

Console.WriteLine(sb.ToString())
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />