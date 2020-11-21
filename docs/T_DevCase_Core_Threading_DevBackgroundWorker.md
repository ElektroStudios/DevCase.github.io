# DevBackgroundWorker Class
 

A extended BackgroundWorker component with synchronous (blocking) run/cancellation support, and asynchronous pause/resume features.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.BackgroundWorker<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Threading.DevBackgroundWorker<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Threading">DevCase.Core.Threading</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ToolboxBitmapAttribute(typeof(Component), "Component.bmp")]
[DefaultEventAttribute("DoWork")]
public class DevBackgroundWorker : BackgroundWorker
```

**VB**<br />
``` VB
<ToolboxBitmapAttribute(GetType(Component), "Component.bmp")>
<DefaultEventAttribute("DoWork")>
Public Class DevBackgroundWorker
	Inherits BackgroundWorker
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevBackgroundWorker
```

**C++**<br />
``` C++
[ToolboxBitmapAttribute(typeof(Component), L"Component.bmp")]
[DefaultEventAttribute(L"DoWork")]
public ref class DevBackgroundWorker : public BackgroundWorker
```

**F#**<br />
``` F#
[<ToolboxBitmapAttribute(typeof(Component), "Component.bmp")>]
[<DefaultEventAttribute("DoWork")>]
type DevBackgroundWorker =  
    class
        inherit BackgroundWorker
    end
```

The DevBackgroundWorker type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Threading_DevBackgroundWorker__ctor">DevBackgroundWorker</a></td><td>
Initializes a new instance of the DevBackgroundWorker class.</td></tr></table>&nbsp;
<a href="#devbackgroundworker-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Threading_DevBackgroundWorker_Cancel">Cancel</a></td><td>
Requests cancellation of a pending background operation. 

 It blocks the caller thread until the remaining background work is canceled.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Threading_DevBackgroundWorker_CancelAsync">CancelAsync</a></td><td>
Asynchronously requests cancellation of a pending background operation.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Threading_DevBackgroundWorker_Pause">Pause</a></td><td>
Pause a pending background operation. 

 It blocks the caller thread until the background work is resumed. To resume the background work, call the <a href="M_DevCase_Core_Threading_DevBackgroundWorker_Resume">Resume()</a> method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Threading_DevBackgroundWorker_RequestPause">RequestPause</a></td><td>
Asynchronously requests to pause a pending background operation. 

 To pause the background work after requesting a pause, call the <a href="M_DevCase_Core_Threading_DevBackgroundWorker_Pause">Pause()</a> method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Threading_DevBackgroundWorker_Resume">Resume</a></td><td>
Resume a pending paused background operation.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Threading_DevBackgroundWorker_Run">Run</a></td><td>
Starts execution of a background operation. 

 It blocks the caller thread until the background work is done.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Threading_DevBackgroundWorker_RunAsync">RunAsync</a></td><td>
Asynchronously starts execution of a background operation.</td></tr></table>&nbsp;
<a href="#devbackgroundworker-class">Back to Top</a>

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
<a href="#devbackgroundworker-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Friend WithEvents Worker As DevBackgroundWorker

Private Sub Button_Run_Click() Handles Button_Run.Click

    If (Me.Worker IsNot Nothing) Then

        Select Case Me.Worker.State
            Case DevBackgroundWorkerState.Running, DevBackgroundWorkerState.Paused
                Me.Worker.Cancel()
            Case Else
                ' Do Nothing.
        End Select

    End If

    Me.Worker = New DevBackgroundWorker
    Me.Worker.RunAsync()

End Sub

Private Sub Button_Pause_Click() Handles Button_Pause.Click
    Me.Worker.RequestPause()
End Sub

Private Sub Button_Resume_Click() Handles Button_Resume.Click
    Me.Worker.Resume()
End Sub

Private Sub Button_Cancel_Click() Handles Button_Cancel.Click
    Me.Worker.Cancel()
End Sub

''' ----------------------------------------------------------------------------------------------------
''' <summary>
''' Handles the <see cref="DevBackgroundWorker.DoWork"/> event of the <see cref="Worker"/> instance.
''' </summary>
''' ----------------------------------------------------------------------------------------------------
''' <param name="sender">
''' The source of the event.
''' </param>
''' 
''' <param name="e">
''' The <see cref="DoWorkEventArgs"/> instance containing the event data.
''' </param>
''' ----------------------------------------------------------------------------------------------------
<DebuggerStepperBoundary>
Private Sub Worker_DoWork(ByVal sender As Object, ByVal e As DoWorkEventArgs) _
Handles Worker.DoWork

    Dim progress As Integer

    Dim lock As Object = ""
    SyncLock lock

        For i As Integer = 0 To 100
            If (Me.Worker.CancellationPending) Then ' Cancel the background operation.
                e.Cancel = True
                Exit For

            Else
                If (Me.Worker.PausePending) Then ' Pause the background operation.
                    Me.Worker.Pause() ' Blocking pause call.
                End If

                Me.DoSomething()

                If Me.Worker.WorkerReportsProgress Then
                    progress = i
                    Me.Worker.ReportProgress(progress)
                End If

            End If

        Next i

    End SyncLock

    If (Me.Worker.WorkerReportsProgress) AndAlso Not (Me.Worker.CancellationPending) AndAlso (progress < 100) Then
        Me.Worker.ReportProgress(percentProgress:=100)
    End If

End Sub

''' ----------------------------------------------------------------------------------------------------
''' <summary>
''' Handles the <see cref="DevBackgroundWorker.ProgressChanged"/> event of the <see cref="Worker"/> instance.
''' </summary>
''' ----------------------------------------------------------------------------------------------------
''' <param name="sender">
''' The source of the event.
''' </param>
''' 
''' <param name="e">
''' The <see cref="ProgressChangedEventArgs"/> instance containing the event data.
''' </param>
''' ----------------------------------------------------------------------------------------------------
<DebuggerStepperBoundary>
Private Sub Worker_ProgressChanged(ByVal sender As Object, ByVal e As ProgressChangedEventArgs) _
Handles Worker.ProgressChanged

    Console.WriteLine(String.Format("Background Work Progress: {00}%", e.ProgressPercentage))

End Sub

''' ----------------------------------------------------------------------------------------------------
''' <summary>
''' Handles the <see cref="DevBackgroundWorker.RunWorkerCompleted"/> event of the <see cref="Worker"/> instance.
''' </summary>
''' ----------------------------------------------------------------------------------------------------
''' <param name="sender">
''' The source of the event.
''' </param>
''' 
''' <param name="e">
''' The <see cref="RunWorkerCompletedEventArgs"/> instance containing the event data.
''' </param>
''' ----------------------------------------------------------------------------------------------------
<DebuggerStepperBoundary>
Private Sub Worker_RunWorkerCompleted(ByVal sender As Object, ByVal e As RunWorkerCompletedEventArgs) _
Handles Worker.RunWorkerCompleted

    If (e.Cancelled) Then
        Debug.WriteLine("Background work cancelled.")

    ElseIf (e.Error IsNot Nothing) Then
        Debug.WriteLine("Background work error.")

    Else
        Debug.WriteLine("Background work done.")

    End If

    Console.WriteLine(String.Format("State: {0}", Me.Worker.State.ToString()))

End Sub

<DebuggerStepperBoundary>
Private Sub DoSomething()
    Thread.Sleep(TimeSpan.FromSeconds(1))
End Sub
```


## See Also


#### Reference
<a href="N_DevCase_Core_Threading">DevCase.Core.Threading Namespace</a><br />System.ComponentModel.BackgroundWorker<br />