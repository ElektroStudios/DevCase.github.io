# NumericSequenceFormatter Class
 

Provides a mechanism to perform custom string formatting of a numeric sequence. (Byte, Int16, Int32, Int64, etc.)


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.NumericSequenceFormatter<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class NumericSequenceFormatter : AestheticObject, 
	IFormatProvider, ICustomFormatter
```

**VB**<br />
``` VB
Public NotInheritable Class NumericSequenceFormatter
	Inherits AestheticObject
	Implements IFormatProvider, ICustomFormatter
```

**VB Usage**<br />
``` VB Usage
Dim instance As NumericSequenceFormatter
```

**C++**<br />
``` C++
public ref class NumericSequenceFormatter sealed : public AestheticObject, 
	IFormatProvider, ICustomFormatter
```

**F#**<br />
``` F#
[<SealedAttribute>]
type NumericSequenceFormatter =  
    class
        inherit AestheticObject
        interface IFormatProvider
        interface ICustomFormatter
    end
```

The NumericSequenceFormatter type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_NumericSequenceFormatter__ctor">NumericSequenceFormatter</a></td><td>
Initializes a new instance of the NumericSequenceFormatter class.</td></tr></table>&nbsp;
<a href="#numericsequenceformatter-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_NumericSequenceFormatter_DoFormat__1">DoFormat(T)</a></td><td>
Does the format.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_NumericSequenceFormatter_Format">Format</a></td><td>
Converts the value of a specified object to an equivalent string representation using specified format and culture-specific formatting information.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_NumericSequenceFormatter_GetFormat">GetFormat</a></td><td>
Returns an object that provides formatting services for the specified type.</td></tr></table>&nbsp;
<a href="#numericsequenceformatter-class">Back to Top</a>

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
<a href="#numericsequenceformatter-class">Back to Top</a>

## Remarks


## Examples
This is a code example. 
**VB**<br />
``` VB
Dim arr As Integer() = {1, 10, 100, 1000}

Console.WriteLine(String.Format(New NumericSequenceFormatter(), "Comma separated...........: {0:C}", arr))
Console.WriteLine(String.Format(New NumericSequenceFormatter(), "Comma separated and padded: {0:CP}", arr))
Console.WriteLine()

Console.WriteLine(String.Format(New NumericSequenceFormatter(), "White-Space separated...........: {0:W}", arr))
Console.WriteLine(String.Format(New NumericSequenceFormatter(), "White-Space separated and padded: {0:WP}", arr))
Console.WriteLine()

Console.WriteLine(String.Format(New NumericSequenceFormatter(), "Tab separated...........: {0:T}", arr))
Console.WriteLine(String.Format(New NumericSequenceFormatter(), "Tab-separated and padded: {0:TP}", arr))
Console.WriteLine()

Console.WriteLine(String.Format(New NumericSequenceFormatter(), "Multi-line...........: {0:M}", arr))
Console.WriteLine(String.Format(New NumericSequenceFormatter(), "Multi-line and padded: {0:MP}", arr))
Console.WriteLine()
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />System.IFormatProvider<br />System.ICustomFormatter<br />