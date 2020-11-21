# Hotkey Class
 

Creates a system-wide hotkey for the current application.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.NativeWindow<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticNativeWindow">DevCase.Core.Design.AestheticNativeWindow</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.Hotkey<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class Hotkey : AestheticNativeWindow, IDisposable
```

**VB**<br />
``` VB
Public Class Hotkey
	Inherits AestheticNativeWindow
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As Hotkey
```

**C++**<br />
``` C++
public ref class Hotkey : public AestheticNativeWindow, 
	IDisposable
```

**F#**<br />
``` F#
type Hotkey =  
    class
        inherit AestheticNativeWindow
        interface IDisposable
    end
```

The Hotkey type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Hotkey__ctor">Hotkey</a></td><td>
Initializes a new instance of the Hotkey class.</td></tr></table>&nbsp;
<a href="#hotkey-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Hotkey_Count">Count</a></td><td>
Gets a value that specifies how many times was pressed the registered hotkey.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Hotkey_Handle">Handle</a></td><td>
Gets the handle for the window that owns this Hotkey instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Hotkey_Id">Id</a></td><td>
Gets the unique identifier assigned to the hotkey.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Hotkey_Key">Key</a></td><td>
Gets the key assigned to the hotkey.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Hotkey_Modifier">Modifier</a></td><td>
Gets the key-modifiers assigned to the hotkey.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Hotkey_Tag">Tag</a></td><td>
Gets or sets an user-defined data associated with this object.</td></tr></table>&nbsp;
<a href="#hotkey-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Hotkey_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Hotkey_IsRegistered">IsRegistered</a></td><td>
Determines whether this hotkey is registered on the system.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Hotkey_Register">Register</a></td><td>
Registers this hotkey on the system.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Hotkey_Unregister">Unregister</a></td><td>
Unregisters this hotkey from the system. So after calling this method the hotkey turns unavailable. 

 Note that the hotkey can be re-registered at any time calling the <a href="M_DevCase_Core_Application_Hotkey_Register">Register()</a> method.</td></tr></table>&nbsp;
<a href="#hotkey-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Application_Hotkey_Press">Press</a></td><td>
Occurs when the hotkey is pressed.</td></tr></table>&nbsp;
<a href="#hotkey-class">Back to Top</a>

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
<a href="#hotkey-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    Private WithEvents hotkey As Hotkey

    Public Sub Test() Handles MyBase.Shown

        MyClass.InitializeComponent()

        ' Registers a new global hotkey on the system. (Alt + Ctrl + A) 
        hotkey = New Hotkey(HotkeyModifiers.Alt Or HotkeyModifiers.Control, Keys.A)

        ' Replaces the current registered hotkey with a new one. (Alt + Escape)
        hotkey = New Hotkey(DirectCast([Enum].Parse(GetType(HotkeyModifiers), "Alt", True), HotkeyModifiers),
                            DirectCast([Enum].Parse(GetType(Keys), "Escape", True), Keys))

        ' Set the tag property.
        hotkey.Tag = "I'm a String tag"

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Handles the <see cref="HotKey.Press"/> event of the HotKey control.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="sender">
    ''' The source of the event.
    ''' </param>
    ''' 
    ''' <param name="e">
    ''' The <see cref="HotkeyPressEventArgs"/> instance containing the event data.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Private Sub HotKey_Press(ByVal sender As Object, ByVal e As HotkeyPressEventArgs) _
    Handles hotkey.Press

        Dim sb As New Global.System.Text.StringBuilder
        With sb
            .AppendLine(String.Format("Key.......: {0}", e.Key.ToString()))
            .AppendLine(String.Format("Modifiers.: {0}", e.Modifiers.ToString()))
            .AppendLine(String.Format("Identifier: {0}", e.Id))
            .AppendLine(String.Format("Press-count: {0}", DirectCast(sender, Hotkey).Count))
            .AppendLine(String.Format("Tag: {0}", DirectCast(sender, Hotkey).Tag.ToString()))
        End With

        MessageBox.Show(sb.ToString(), String.Empty, MessageBoxButtons.OK, MessageBoxIcon.Information)

        ' Unregister the hotkey.
        Me.hotkey.Unregister()

        ' Is Registered?
        Debug.WriteLine(Me.hotkey.IsRegistered)

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />