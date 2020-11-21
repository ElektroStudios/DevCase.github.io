# ProcessTrafficMonitor Class
 

Monitorizes the network traffic of a process.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_NET_NetworkTrafficMonitor">DevCase.Core.NET.NetworkTrafficMonitor</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.NET.ProcessTrafficMonitor<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class ProcessTrafficMonitor : NetworkTrafficMonitor
```

**VB**<br />
``` VB
Public Class ProcessTrafficMonitor
	Inherits NetworkTrafficMonitor
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessTrafficMonitor
```

**C++**<br />
``` C++
public ref class ProcessTrafficMonitor : public NetworkTrafficMonitor
```

**F#**<br />
``` F#
type ProcessTrafficMonitor =  
    class
        inherit NetworkTrafficMonitor
    end
```

The ProcessTrafficMonitor type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_ProcessTrafficMonitor__ctor">ProcessTrafficMonitor</a></td><td>
Initializes a new instance of the ProcessTrafficMonitor class.</td></tr></table>&nbsp;
<a href="#processtrafficmonitor-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_ProcessTrafficMonitor_ProcessId">ProcessId</a></td><td>
Gets the name of the process that is being monitored.</td></tr></table>&nbsp;
<a href="#processtrafficmonitor-class">Back to Top</a>

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
<a href="#processtrafficmonitor-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public NotInheritable Class Form1 : Inherits Form

    Friend WithEvents ProcNetMon As ProcessTrafficMonitor

    Private Sub Form1_Shown() Handles MyBase.Shown
        Me.InitializeNetMon()
    End Sub

    Private Sub InitializeNetMon

        Try
           Me.ProcNetMon = New ProcessTrafficMonitor(Process.GetCurrentProcess.Id)
           Me.ProcNetMon.UpdateBehavior = TrafficMonitorUpdateBehavior.FireAlwaysAfterTick
           Me.ProcNetMon.UpdateInterval = 1000 ' 1 sec
           Me.ProcNetMon.Start()

        Catch ex As Win32Exception When (ex.ErrorCode = -2147467259)
            MessageBox.Show("Cannot initialize network monitor. Ensure to enable performance counters service.", "",
                            MessageBoxButtons.OK, MessageBoxIcon.Error)

        Catch ex As Exception
            Throw

        End Try

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Handles the <see cref="ProcessTrafficMonitor.TrafficChanged"/> event of the <see cref="ProcNetMon"/> instance.
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
    Private Sub ProcNetMon_TrafficChanged(ByVal sender As Object, ByVal e As TrafficChangedEventArgs) _
    Handles procNetMon.TrafficChanged

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

        If Me.ProcNetMon.IsActive Then
            Me.ProcNetMon.Stop()
        Else
            Me.ProcNetMon.Start()
        End If

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />