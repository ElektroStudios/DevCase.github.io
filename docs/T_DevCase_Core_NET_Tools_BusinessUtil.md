# BusinessUtil Class
 

Contains businnes/e-commerce related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.NET.Tools.BusinessUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class BusinessUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class BusinessUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As BusinessUtil
```

**C++**<br />
``` C++
public ref class BusinessUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type BusinessUtil =  
    class
        inherit AestheticObject
    end
```

The BusinessUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_NET_Tools_BusinessUtil_ValidateCreditCardNumber">ValidateCreditCardNumber</a></td><td>
Uses the Luhn algorithm to determines whether the specified credit card number is valid. 

 Please de aware that not all valid credit cards can be verified with the Luhn algorithm because it not covers all range of card numbers, however the Luhn algorithm does work for many, if not most, major credit cards. 

 The Luhn algorithm is simply used to prevent transpositional errors, it is useful as a sanity check prior to submitting card numbers to a payment gateway, but not suitable to absolutely validate whether a number is a valid card number. 

 The only way to absolutely verify a credit card number is to validate it via a payment gateway.</td></tr></table>&nbsp;
<a href="#businessutil-class">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="F_DevCase_Core_NET_Tools_BusinessUtil_CreditCardsTestNumbers">CreditCardsTestNumbers</a></td><td>
Contains a collection of credit card numbers for testing purposes.</td></tr></table>&nbsp;
<a href="#businessutil-class">Back to Top</a>

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
<a href="#businessutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />