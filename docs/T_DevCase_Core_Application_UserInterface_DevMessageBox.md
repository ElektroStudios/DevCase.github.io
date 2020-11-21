# DevMessageBox Class
 

Represents a MessageBox that will be displayed centered to the specified Form or Control.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.Application.UserInterface.DevMessageBox<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class DevMessageBox : IDisposable
```

**VB**<br />
``` VB
Public Class DevMessageBox
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevMessageBox
```

**C++**<br />
``` C++
public ref class DevMessageBox : IDisposable
```

**F#**<br />
``` F#
type DevMessageBox =  
    class
        interface IDisposable
    end
```

The DevMessageBox type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox__ctor">DevMessageBox(Control)</a></td><td>
Initializes a new instance of the DevMessageBox class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox__ctor_2">DevMessageBox(Form)</a></td><td>
Initializes a new instance of the DevMessageBox class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox__ctor_1">DevMessageBox(Control, Int32)</a></td><td>
Initializes a new instance of the DevMessageBox class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox__ctor_3">DevMessageBox(Form, Int32)</a></td><td>
Initializes a new instance of the DevMessageBox class.</td></tr></table>&nbsp;
<a href="#devmessagebox-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_DevMessageBox_Owner">Owner</a></td><td>
Gets the owner Control to center the DevMessageBox.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_DevMessageBox_TimeOut">TimeOut</a></td><td>
Gets or sets the time interval to auto-close this DevMessageBox, in milliseconds. Default value is '0', which means Infinite.</td></tr></table>&nbsp;
<a href="#devmessagebox-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox_Show">Show(String)</a></td><td>
Displays a message box with specified text.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox_Show_1">Show(String, String)</a></td><td>
Displays a message box with specified text and caption.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox_Show_2">Show(String, String, MessageBoxButtons)</a></td><td>
Displays a message box with specified text, caption, and buttons.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox_Show_3">Show(String, String, MessageBoxButtons, MessageBoxIcon)</a></td><td>
Displays a message box with specified text, caption, buttons, and icon.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox_Show_4">Show(String, String, MessageBoxButtons, MessageBoxIcon, MessageBoxDefaultButton)</a></td><td>
Displays a message box with the specified text, caption, buttons, icon, and default button.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox_Show_5">Show(String, String, MessageBoxButtons, MessageBoxIcon, MessageBoxDefaultButton, MessageBoxOptions)</a></td><td>
Displays a message box with the specified text, caption, buttons, icon, default button, and options.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox_Show_6">Show(String, String, MessageBoxButtons, MessageBoxIcon, MessageBoxDefaultButton, MessageBoxOptions, Boolean)</a></td><td>
Displays a message box with the specified text, caption, buttons, icon, default button, options, and Help button.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox_Show_7">Show(String, String, MessageBoxButtons, MessageBoxIcon, MessageBoxDefaultButton, MessageBoxOptions, String)</a></td><td>
Displays a message box with the specified text, caption, buttons, icon, default button, options, and Help button, using the specified Help file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox_Show_8">Show(String, String, MessageBoxButtons, MessageBoxIcon, MessageBoxDefaultButton, MessageBoxOptions, String, String)</a></td><td>
Displays a message box with the specified text, caption, buttons, icon, default button, options, and Help button, using the specified Help file and Help keyword.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox_Show_9">Show(String, String, MessageBoxButtons, MessageBoxIcon, MessageBoxDefaultButton, MessageBoxOptions, String, HelpNavigator)</a></td><td>
Displays a message box with the specified text, caption, buttons, icon, default button, options, and Help button, using the specified Help file and HelpNavigator.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_DevMessageBox_Show_10">Show(String, String, MessageBoxButtons, MessageBoxIcon, MessageBoxDefaultButton, MessageBoxOptions, String, HelpNavigator, Object)</a></td><td>
Displays a message box with the specified text, caption, buttons, icon, default button, options, and Help button, using the specified Help file, HelpNavigator, and Help topic.</td></tr></table>&nbsp;
<a href="#devmessagebox-class">Back to Top</a>

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
<a href="#devmessagebox-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using msg As New DevMessageBox(owner:=Me, timeOut:=2500)

    msg.Show("Text", "Title", MessageBoxButtons.OK, MessageBoxIcon.Information)

End Using
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />