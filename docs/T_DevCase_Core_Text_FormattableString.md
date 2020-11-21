# FormattableString Class
 

Represents a formattable String.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Text.FormattableString<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("FormattableString")]
[DefaultPropertyAttribute("Format")]
public sealed class FormattableString : AestheticObject, 
	IFormattable
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("FormattableString")>
<DefaultPropertyAttribute("Format")>
Public NotInheritable Class FormattableString
	Inherits AestheticObject
	Implements IFormattable
```

**VB Usage**<br />
``` VB Usage
Dim instance As FormattableString
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"FormattableString")]
[DefaultPropertyAttribute(L"Format")]
public ref class FormattableString sealed : public AestheticObject, 
	IFormattable
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("FormattableString")>]
[<DefaultPropertyAttribute("Format")>]
type FormattableString =  
    class
        inherit AestheticObject
        interface IFormattable
    end
```

The FormattableString type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_FormattableString__ctor_1">FormattableString(String, Object[])</a></td><td>
Initializes a new instance of the FormattableString class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_FormattableString__ctor">FormattableString(IFormatProvider, String, Object[])</a></td><td>
Initializes a new instance of the FormattableString class.</td></tr></table>&nbsp;
<a href="#formattablestring-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_FormattableString_Arguments">Arguments</a></td><td>
Gets or sets the objects to format.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_FormattableString_Format">Format</a></td><td>
Gets or sets the composite format string.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Text_FormattableString_FormatProvider">FormatProvider</a></td><td>
Gets or sets the culture-specific formatting provider.</td></tr></table>&nbsp;
<a href="#formattablestring-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_FormattableString_ToString">ToString()</a></td><td>
Returns a String that represents this FormattableString.
 (Overrides AestheticObject.ToString().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Text_FormattableString_ToString_1">ToString(IFormatProvider)</a></td><td>
Returns a String that represents this FormattableString.</td></tr></table>&nbsp;
<a href="#formattablestring-class">Back to Top</a>

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
<a href="#formattablestring-class">Back to Top</a>

## Explicit Interface Implementations
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Text_FormattableString_System_IFormattable_ToString">IFormattable.ToString</a></td><td /></tr></table>&nbsp;
<a href="#formattablestring-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim fstr As New FormattableString("This is a {0}", "test")

' Change arguments.
fstr.Arguments = {0.1}

' Set culture-specific numeric decimal format.
fstr.FormatProvider = CultureInfo.GetCultureInfo("en-US").NumberFormat

' Show resulting string.
Console.WriteLine(fstr.ToString())
```


## See Also


#### Reference
<a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />System.IFormattable<br />