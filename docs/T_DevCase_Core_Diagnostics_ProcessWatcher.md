# ProcessWatcher Class
 

A simple process monitor that notifies about started and stopped processes.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Diagnostics.ProcessWatcher<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class ProcessWatcher : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public Class ProcessWatcher
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessWatcher
```

**C++**<br />
``` C++
public ref class ProcessWatcher : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
type ProcessWatcher =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The ProcessWatcher type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_ProcessWatcher__ctor">ProcessWatcher</a></td><td>
Initializes a new instance of the ProcessWatcher class.</td></tr></table>&nbsp;
<a href="#processwatcher-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_ProcessWatcher_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_ProcessWatcher_Start">Start</a></td><td>
Start monitoring for process starts and stops.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_ProcessWatcher_Stop">Stop</a></td><td>
Stop monitoring for process starts and stops.</td></tr></table>&nbsp;
<a href="#processwatcher-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Diagnostics_ProcessWatcher_ProcessStarted">ProcessStarted</a></td><td>
Occurs when a process starts (run).</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Diagnostics_ProcessWatcher_ProcessStopped">ProcessStopped</a></td><td>
Occurs when a process stops (exit).</td></tr></table>&nbsp;
<a href="#processwatcher-class">Back to Top</a>

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
<a href="#processwatcher-class">Back to Top</a>

## Remarks
In difference to <a href="T_DevCase_Core_Diagnostics_ProcessMonitor">ProcessMonitor</a>, this class is for scenarios on which responsivennes is not an important requisite.

## Examples
This is a code example. 
**VB**<br />
``` VB
Imports System.Management

Public Class Form1 : Inherits Form

    Private WithEvents processWatcher As New ProcessWatcher

    Private Sub Form1_Load(ByVal sender As Object, ByVal e As EventArgs) _
    Handles Me.Load

        Me.processWatcher.Start()

    End Sub

    Private Sub Form1_FormClosing(ByVal sender As Object, ByVal e As FormClosingEventArgs) _
    Handles Me.FormClosing

        Me.processWatcher.Dispose()

    End Sub

    Private Sub ProcessWatcher_ProcessStarted(ByVal sender As Object, ByVal e As EventArrivedEventArgs) _
    Handles processWatcher.ProcessStarted

        Dim name As String = CStr(e.NewEvent.Properties("ProcessName").Value)
        Dim pid As Integer = CInt(e.NewEvent.Properties("ProcessId").Value)
        Dim path As String = String.Empty

        Dim connOptions As New ConnectionOptions With {
            .Impersonation = ImpersonationLevel.Impersonate,
            .EnablePrivileges = True
        }

        Dim scope As New ManagementScope(String.Format("\\{0}\ROOT\CIMV2", Environment.MachineName), connOptions)
        scope.Connect()

        Dim query As New SelectQuery(String.Format("SELECT * FROM Win32_Process WHERE ProcessId={0}", pid))
        Dim enumOptions As New EnumerationOptions With {.ReturnImmediately = True}

        Using mos As New ManagementObjectSearcher(scope, query, enumOptions),
              moc As ManagementObjectCollection = mos.Get(),
              mo As ManagementObject = DirectCast(moc(0), ManagementObject)

           path = CStr(mo.Properties("ExecutablePath").Value)
        End Using

        Console.WriteLine(String.Format("Process started | Name: {0}", name))
        Console.WriteLine(String.Format("Process started | PID : {0}", pid))
        Console.WriteLine(String.Format("Process started | Path: {0}", path))

    End Sub

    Private Sub ProcessWatcher_ProcessStopped(ByVal sender As Object, ByVal e As EventArrivedEventArgs) _
    Handles processWatcher.ProcessStopped

        Dim name As String = e.NewEvent.Properties("ProcessName").Value.ToString()

        Console.WriteLine(String.Format("Process stopped | Name: {0}", name))

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br />