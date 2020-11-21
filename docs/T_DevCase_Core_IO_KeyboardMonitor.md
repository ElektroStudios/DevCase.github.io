# KeyboardMonitor Class
 

Handles the raw input from keyboard devices.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.NativeWindow<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticNativeWindow">DevCase.Core.Design.AestheticNativeWindow</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.KeyboardMonitor<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class KeyboardMonitor : AestheticNativeWindow, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class KeyboardMonitor
	Inherits AestheticNativeWindow
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardMonitor
```

**C++**<br />
``` C++
public ref class KeyboardMonitor sealed : public AestheticNativeWindow, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type KeyboardMonitor =  
    class
        inherit AestheticNativeWindow
        interface IDisposable
    end
```

The KeyboardMonitor type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_KeyboardMonitor__ctor">KeyboardMonitor</a></td><td>
Initializes a new instance of the KeyboardMonitor class. 

 Caling this constructor causes to registers the raw input devices for the calling window.</td></tr></table>&nbsp;
<a href="#keyboardmonitor-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_KeyboardMonitor_DeviceCount">DeviceCount</a></td><td>
Gets the amount of keyboard devices.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_KeyboardMonitor_Enabled">Enabled</a></td><td>
Gets or sets a value that determines whether the keylogger is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_KeyboardMonitor_Handle">Handle</a></td><td>
Gets the handle for the window that owns this KeyboardMonitor instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_KeyboardMonitor_HandlePastes">HandlePastes</a></td><td>
Gets or sets a value that determines whether a paste operation (Ctrl+V) should be handled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_KeyboardMonitor_IgnoredChars">IgnoredChars</a></td><td>
Gets or sets a collection of Char to ignore from raising the <a href="E_DevCase_Core_IO_KeyboardMonitor_KeyPressed">KeyPressed</a> event.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_KeyboardMonitor_IgnoredCharsComparer">IgnoredCharsComparer</a></td><td>
Gets or sets the comparison behavior for <a href="P_DevCase_Core_IO_KeyboardMonitor_IgnoredChars">IgnoredChars</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_KeyboardMonitor_IgnoredKeys">IgnoredKeys</a></td><td>
Gets or sets a collection of Keys to ignore from raising the <a href="E_DevCase_Core_IO_KeyboardMonitor_KeyPressed">KeyPressed</a> event.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_KeyboardMonitor_IgnoredStrings">IgnoredStrings</a></td><td>
Gets or sets a collection of String to ignore from raising the <a href="E_DevCase_Core_IO_KeyboardMonitor_KeyPressed">KeyPressed</a> event.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_KeyboardMonitor_IgnoredStringsComparer">IgnoredStringsComparer</a></td><td>
Gets or sets the comparison behavior for <a href="P_DevCase_Core_IO_KeyboardMonitor_IgnoredStrings">IgnoredStrings</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_KeyboardMonitor_KeyboardLayoutHandle">KeyboardLayoutHandle</a></td><td>
Gets the keyboard layout handle (HKL).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_KeyboardMonitor_KeyboardLayoutID">KeyboardLayoutID</a></td><td>
Gets the keyboard layout Identifier.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_KeyboardMonitor_Language">Language</a></td><td>
Gets or sets the keyboard language.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_KeyboardMonitor_OwnerWindow">OwnerWindow</a></td><td>
Gets the window that owns this KeyboardMonitor instance.</td></tr></table>&nbsp;
<a href="#keyboardmonitor-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_KeyboardMonitor_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#keyboardmonitor-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_KeyboardMonitor_HotkeyPastePressed">HotkeyPastePressed</a></td><td>
Occurs when a paste hotkey is pressed (`Ctrl`+`V`).</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_KeyboardMonitor_KeyPressed">KeyPressed</a></td><td>
Occurs when a key is pressed.</td></tr></table>&nbsp;
<a href="#keyboardmonitor-class">Back to Top</a>

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
<a href="#keyboardmonitor-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public NotInheritable Class Form1 : Inherits Form

    Friend WithEvents KeyLogger As New KeyboardMonitor(Me)

    Public Sub New()

        Me.InitializeComponent()

        ' Set keyboard layout to the default culture, in my case 'es-ES'.
        Me.KeyLogger.Language = InputLanguage.DefaultInputLanguage.Culture.Name

        ' Handle text pasting operations (Ctrl+V).
        Me.KeyLogger.HandlePastes = True

        ' Avoid raising KeyPressed event for non-relevant keys for this app example: 
        ' Left/Right Shift, Alt, AltGr, CapsLock, NumLock, and Left/Right Win key.
        Me.KeyLogger.IgnoredKeys = {Keys.ShiftKey, Keys.Menu, Keys.CapsLock, Keys.NumLock, Keys.LWin, Keys.RWin}

        ' Me.keyLogger.IgnoredChars = {"^"c}
        ' Me.keyLogger.IgnoredCharsComparer = EqualityComparer(Of Char).Default

        ' Me.keyLogger.IgnoredStrings = {"^^"}
        ' Me.keyLogger.IgnoredStringsComparer = StringComparer.OrdinalIgnoreCase

        ' Enable the keylogger.
        Me.KeyLogger.Enabled = True 

    End Sub

    Private Sub KeyLogger_KeyPressed(ByVal sender As Object, ByVal e As KeyPressedEventArgs) _
    Handles KeyLogger.KeyPressed

        Me.Label1.Text = String.Format("Device Handle: {0}", e.DeviceInfo.Handle.ToString())
        Me.Label2.Text = String.Format("Device Type: {0}", e.DeviceInfo.Type)
        Me.Label3.Text = String.Format("Device Name: {0}", e.DeviceInfo.Name.Replace("&", "&&"))
        Me.Label4.Text = String.Format("Device Description: {0}", e.DeviceInfo.Description)
        Me.Label5.Text = String.Format("Device Key:WinForms.Keys.{0}", e.DeviceInfo.Key.ToString())
        Me.Label6.Text = String.Format("Devices Count: {0}", Me.KeyLogger.DeviceCount.ToString())

        Select Case e.DeviceInfo.Key

            Case Keys.Enter
                e.DeviceInfo.Chars = ControlChars.CrLf & "{ENTER}"

            Case Keys.Back
                e.DeviceInfo.Chars = "{BACKSPACE}"

            Case Keys.ControlKey
                e.DeviceInfo.Chars = "{CTRL}"

            Case Else
                ' ...

        End Select

        Me.TextBox1.Text = e.DeviceInfo.Chars
        Me.TextBox2.AppendText(e.DeviceInfo.Chars)

    End Sub

    Private Sub KeyLogger_HotkeyPastePressed(ByVal sender As Object, ByVal e As HotkeyPastePressedEventArgs) _
    Handles KeyLogger.HotkeyPastePressed

        Me.TextBox2.AppendText("{INIT_PASTE}" & e.ClipboardData & "{END_PASTE}")

    End Sub

    Private Sub Button_Clean_Click(sender As Object, e As EventArgs) _
    Handles Button1.Click

        Me.TextBox2.Clear()

    End Sub

    Private Sub Button_Dispose_Click(ByVal sender As Object, ByVal e As EventArgs) _
    Handles Button2.Click

        If Me.KeyLogger IsNot Nothing Then
            Me.KeyLogger.Dispose()
        End If

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />