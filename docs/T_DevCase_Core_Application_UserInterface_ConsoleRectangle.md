# ConsoleRectangle Structure
 

Stores a set of four integers that represent the location and size of a (printable) rectangle on a console output buffer.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[ComVisibleAttribute(true)]
public struct ConsoleRectangle
```

**VB**<br />
``` VB
<SerializableAttribute>
<ComVisibleAttribute(true)>
Public Structure ConsoleRectangle
```

**VB Usage**<br />
``` VB Usage
Dim instance As ConsoleRectangle
```

**C++**<br />
``` C++
[SerializableAttribute]
[ComVisibleAttribute(true)]
public value class ConsoleRectangle
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<ComVisibleAttribute(true)>]
type ConsoleRectangle =  struct end
```

The ConsoleRectangle type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle__ctor_2">ConsoleRectangle(Rectangle)</a></td><td>
Initializes a new instance of the ConsoleRectangle structure.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle__ctor">ConsoleRectangle(Point, Size)</a></td><td>
Initializes a new instance of the ConsoleRectangle structure.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle__ctor_3">ConsoleRectangle(Rectangle, Char, Char, Char, Char)</a></td><td>
Initializes a new instance of the ConsoleRectangle structure.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle__ctor_1">ConsoleRectangle(Point, Size, Char, Char, Char, Char)</a></td><td>
Initializes a new instance of the ConsoleRectangle structure.</td></tr></table>&nbsp;
<a href="#consolerectangle-structure">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleRectangle_CharBottom">CharBottom</a></td><td>
Gets or sets the character to print the bottom border of this ConsoleRectangle on a console output buffer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleRectangle_CharLeft">CharLeft</a></td><td>
Gets or sets the character to print the left border of this ConsoleRectangle on a console output buffer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleRectangle_CharRight">CharRight</a></td><td>
Gets or sets the character to print the right border of this ConsoleRectangle on a console output buffer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleRectangle_CharTop">CharTop</a></td><td>
Gets or sets the character to print the top border of this ConsoleRectangle on a console output buffer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleRectangle_Height">Height</a></td><td>
Gets the height of this ConsoleRectangle.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleRectangle_Width">Width</a></td><td>
Gets the width of this ConsoleRectangle.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleRectangle_X">X</a></td><td>
Gets the x-coordinate of the upper-left corner of this ConsoleRectangle.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleRectangle_Y">Y</a></td><td>
Gets the y-coordinate of the upper-left corner of this ConsoleRectangle.</td></tr></table>&nbsp;
<a href="#consolerectangle-structure">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle_Inflate">Inflate(Size)</a></td><td>
Enlarges this ConsoleRectangle by the specified amount.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle_Inflate_1">Inflate(Int32, Int32)</a></td><td>
Enlarges this ConsoleRectangle by the specified amount.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle_Offset">Offset(Point)</a></td><td>
Adjusts the location of this ConsoleRectangle by the specified amount.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle_Offset_1">Offset(Int32, Int32)</a></td><td>
Adjusts the location of this ConsoleRectangle by the specified amount.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle_ToString">ToString</a></td><td>
Returns a String that represents this ConsoleRectangle.
 (Overrides ValueType.ToString().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle_Write">Write</a></td><td>
Writes the bounds of this ConsoleRectangle on the current console output buffer.</td></tr></table>&nbsp;
<a href="#consolerectangle-structure">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle_op_Equality_1">Equality(Rectangle, ConsoleRectangle)</a></td><td>
Tests whether two Rectangle and ConsoleRectangle structures have equal location and size.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle_op_Equality">Equality(ConsoleRectangle, ConsoleRectangle)</a></td><td>
Tests whether two ConsoleRectangle structures have equal location, size and characters.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle_op_Implicit_1">Implicit(Rectangle to ConsoleRectangle)</a></td><td>
Performs an implicit conversion from Rectangle to ConsoleRectangle.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle_op_Implicit">Implicit(ConsoleRectangle to Rectangle)</a></td><td>
Performs an implicit conversion from ConsoleRectangle to Rectangle.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle_op_Inequality_1">Inequality(Rectangle, ConsoleRectangle)</a></td><td>
Determine whether two Rectangle and ConsoleRectangle structures differ in location or size.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleRectangle_op_Inequality">Inequality(ConsoleRectangle, ConsoleRectangle)</a></td><td>
Tests whether two ConsoleRectangle structures differ in location, size or characters.</td></tr></table>&nbsp;
<a href="#consolerectangle-structure">Back to Top</a>

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
<a href="#consolerectangle-structure">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Module Module1

    Public Sub Main()
        Dim rc1Pos As New Point(2, Console.CursorTop + 2)
        Dim rc1 As New ConsoleRectangle(rc1Pos, New Size(32, 4), "▌"c, "▀"c, "▐"c, "▄"c)
        rc1.Write()

        Dim rc2Pos As New Point(2, Console.CursorTop + 2)
        Dim rc2 As New ConsoleRectangle(rc2Pos, New Size(32, 4), "«"c, "—"c, "»"c, "—"c)
        rc2.Write()

        Dim rc3Pos As New Point(2, Console.CursorTop + 2)
        Dim rc3 As New ConsoleRectangle(rc3Pos, New Size(11, 5), "▌"c, "▀"c, "▐"c, "▄"c)
        rc3.Write()

        Dim rc4Pos As New Point(rc3.X + (rc3.Width \ 2), rc3.Y + (rc3.Height \ 2))
        Dim rc4 As New ConsoleRectangle(rc4Pos, rc3.Size, "X"c, "X"c, "X"c, "X"c)
        rc4.Write()

        Console.SetCursorPosition(rc1.X + 9, rc1.Y)
        Console.Write(" Hello World ")
        Console.SetCursorPosition(rc1.X + 6, rc1.Y + 2)
        Console.Write(" By ElektroStudios ")

        Console.CursorVisible = False
        Console.ReadKey(intercept:=True)
    End Sub

End Module
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />