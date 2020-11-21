# FixedLengthString Class
 

Defines a String with a fixed length.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Text.FixedLengthString<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("FixedLengthString")]
public sealed class FixedLengthString : AestheticObject
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("FixedLengthString")>
Public NotInheritable Class FixedLengthString
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As FixedLengthString
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"FixedLengthString")]
public ref class FixedLengthString sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("FixedLengthString")>]
type FixedLengthString =  
    class
        inherit AestheticObject
    end
```

The FixedLengthString type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_FixedLengthString__ctor">FixedLengthString</a></td><td>
Initializes a new instance of the FixedLengthString class.</td></tr></table>&nbsp;
<a href="#fixedlengthstring-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_FixedLengthString_FixedLength">FixedLength</a></td><td>
Gets or sets the fixed string length.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_FixedLengthString_PaddingChar">PaddingChar</a></td><td>
Gets or sets the padding character thath fills the string.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_FixedLengthString_ValueFixed">ValueFixed</a></td><td>
Gets the fixed string.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_FixedLengthString_ValueUnfixed">ValueUnfixed</a></td><td>
Gets or sets the unmodified string.</td></tr></table>&nbsp;
<a href="#fixedlengthstring-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_FixedLengthString_ToString">ToString</a></td><td>
Returns a String that represents this instance.
 (Overrides AestheticObject.ToString().)</td></tr></table>&nbsp;
<a href="#fixedlengthstring-class">Back to Top</a>

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
<a href="#fixedlengthstring-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim fixedStr As New FixedLengthString("", 10)
MessageBox.Show(String.Format("""{0}""", fixedStr.ValueFixed)) ' Result: "          "

fixedStr.ValueUnfixed = "12345"
MessageBox.Show(String.Format("""{0}""", fixedStr.ValueFixed)) ' Result: "1245      "

fixedStr.ValueUnfixed = "1234567890abc"
MessageBox.Show(String.Format("""{0}""", fixedStr.ValueFixed)) ' Result: "1234567890"
```


## See Also


#### Reference
<a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />