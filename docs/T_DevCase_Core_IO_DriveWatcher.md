# DriveWatcher Class
 

A device insertion and removal monitor.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.NativeWindow<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticNativeWindow">DevCase.Core.Design.AestheticNativeWindow</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.DriveWatcher<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class DriveWatcher : AestheticNativeWindow, 
	IDisposable
```

**VB**<br />
``` VB
Public Class DriveWatcher
	Inherits AestheticNativeWindow
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveWatcher
```

**C++**<br />
``` C++
public ref class DriveWatcher : public AestheticNativeWindow, 
	IDisposable
```

**F#**<br />
``` F#
type DriveWatcher =  
    class
        inherit AestheticNativeWindow
        interface IDisposable
    end
```

The DriveWatcher type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_DriveWatcher__ctor">DriveWatcher</a></td><td>
Initializes a new instance of DriveWatcher class.</td></tr></table>&nbsp;
<a href="#drivewatcher-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_DriveWatcher_Drives">Drives</a></td><td>
Gets the connected drives on this computer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_DriveWatcher_Handle">Handle</a></td><td>
Gets the handle for the NativeWindow that owns this DriveWatcher instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_DriveWatcher_IsRunning">IsRunning</a></td><td>
Gets a value that determines whether the monitor is running.</td></tr></table>&nbsp;
<a href="#drivewatcher-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_DriveWatcher_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_DriveWatcher_Start">Start</a></td><td>
Starts monitoring.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_DriveWatcher_Stop">Stop</a></td><td>
Stops monitoring.</td></tr></table>&nbsp;
<a href="#drivewatcher-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_DriveWatcher_DriveStatusChanged">DriveStatusChanged</a></td><td>
Occurs when a drive is inserted, removed, or changed.</td></tr></table>&nbsp;
<a href="#drivewatcher-class">Back to Top</a>

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
<a href="#drivewatcher-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Friend WithEvents DriveMon As New DriveWatcher

''' <summary>
''' Handles the <see cref="DriveWatcher.DriveStatusChanged"/> event of the <see cref="DriveMon"/> instance.
''' </summary>
Private Sub DriveMon_DriveStatusChanged(ByVal sender As Object, ByVal e As DriveStatusChangedEventArgs) _
Handles DriveMon.DriveStatusChanged

    Select Case e.DeviceEvent

        Case DevCase.Interop.Unmanaged.Win32.DeviceEvents.Arrival
            Dim sb As New Global.System.Text.StringBuilder
            sb.AppendLine("New drive connected...'")
            sb.AppendLine(String.Format("Type......: {0}", e.DriveInfo.DriveType.ToString()))
            sb.AppendLine(String.Format("Label.....: {0}", e.DriveInfo.VolumeLabel))
            sb.AppendLine(String.Format("Name......: {0}", e.DriveInfo.Name))
            sb.AppendLine(String.Format("Root......: {0}", e.DriveInfo.RootDirectory))
            sb.AppendLine(String.Format("FileSystem: {0}", e.DriveInfo.DriveFormat))
            sb.AppendLine(String.Format("Size......: {0} GB", (e.DriveInfo.TotalSize / (1024 ^ 3)).ToString("n1")))
            sb.AppendLine(String.Format("Free space: {0} GB", (e.DriveInfo.AvailableFreeSpace / (1024 ^ 3)).ToString("n1")))
            Console.WriteLine(sb.ToString())

        Case DevCase.Interop.Unmanaged.Win32.DeviceEvents.RemoveComplete
            Dim sb As New Global.System.Text.StringBuilder
            sb.AppendLine("Drive disconnected...'")
            sb.AppendLine(String.Format("Name: {0}", e.DriveInfo.Name))
            sb.AppendLine(String.Format("Root: {0}", e.DriveInfo.RootDirectory))
            Console.WriteLine(sb.ToString())

    End Select

End Sub

Private Sub StartMon_Click(ByVal sender As Object, ByVal e As EventArgs) _
Handles Button_StartMon.Click

    Me.DriveMon.Start()

End Sub

Private Sub StopMon_Click(ByVal sender As Object, ByVal e As EventArgs) _
Handles Button_StopMon.Click

    Me.DriveMon.Stop()

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />