# AudioPlayer Class
 

Plays a Wave, Mp3 or Mid file.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.NativeWindow<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticNativeWindow">DevCase.Core.Design.AestheticNativeWindow</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Multimedia.AudioPlayer<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class AudioPlayer : AestheticNativeWindow, 
	IDisposable
```

**VB**<br />
``` VB
Public Class AudioPlayer
	Inherits AestheticNativeWindow
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As AudioPlayer
```

**C++**<br />
``` C++
public ref class AudioPlayer : public AestheticNativeWindow, 
	IDisposable
```

**F#**<br />
``` F#
type AudioPlayer =  
    class
        inherit AestheticNativeWindow
        interface IDisposable
    end
```

The AudioPlayer type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_AudioPlayer__ctor">AudioPlayer</a></td><td>
Initializes a new instance of the AudioPlayer class.</td></tr></table>&nbsp;
<a href="#audioplayer-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_AudioPlayer_Channels">Channels</a></td><td>
Gets the channels of the current audio file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_AudioPlayer_Filepath">Filepath</a></td><td>
Gets the filepath of the audio file that will be played.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_AudioPlayer_Handle">Handle</a></td><td>
Gets the handle for the NativeWindow that owns this AudioPlayer instance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_AudioPlayer_IsFileLoaded">IsFileLoaded</a></td><td>
Gets a value that indicates whether the player has loaded a file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_AudioPlayer_Length">Length</a></td><td>
Gets the audio length of the current file, in milleseconds.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_AudioPlayer_PlaybackMode">PlaybackMode</a></td><td>
Gets or sets the playback mode for the current audio file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_AudioPlayer_Position">Position</a></td><td>
Gets the audio position of the current playback, in milleseconds.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_AudioPlayer_Status">Status</a></td><td>
Gets the current player State.</td></tr></table>&nbsp;
<a href="#audioplayer-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_AudioPlayer_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_AudioPlayer_LoadFile">LoadFile</a></td><td>
Loads an audio file on the player.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_AudioPlayer_Pause">Pause</a></td><td>
Pauses the current playback.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_AudioPlayer_Play">Play</a></td><td>
Plays the file that is specified as the filename.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_AudioPlayer_Resume">Resume</a></td><td>
Resumes a previously paused playback.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_AudioPlayer_Seek">Seek(Int64)</a></td><td>
Sets the playback position.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_AudioPlayer_Seek_1">Seek(TimeSpan)</a></td><td>
Pauses the current playback.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_AudioPlayer_Stop">Stop</a></td><td>
Stops the current playback.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_AudioPlayer_UnLoadFile">UnLoadFile</a></td><td>
Unloads the current audio file from playback.</td></tr></table>&nbsp;
<a href="#audioplayer-class">Back to Top</a>

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
<a href="#audioplayer-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim player As New AudioPlayer

Sub Button_LoadFile_Click() Handles Button_LoadFile.Click

    If Not player.IsFileLoaded Then
        player.LoadFile("C:\File.wav")
    End If

End Sub

Sub Button_Play_Click() Handles Button_Play.Click

    If Not (player.Status = PlayerStatus.Playing) Then
        player.Play(AudioPlayMode.Background)
    End If

End Sub

Sub Button_Stop_Click() Handles Button_Stop.Click

    If Not (player.Status = PlayerStatus.Stopped) Then
        player.Stop()
    End If

End Sub

Sub Button_PauseResume_Click() Handles Button_PauseResume.Click

    If (player.Status = PlayerStatus.Playing) Then
        player.Pause()

    ElseIf (player.Status = PlayerStatus.Paused) Then
        player.Resume()

    End If

End Sub

Private Sub Button_SeekBackward_Click(sender As Object, e As EventArgs) Handles Button_SeekBackward.Click

    Dim currentPosition As Long = CLng(player.Position.TotalMilliseconds)

    If ((currentPosition - 5000) <= 0) Then
        player.Seek(0)

    Else
        player.Seek(currentPosition - 5000)

    End If

End Sub

Private Sub Button_SeekForward_Click(sender As Object, e As EventArgs) Handles Button_SeekForward.Click

    Dim currentPosition As Long = CLng(player.Position.TotalMilliseconds)

    If Not ((currentPosition + 5000) >= player.Length) Then
        player.Seek(currentPosition + 5000)
    End If

End Sub

Sub Button_UnloadFile_Click() Handles Button_UnloadFile.Click

    If player.IsFileLoaded Then
        player.UnLoadFile()
    End If

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />