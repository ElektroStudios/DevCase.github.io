# WMIEventWatcher Class
 

A WMI event monitor that notifies about event arrivals for the subscribed event class.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Management.ManagementEventWatcher<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.WMIEventWatcher<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class WMIEventWatcher : ManagementEventWatcher
```

**VB**<br />
``` VB
Public Class WMIEventWatcher
	Inherits ManagementEventWatcher
```

**VB Usage**<br />
``` VB Usage
Dim instance As WMIEventWatcher
```

**C++**<br />
``` C++
public ref class WMIEventWatcher : public ManagementEventWatcher
```

**F#**<br />
``` F#
type WMIEventWatcher =  
    class
        inherit ManagementEventWatcher
    end
```

The WMIEventWatcher type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_WMIEventWatcher__ctor">WMIEventWatcher(SelectQuery)</a></td><td>
Initializes a new instance of the WMIEventWatcher class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_WMIEventWatcher__ctor_4">WMIEventWatcher(String)</a></td><td>
Initializes a new instance of the WMIEventWatcher class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_WMIEventWatcher__ctor_1">WMIEventWatcher(SelectQuery, Single)</a></td><td>
Initializes a new instance of the WMIEventWatcher class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_WMIEventWatcher__ctor_2">WMIEventWatcher(SelectQuery, TimeSpan)</a></td><td>
Initializes a new instance of the WMIEventWatcher class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_WMIEventWatcher__ctor_3">WMIEventWatcher(SelectQuery, UInt32)</a></td><td>
Initializes a new instance of the WMIEventWatcher class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_WMIEventWatcher__ctor_5">WMIEventWatcher(String, Single)</a></td><td>
Initializes a new instance of the WMIEventWatcher class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_WMIEventWatcher__ctor_10">WMIEventWatcher(String, TimeSpan)</a></td><td>
Initializes a new instance of the WMIEventWatcher class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_WMIEventWatcher__ctor_6">WMIEventWatcher(String, String, Single)</a></td><td>
Initializes a new instance of the WMIEventWatcher class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_WMIEventWatcher__ctor_9">WMIEventWatcher(String, String, TimeSpan)</a></td><td>
Initializes a new instance of the WMIEventWatcher class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_WMIEventWatcher__ctor_7">WMIEventWatcher(String, String, String[], TimeSpan)</a></td><td>
Initializes a new instance of the WMIEventWatcher class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_WMIEventWatcher__ctor_8">WMIEventWatcher(String, String, String[], UInt32)</a></td><td>
Initializes a new instance of the WMIEventWatcher class.</td></tr></table>&nbsp;
<a href="#wmieventwatcher-class">Back to Top</a>

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
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Component_ComponentExtensions_GetEventHandlers">GetEventHandlers</a></td><td>
Gets all the delegates associated to the specified event raised by the source Component.
 (Defined by <a href="T_DevCase_Core_Extensions_Component_ComponentExtensions">ComponentExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#wmieventwatcher-class">Back to Top</a>

## Examples
This is a code example that demonstrates how to subscribe for drive mount/unmount events. 
**VB**<br />
``` VB
Imports System.Management

Public NotInheritable Class Form1 : Inherits Form

    Private WithEvents EventWatcher As New WMIEventWatcher("Win32_VolumeChangeEvent", withinInterval:=1)

    Private Sub Form1_Load(ByVal sender As Object, ByVal e As EventArgs) Handles Me.Load
        Dim connOptions As New ConnectionOptions With {
            .Impersonation = ImpersonationLevel.Impersonate,
            .EnablePrivileges = True
        }

        Dim scope As New ManagementScope(String.Format("\\{0}\ROOT\CIMV2", Environment.MachineName), connOptions)
        scope.Connect()

        Me.EventWatcher.Scope = scope
        Me.EventWatcher.Start()
    End Sub

    Private Sub Form1_FormClosing(ByVal sender As Object, ByVal e As FormClosingEventArgs) Handles Me.FormClosing
        Me.EventWatcher.Dispose()
    End Sub

    Private Sub EventWatcher_EventArrived(ByVal sender As Object, ByVal e As EventArrivedEventArgs) _
    Handles EventWatcher.EventArrived

        Dim driveName As String = CStr(e.NewEvent.Properties("DriveName").Value)
        Dim eventType As Integer = CInt(e.NewEvent.Properties("EventType").Value)

        Console.WriteLine(String.Format("Drive Name: {0}", driveName))
        Console.WriteLine(String.Format("Event Type: {0}", eventType))

    End Sub

End Class
```


## Examples
This is a code example that demonstrates how to subscribe for CD-ROM insertion/ejecton events. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    Private WithEvents EventWatcher As New WMIEventWatcher(
        "__InstanceModificationEvent",
        condition:="TargetInstance ISA 'Win32_LogicalDisk' and TargetInstance.DriveType = 5",
        withinInterval:=1
    )

    Private Sub Form1_Load(ByVal sender As Object, ByVal e As EventArgs) Handles Me.Load

        Dim connOptions As New ConnectionOptions With {
            .Impersonation = ImpersonationLevel.Impersonate,
            .EnablePrivileges = True
        }

        Dim scope As New ManagementScope(String.Format("\\{0}\ROOT\CIMV2", Environment.MachineName), connOptions)
        scope.Connect()

        Me.EventWatcher.Scope = scope
        Me.EventWatcher.Start()

    End Sub

    Private Sub Form1_FormClosing(ByVal sender As Object, ByVal e As FormClosingEventArgs) Handles Me.FormClosing

        Me.EventWatcher.Dispose()

    End Sub

    Private Sub EventWatcher_EventArrived(ByVal sender As Object, ByVal e As EventArrivedEventArgs) Handles EventWatcher.EventArrived

        Using mo As ManagementBaseObject = e.NewEvent

            Dim name As String = Convert.ToString(mo.Properties("Name").Value)
            ' Dim name As String = Convert.ToString(mo.Properties("VolumeName").Value)

            Dim di As DriveInfo = (From item In DriveInfo.GetDrives()
                                   Where String.IsNullOrEmpty(item.Name)
                                  ).Single()

            If Not String.IsNullOrEmpty(di.VolumeLabel) Then
                Console.WriteLine(String.Format("CD-ROM tray inserted in drive {0}.", di.Name))

            Else
                Console.WriteLine(String.Format("CD-ROM tray ejected in drive {0}.", di.Name))

            End If

        End Using

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />