# PowerStateMonitor Class
 

Monitors the system and battery power-state activity. 

 Suscribe to the events exposed by this class to be notifies about power-state changes.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.PowerStateMonitor<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class PowerStateMonitor : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public Class PowerStateMonitor
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As PowerStateMonitor
```

**C++**<br />
``` C++
public ref class PowerStateMonitor : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
type PowerStateMonitor =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The PowerStateMonitor type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Shell_PowerStateMonitor__ctor">PowerStateMonitor</a></td><td>
Initializes a new instance of the PowerStateMonitor class.</td></tr></table>&nbsp;
<a href="#powerstatemonitor-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Shell_PowerStateMonitor_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Shell_PowerStateMonitor_Start">Start</a></td><td>
Starts the monitor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Shell_PowerStateMonitor_Stop">Stop</a></td><td>
Stops the monitor.</td></tr></table>&nbsp;
<a href="#powerstatemonitor-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Shell_PowerStateMonitor_BatteryStatusChanged">BatteryStatusChanged</a></td><td>
Occurs when the battery status changed.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Shell_PowerStateMonitor_SuspendInitiated">SuspendInitiated</a></td><td>
Occurs when the system is about to enter in Suspend state.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_Shell_PowerStateMonitor_SuspendResumed">SuspendResumed</a></td><td>
Occurs when the system is about to resume from Suspend state.</td></tr></table>&nbsp;
<a href="#powerstatemonitor-class">Back to Top</a>

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
<a href="#powerstatemonitor-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Friend WithEvents PowerStateMon As New PowerStateMonitor

Sub Test() Handles Me.Shown

    Me.PowerStateMon.Start()

End Sub

Private Sub PowerStateMon_SuspendInitiated(ByVal sender As Object, ByVal e As EventArgs) _
Handles PowerStateMon.SuspendInitiated

    Process.Start("CMD.exe", "/K Echo %TIME% The system is entering in Suspend state.")

End Sub

Private Sub PowerStateMon_SuspendResumed(ByVal sender As Object, ByVal e As EventArgs) _
Handles PowerStateMon.SuspendResumed

    Process.Start("CMD.exe", "/K Echo %TIME% The system resumed from Suspend state.")

End Sub

Private Sub PowerStateMon_BatteryStatusChanged(ByVal sender As Object, ByVal e As BatteryStatusChangedEventArgs) _
Handles PowerStateMon.BatteryStatusChanged

    Select Case e.BatteryChargeStatus

        Case BatteryChargeStatus.Low
            MessageBox.Show("Battery is running low.", "Low Battery", MessageBoxButtons.OK,  MessageBoxIcon.Exclamation)

        Case BatteryChargeStatus.Critical
            MessageBox.Show("Battery is critically low.", "Critical Battery", MessageBoxButtons.OK, MessageBoxIcon.Stop)

        Case Else
            ' Battery is okay.
            Exit Select

    End Select

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />