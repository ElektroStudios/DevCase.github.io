# TypeWritter Class
 

Simulates text-typying effect like a typewritter.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.Tools.Console.TypeWritter<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class TypeWritter : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class TypeWritter
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As TypeWritter
```

**C++**<br />
``` C++
public ref class TypeWritter sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type TypeWritter =  
    class
        inherit AestheticObject
    end
```

The TypeWritter type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_Write">Write</a></td><td>
Writes text simulating a typewritter effect.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_WriteAsync">WriteAsync</a></td><td>
Asynchronously writes text simulating a typewritter effect.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_WriteColor">WriteColor(String, Char[], Int32, Int32)</a></td><td>
Writes colored text simulating a typewritter effect. 

 Use `*F##*` as the start delimiter of the ForeColor, use `*-F*` as the end delimiter of the ForeColor. 

 Use `*B##*` as the start delimiter of the BackColor, use `*-B*` as the end delimiter of the BackColor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_WriteColor_1">WriteColor(String, ConsoleColor, ConsoleColor, Int32, Int32)</a></td><td>
Writes colored text simulating a typewritter effect.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_WriteColorAsync">WriteColorAsync(CancellationToken, String, Char[], Int32, Int32)</a></td><td>
Asynchronously writes colored text simulating a typewritter effect.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_WriteColorAsync_1">WriteColorAsync(CancellationToken, String, ConsoleColor, ConsoleColor, Int32, Int32)</a></td><td>
Asynchronously writes colored text simulating a typewritter effect.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_WriteColorLine">WriteColorLine(String, Char[], Int32, Int32)</a></td><td>
Writes colored text simulating a typewritter effect, and adds an empty line at the end. 

 Use `*F##*` as the start delimiter of the ForeColor, use `*-F*` as the end delimiter of the ForeColor. 

 Use `*B##*` as the start delimiter of the BackColor, use `*-B*` as the end delimiter of the BackColor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_WriteColorLine_1">WriteColorLine(String, ConsoleColor, ConsoleColor, Int32, Int32)</a></td><td>
Writes colored-text simulating a typewritter effect, and adds an empty line at the end.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_WriteColorLineAsync">WriteColorLineAsync(CancellationToken, String, Char[], Int32, Int32)</a></td><td>
Asynchronously writes colored text simulating a typewritter effect, and adds an empty line at the end. 

 Use `*F##*` as the start delimiter of the ForeColor, use `*-F*` as the end delimiter of the ForeColor. 

 Use `*B##*` as the start delimiter of the BackColor, use `*-B*` as the end delimiter of the BackColor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_WriteColorLineAsync_1">WriteColorLineAsync(CancellationToken, String, ConsoleColor, ConsoleColor, Int32, Int32)</a></td><td>
Asynchronously writes colored text simulating a typewritter effect, and adds an empty line at the end.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_WriteEmptyLine">WriteEmptyLine</a></td><td>
Writes an empty line.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_WriteLine">WriteLine</a></td><td>
Writes text simulating a typewritter effect, and adds a break-line at the end.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_WriteLineAsync">WriteLineAsync</a></td><td>
Asynchronously writes text simulating a typewritter effect, and adds a break-line at the end.</td></tr></table>&nbsp;
<a href="#typewritter-class">Back to Top</a>

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
<a href="#typewritter-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Console.WriteLine()
TypeWritter.WriteColorLine("*F10*Hello *F14*W*F15*o*F13*r*F03*l*F08*d*F11*!*-F*", {"*"c})
TypeWritter.WriteEmptyLine()
TypeWritter.WriteColorLine("This is my typewritter.", ConsoleColor.White, Nothing)
Console.ReadKey()
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />