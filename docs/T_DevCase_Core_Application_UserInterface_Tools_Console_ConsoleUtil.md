# ConsoleUtil Class
 

Contains Command-line Interface related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.Tools.Console.ConsoleUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ConsoleUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class ConsoleUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As ConsoleUtil
```

**C++**<br />
``` C++
public ref class ConsoleUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ConsoleUtil =  
    class
        inherit AestheticObject
    end
```

The ConsoleUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_DisplayMode">DisplayMode</a></td><td>
Gets the window handle of the console associated with the calling process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_Handle">Handle</a></td><td>
Gets the window handle of the console associated with the calling process.</td></tr></table>&nbsp;
<a href="#consoleutil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_ArgumentsAreEmpty">ArgumentsAreEmpty</a></td><td>
Determines whether the command-line arguments for the current process are empty.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_ClearCurrentLine">ClearCurrentLine</a></td><td>
Clears the current console line.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_CommandLineParameterPrefixToChar">CommandLineParameterPrefixToChar</a></td><td>
Translates a <a href="T_DevCase_Core_Application_CommandLineParameterPrefix">CommandLineParameterPrefix</a> to its equivalent character. 

 For Example: CommandLineParameterPrefix.Slash -> "/"</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_CommandLineParameterSuffixToChar">CommandLineParameterSuffixToChar</a></td><td>
Translates a <a href="T_DevCase_Core_Application_CommandLineParameterSuffix">CommandLineParameterSuffix</a> to its equivalent character. 

 For Example: CommandLineParameterSuffix.EqualsSign -> "="</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_ConsoleTextBlink">ConsoleTextBlink(Point, Int32, Int32)</a></td><td>
Blinks the specified text for indefinitely time on the current attached console window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_ConsoleTextBlink_2">ConsoleTextBlink(Point, Int32, TimeSpan)</a></td><td>
Blinks the specified text for indefinitely time on the current attached console window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_ConsoleTextBlink_1">ConsoleTextBlink(Point, Int32, Int32, Int32)</a></td><td>
Blinks the specified text for the specified amount of times on the current attached console window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_ConsoleTextBlink_3">ConsoleTextBlink(Point, Int32, TimeSpan, Int32)</a></td><td>
Blinks the specified text for the specified amount of times on the current attached console window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_GetArgumentValue__1">GetArgumentValue(T)</a></td><td>
Determines whether the specified <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> is assigned in the given command-line argument, then tries to get the assigned value of the parameter.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_HideConsole">HideConsole</a></td><td>
Hides the console window associated with the calling process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_IsParameterAssignedInArgument">IsParameterAssignedInArgument(CommandLineParameter, String)</a></td><td>
Determines whether the specified <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> is assigned in the given command-line argument.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_IsParameterAssignedInArgument_2">IsParameterAssignedInArgument(CommandLineParameterPrefix, String, String)</a></td><td>
Determines whether the specified command-line parameter is assigned in the given command-line argument.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_IsParameterAssignedInArgument_1">IsParameterAssignedInArgument(CommandLineParameterPrefix, String, CommandLineParameterSuffix, String)</a></td><td>
Determines whether the specified command-line parameter is assigned in the given command-line argument.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_IsParameterAssignedInArgument__1">IsParameterAssignedInArgument(T)(CommandLineValueParameter(T), String)</a></td><td>
Determines whether the specified <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> is assigned in the given command-line argument.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_JoinArguments">JoinArguments</a></td><td>
Returns a single string representation of the command-line arguments for the current process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_Pause">Pause()</a></td><td>
Pause the console execution indefinitely until any key is pressed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_Pause_1">Pause(Keys)</a></td><td>
Pause the console execution indefinitely until the specified key is pressed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_SetConsolefont">SetConsolefont</a></td><td>
Sets the text font for the console attached to the current process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_SetParameterValue__1">SetParameterValue(T)</a></td><td>
Determines whether the specified <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> is assigned in the given command-line argument, then tries to set the assigned value of the parameter.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_ShowConsole">ShowConsole</a></td><td>
Shows the console window associated with the calling process.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_SpinCursor">SpinCursor</a></td><td>
Animates the console cursor producing a spin effect.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_SpinCursorAsync">SpinCursorAsync</a></td><td>
Asynchronously animates the console cursor producing a spin effect.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_WriteColorText">WriteColorText(String, Char[])</a></td><td>
Writes colored text on the Console. 

 Use `*F##*` as the start delimiter of the ForeColor, use `*-F*` as the end delimiter of the ForeColor. 

 Use `*B##*` as the start delimiter of the BackColor, use `*-B*` as the end delimiter of the BackColor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_WriteColorText_1">WriteColorText(String, ConsoleColor, ConsoleColor)</a></td><td>
Writes colored text on the Console.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_WriteColorTextLine">WriteColorTextLine(String, Char[])</a></td><td>
Writes colored text on the Console and adds an empty line at the end. 

 Use `*F##*` as the start delimiter of the ForeColor, use `*-F*` as the end delimiter of the ForeColor. 

 Use `*B##*` as the start delimiter of the BackColor, use `*-B*` as the end delimiter of the BackColor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_WriteColorTextLine_1">WriteColorTextLine(String, ConsoleColor, ConsoleColor)</a></td><td>
Writes colored text on the Console and adds an empty line at the end.</td></tr></table>&nbsp;
<a href="#consoleutil-class">Back to Top</a>

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
<a href="#consoleutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />