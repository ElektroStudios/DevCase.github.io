# ProcessMonitor Class
 

A simple process monitor that notifies about started and stopped processes.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Diagnostics.ProcessMonitor<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class ProcessMonitor : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public Class ProcessMonitor
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessMonitor
```

**C++**<br />
``` C++
public ref class ProcessMonitor : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
type ProcessMonitor =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The ProcessMonitor type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_ProcessMonitor__ctor">ProcessMonitor</a></td><td>
Initializes a new instance of the ProcessMonitor class.</td></tr></table>&nbsp;
<a href="#processmonitor-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Diagnostics_ProcessMonitor_Interval">Interval</a></td><td>
Gets or sets the monitoring interval.</td></tr></table>&nbsp;
<a href="#processmonitor-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_ProcessMonitor_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_ProcessMonitor_Start">Start</a></td><td>
Starts monitoring.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_ProcessMonitor_Stop">Stop</a></td><td>
Stops monitoring.</td></tr></table>&nbsp;
<a href="#processmonitor-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Diagnostics_ProcessMonitor_ProcessStarted">ProcessStarted</a></td><td>
Occurs when a process starts.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Diagnostics_ProcessMonitor_ProcessStopped">ProcessStopped</a></td><td>
Occurs when a process stops.</td></tr></table>&nbsp;
<a href="#processmonitor-class">Back to Top</a>

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
<a href="#processmonitor-class">Back to Top</a>

## Remarks
In difference to <a href="T_DevCase_Core_Diagnostics_ProcessWatcher">ProcessWatcher</a>, this class is for scenarios on which responsivennes is a necessary requisite.

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    Dim WithEvents procMon As New ProcessMonitor With {.Interval = 100}

    Private Sub Form1_Load(ByVal sender As Object, ByVal e As EventArgs) _
    Handles Me.Load

        Me.procMon.Start()

    End Sub

    Private Sub Form1_FormClosing(ByVal sender As Object, ByVal e As FormClosingEventArgs) _
    Handles Me.FormClosing

        Me.procMon.Dispose()

    End Sub

    Private Sub ProcessMonitor_ProcessStarted(ByVal sender As Object, ByVal e As ProcessMonitor.ProcessMonitorEventArgs) _
    Handles procMon.ProcessStarted

        Dim p As Process = Process.GetProcessById(e.ProcessId)

        Console.WriteLine(String.Format("Process started | Name: {0}", e.ProcessName))
        Console.WriteLine(String.Format("Process started | PID : {0}", e.ProcessId))
        Console.WriteLine(String.Format("Process started | Path: {0}", p.MainModule.FileName))

    End Sub

    Private Sub ProcessMonitor_ProcessStopped(ByVal sender As Object, ByVal e As ProcessMonitor.ProcessMonitorEventArgs) _
    Handles procMon.ProcessStopped

        Console.WriteLine(String.Format("Process started | Name: {0}", e.ProcessName))
        Console.WriteLine(String.Format("Process started | PID : {0}", e.ProcessId))

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br />