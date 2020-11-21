# TimeMeasurer Class
 

Measures the elapsed and/or remaining time of a time interval. The time measurer can be used as a chronometer or a countdown.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.DateAndTime.TimeMeasurer<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_DateAndTime">DevCase.Core.DateAndTime</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class TimeMeasurer : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class TimeMeasurer
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As TimeMeasurer
```

**C++**<br />
``` C++
public ref class TimeMeasurer sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type TimeMeasurer =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The TimeMeasurer type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_DateAndTime_TimeMeasurer__ctor">TimeMeasurer</a></td><td>
Initializes a new instance of the TimeMeasurer class.</td></tr></table>&nbsp;
<a href="#timemeasurer-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_DateAndTime_TimeMeasurer_MaxValue">MaxValue</a></td><td>
Gets the maximum time that the TimeMeasurer can measure, in milliseconds.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_DateAndTime_TimeMeasurer_State">State</a></td><td>
Gets the current state of this TimeMeasurer instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_DateAndTime_TimeMeasurer_UpdateInterval">UpdateInterval</a></td><td>
Gets or sets the update interval. Maximum value is 1000 (1 second).</td></tr></table>&nbsp;
<a href="#timemeasurer-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_DateAndTime_TimeMeasurer_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_DateAndTime_TimeMeasurer_Pause">Pause</a></td><td>
Pauses the time interval measurement.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_DateAndTime_TimeMeasurer_Resume">Resume</a></td><td>
Resumes the time interval measurement.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_DateAndTime_TimeMeasurer_Start_1">Start(Double)</a></td><td>
Starts the time interval measurement.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_DateAndTime_TimeMeasurer_Start_2">Start(TimeSpan)</a></td><td>
Starts a time interval measurement given a TimeSpan.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_DateAndTime_TimeMeasurer_Start">Start(DateTime, DateTime)</a></td><td>
Starts a time interval measurement given a difference between two dates.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_DateAndTime_TimeMeasurer_Stop">Stop</a></td><td>
Stops the time interval measurement.</td></tr></table>&nbsp;
<a href="#timemeasurer-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_DateAndTime_TimeMeasurer_TimeUpdated">TimeUpdated</a></td><td>
Occurs when the elapsed/remaining time updates.</td></tr></table>&nbsp;
<a href="#timemeasurer-class">Back to Top</a>

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
<a href="#timemeasurer-class">Back to Top</a>

## Examples
This is a code example to use a chronometer. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' A <see cref="TimeMeasurer"/> instance which is used as a chronometer.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    Private WithEvents chrono As New TimeMeasurer With {.UpdateInterval = 100}

    ' Label used to display the elapsed time.
    Private lblChrono As Label

    Private Shadows Sub Shown() Handles MyBase.Shown

        Me.lblChrono = Me.Label1
        Me.chrono.Start(TimeSpan.FromMinutes(1.0R))

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Handles the <see cref="TimeMeasurer.TimeUpdated"/> event of the chrono instance.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="sender">
    ''' The source of the event.
    ''' </param>
    ''' 
    ''' <param name="e">
    ''' The <see cref="TimeMeasurerUpdatedEventArgs"/> instance containing the event data.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Private Sub Chrono_TimeUpdated(ByVal sender As Object, ByVal e As TimeMeasurerUpdatedEventArgs) _
    Handles chrono.TimeUpdated

        ' H:M:S:MS
        Me.lblChrono.Text = String.Format("{0:00}:{1:00}:{2:00}:{3:000}",
                                          e.Elapsed.Hours, e.Elapsed.Minutes, e.Elapsed.Seconds, e.Elapsed.Milliseconds)

        If (e.Elapsed = e.Goal) Then
            Me.lblChrono.Text = "Chronometer Done!"
        End If

    End Sub

End Class
```


## Examples
This is a code example to use a countdown. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form


    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' A <see cref="TimeMeasurer"/> instance which is used as a countdown.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    Private WithEvents countdown As New TimeMeasurer With {.UpdateInterval = 100}

    ' Label used to display the remaining time.
    Private lblCountdown As Label

    Private Shadows Sub Shown() Handles MyBase.Shown

        Me.lblCountdown = Me.Label1
        Me.countdown.Start(TimeSpan.FromMinutes(1.0R))

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Handles the <see cref="TimeMeasurer.TimeUpdated"/> event of the countdown instance.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="sender">
    ''' The source of the event.
    ''' </param>
    ''' 
    ''' <param name="e">
    ''' The <see cref="TimeMeasurerUpdatedEventArgs"/> instance containing the event data.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Private Sub Countdown_TimeUpdated(ByVal sender As Object, ByVal e As TimeMeasurerUpdatedEventArgs) _
    Handles countdown.TimeUpdated

        ' Measure H:M:S:MS
        Me.lblCountdown.Text = String.Format("{0:00}:{1:00}:{2:00}:{3:000}",
                                             e.Remaining.Hours, e.Remaining.Minutes, e.Remaining.Seconds, e.Remaining.Milliseconds)

        If (e.Elapsed.Subtract(e.Remaining) = e.Goal) Then
            Me.lblCountdown.Text = "Countdown Done!"
        End If

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_DateAndTime">DevCase.Core.DateAndTime Namespace</a><br />