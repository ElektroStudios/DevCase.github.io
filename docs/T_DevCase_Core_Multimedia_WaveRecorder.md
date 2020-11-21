# WaveRecorder Class
 

Defines a Wave audio recorder.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Multimedia.WaveRecorder<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class WaveRecorder : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public Class WaveRecorder
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As WaveRecorder
```

**C++**<br />
``` C++
public ref class WaveRecorder : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
type WaveRecorder =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The WaveRecorder type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_WaveRecorder__ctor">WaveRecorder</a></td><td>
Initializes a new instance of the WaveRecorder class.</td></tr></table>&nbsp;
<a href="#waverecorder-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_WaveRecorder_Status">Status</a></td><td>
Gets the current recording status.</td></tr></table>&nbsp;
<a href="#waverecorder-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_WaveRecorder_Delete">Delete</a></td><td>
Deletes any audio recorded.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_WaveRecorder_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_WaveRecorder_Play">Play</a></td><td>
Plays the recording.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_WaveRecorder_Record">Record</a></td><td>
Starts or resumes the audio recording.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_WaveRecorder_Save">Save</a></td><td>
Stops recording and saves the recorded audio to disk.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_WaveRecorder_Stop">Stop</a></td><td>
Stops recording.</td></tr></table>&nbsp;
<a href="#waverecorder-class">Back to Top</a>

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
<a href="#waverecorder-class">Back to Top</a>

## Remarks
Default recording quality specifications: Microsoft Wave, two channels (Stereo), 16-bit depth, 44.100 khz, 192.000 kbps.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim recorder As New WaveRecorder

Sub Button_Record_Click() Handles Button_Record.Click

    If Not (recorder.Status = RecorderStatus.Recording) Then
        recorder.Record()
    End If

End Sub

Sub Button_Stop_Click() Handles Button_Stop.Click

    If (recorder.Status = RecorderStatus.Recording) Then
        recorder.Stop()
    End If

End Sub

Sub Button_Play_Click() Handles Button_Play.Click

    If (recorder.Status = RecorderStatus.Stopped) Then
        recorder.Play()
    End If

End Sub

Sub Button_Delete_Click() Handles Button_Delete.Click

    If Not (recorder.Status = RecorderStatus.Empty) Then
        recorder.Delete()
    End If

End Sub

Sub Button_Save_Click() Handles Button_Save.Click

    If Not (recorder.Status = RecorderStatus.Empty) Then
        recorder.Save("C:\File.wav", overWrite:=True)
    End If

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />