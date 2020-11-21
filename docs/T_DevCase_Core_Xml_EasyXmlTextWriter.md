# EasyXmlTextWriter Class
 

Wraps a XmlTextWriter to write an Xml document in a easier way


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Xml.EasyXmlTextWriter<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Xml">DevCase.Core.Xml</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class EasyXmlTextWriter : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class EasyXmlTextWriter
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As EasyXmlTextWriter
```

**C++**<br />
``` C++
public ref class EasyXmlTextWriter sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type EasyXmlTextWriter =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The EasyXmlTextWriter type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Xml_EasyXmlTextWriter__ctor">EasyXmlTextWriter</a></td><td>
Initializes a new instance of the EasyXmlTextWriter class.</td></tr></table>&nbsp;
<a href="#easyxmltextwriter-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Xml_EasyXmlTextWriter_XmlWriter">XmlWriter</a></td><td>
The underlying XmlTextWriter instance.</td></tr></table>&nbsp;
<a href="#easyxmltextwriter-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Xml_EasyXmlTextWriter_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Xml_EasyXmlTextWriter_WriteBeginningElement">WriteBeginningElement</a></td><td>
Writes the beginning of an Xml element.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Xml_EasyXmlTextWriter_WriteCommentLine">WriteCommentLine</a></td><td>
Writes an Xml comment line.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Xml_EasyXmlTextWriter_WriteElement">WriteElement</a></td><td>
Writes an Xml element.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Xml_EasyXmlTextWriter_WriteElements">WriteElements</a></td><td>
Writes multiple Xml elements.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Xml_EasyXmlTextWriter_WriteEndElement">WriteEndElement</a></td><td>
Writes the end of an Xml element.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Xml_EasyXmlTextWriter_WriteEof">WriteEof</a></td><td>
Writes the ending Xml end of file. This method should be called to terminate writting the Xml.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Xml_EasyXmlTextWriter_WriteHeader">WriteHeader</a></td><td>
Writes the starting Xml header. This method should be called to start writting the Xml.</td></tr></table>&nbsp;
<a href="#easyxmltextwriter-class">Back to Top</a>

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
<a href="#easyxmltextwriter-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
' Create a disposable instance od the EasyXmlTextWriter class.
Using xmlWriter As New EasyXmlTextWriter("C:\My Xml File.xml", Encoding.Default)

    xmlWriter.XmlWriter.Formatting = Formatting.Indented

    ' Write the Xml header.
    xmlWriter.WriteHeader()
    ' Output at this point:
    ' <?xml version="1.0" encoding="Windows-1252"?>

    ' Write a comment line.
    xmlWriter.WriteCommentLine("Xml Songs Database", Formatting.Indented)
    ' Output at this point:
    ' <?xml version="1.0" encoding="Windows-1252"?>
    ' <!--Xml Songs Database-->

    ' Write the "Songs" root element.
    xmlWriter.WriteBeginningElement("Songs", Formatting.Indented)
    ' Output at this point:
    ' <?xml version="1.0" encoding="Windows-1252"?>
    ' <!--Xml Songs Database-->
    ' <Songs>

    ' Write the start of a "song" element.
    xmlWriter.WriteBeginningElement("Song", Formatting.Indented)
    ' Output at this point:
    ' <?xml version="1.0" encoding="Windows-1252"?>
    ' <!--Xml Songs Database-->
    ' <Songs>
    '  <Song>

    ' Write a "song" element.
    xmlWriter.WriteElements({
                             {"Name", "My Song file.mp3"},
                             {"Year", "2013"},
                             {"Genre", "Rock"}
                            }, Formatting.None)
    ' Output at this point:
    ' <?xml version="1.0" encoding="Windows-1252"?>
    ' <!--Xml Songs Database-->
    ' <Songs>
    '  <Song><Name>My Song file.mp3</Name><Year>2007</Year><Genre>Dance</Genre>

    ' Write the end of a "song" element.
    xmlWriter.WriteEndElement(Formatting.None)
    ' Output at this point:
    ' <?xml version="1.0" encoding="Windows-1252"?>
    ' <!--Xml Songs Database-->
    ' <Songs>
    '  <Song><Name>My Song file.mp3</Name><Year>2007</Year><Genre>Dance</Genre></Song>

    ' Write the end of the "Songs" root element.
    xmlWriter.WriteEndElement(Formatting.Indented)
    ' Output at this point:
    ' Output at this point:
    ' <?xml version="1.0" encoding="Windows-1252"?>
    ' <!--Xml Songs Database-->
    ' <Songs>
    '  <Song><Name>My Song file.mp3</Name><Year>2007</Year><Genre>Dance</Genre></Song>
    ' </Songs>

    ' Write the Xml end of file.
    xmlWriter.WriteEof(closeXmlWriter:=True)

    ' Final output:
    '
    '<?xml version="1.0" encoding="Windows-1252"?>
    '<!--Xml Songs Database-->
    '<Songs>
    '  <Song><Name>My Song file.mp3</Name><Year>2007</Year><Genre>Dance</Genre></Song>
    '</Songs>

End Using
```


## See Also


#### Reference
<a href="N_DevCase_Core_Xml">DevCase.Core.Xml Namespace</a><br />