# NetworkTrafficMonitor Class
 

Monitorizes the traffic of a network interface.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.NET.NetworkTrafficMonitor<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_NET_ProcessTrafficMonitor">DevCase.Core.NET.ProcessTrafficMonitor</a><br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class NetworkTrafficMonitor : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public Class NetworkTrafficMonitor
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As NetworkTrafficMonitor
```

**C++**<br />
``` C++
public ref class NetworkTrafficMonitor : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
type NetworkTrafficMonitor =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The NetworkTrafficMonitor type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_NetworkTrafficMonitor__ctor">NetworkTrafficMonitor</a></td><td>
Initializes a new instance of the NetworkTrafficMonitor class.</td></tr></table>&nbsp;
<a href="#networktrafficmonitor-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_NetworkTrafficMonitor_InterfaceName">InterfaceName</a></td><td>
Gets the name of the network interface that is being monitored.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_NetworkTrafficMonitor_IsActive">IsActive</a></td><td>
Gets a value that indicates whether the traffic monitor is active.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_NetworkTrafficMonitor_UpdateBehavior">UpdateBehavior</a></td><td>
Gets or sets a value that controls the behavior of the <a href="E_DevCase_Core_NET_NetworkTrafficMonitor_TrafficChanged">TrafficChanged</a> event.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_NetworkTrafficMonitor_UpdateInterval">UpdateInterval</a></td><td>
Gets a value, in milliseconds, that determines when the monitor will update the traffic values.</td></tr></table>&nbsp;
<a href="#networktrafficmonitor-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_NetworkTrafficMonitor_Dispose">Dispose</a></td><td>
Releases all resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_NET_NetworkTrafficMonitor_GetAvailableInterfaceNames">GetAvailableInterfaceNames</a></td><td>
Gets the available network interface names.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_NetworkTrafficMonitor_GetBytesReceived">GetBytesReceived</a></td><td>
Gets the bytes received.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_NetworkTrafficMonitor_GetBytesSent">GetBytesSent</a></td><td>
Gets the bytes sent.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_NetworkTrafficMonitor_Start">Start</a></td><td>
Initializes the traffic monitoring.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_NetworkTrafficMonitor_Stop">Stop</a></td><td>
Finalizes the traffic monitoring.</td></tr></table>&nbsp;
<a href="#networktrafficmonitor-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_NET_NetworkTrafficMonitor_TrafficChanged">TrafficChanged</a></td><td>
Occurs when the network traffic has changed.</td></tr></table>&nbsp;
<a href="#networktrafficmonitor-class">Back to Top</a>

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
<a href="#networktrafficmonitor-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public NotInheritable Class Form1 : Inherits Form

    Friend WithEvents NetMon As NetworkTrafficMonitor

    Private Sub Form1_Shown() Handles MyBase.Shown
        Me.InitializeNetMon()
    End Sub

    Private Sub InitializeNetMon

        Try
            If Not NetworkTrafficMonitor.GetAvailableInterfaceNames.Any() Then
                Throw New Exception("Any available network interface found.")

            Else
                Me.NetMon = New NetworkTrafficMonitor(NetworkTrafficMonitor.GetAvailableInterfaceNames.First())
                Me.NetMon.UpdateBehavior = TrafficMonitorUpdateBehavior.FireAlwaysAfterTick
                Me.NetMon.UpdateInterval = 1000 ' 1 sec
                Me.NetMon.Start()

            End If

        Catch ex As Win32Exception When (ex.ErrorCode = -2147467259)
            MessageBox.Show("Cannot initialize network monitor. Ensure to enable performance counters service.", "",
                            MessageBoxButtons.OK, MessageBoxIcon.Error)

        Catch ex As Exception
            Throw

        End Try

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Handles the <see cref="NetworkTrafficMonitor.TrafficChanged"/> event of the <see cref="NetMon"/> instance.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="sender">
    ''' The source of the event.
    ''' </param>
    ''' 
    ''' <param name="e">
    ''' The <see cref="TrafficChangedEventArgs"/> instance containing the event data.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Private Sub NetMon_TrafficChanged(ByVal sender As Object, ByVal e As TrafficChangedEventArgs) _
    Handles netMon.TrafficChanged

        Me.LabelBytesReceived.Text = String.Format("Bytes received: {0} kb", (e.BytesReceived / 1024).ToString("n2"))
        Me.LabelDlSpeed.Text = String.Format("DL Speed: {0} kb/sec", (e.DiffBytesReceived / 1024).ToString("n2"))

        Me.LabelBytesSent.Text = String.Format("Bytes sent: {0} kb", (e.BytesSent / 1024).ToString("n2"))
        Me.LabelUlSpeed.Text = String.Format("UL Speed: {0} kb/sec", (e.DiffBytesSent / 1024).ToString("n2"))

    End Sub

    Private Sub BtDownloadUrl_Click() Handles BtDownloadUrl.Click

        Dim url As String = "http://download.thinkbroadband.com/10MB.zip"
        Dim client As New WebClient()
        client.DownloadFileAsync(New Uri(url), Path.GetTempFileName())

    End Sub

    Private Sub BtPauseMon_Click() Handles BtPauseMon.Click

        If Me.netMon.IsActive Then
            Me.netMon.Stop()
        Else
            Me.netMon.Start()
        End If

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />