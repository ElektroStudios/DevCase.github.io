# Converter Class
 

A wrapper of `FFMPEG.exe` application.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.Ffmpeg.Converter<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Ffmpeg">DevCase.ThirdParty.Ffmpeg</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class Converter : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class Converter
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As Converter
```

**C++**<br />
``` C++
public ref class Converter sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type Converter =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The Converter type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Ffmpeg_Converter__ctor">Converter</a></td><td>
Initializes a new instance of the Converter class.</td></tr></table>&nbsp;
<a href="#converter-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Ffmpeg_Converter_Exists">Exists</a></td><td>
Gets a value indicating whether the `FFMPEG.exe` file Exists.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Ffmpeg_Converter_FilePath">FilePath</a></td><td>
Gets the `FFMPEG.exe` filepath.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Ffmpeg_Converter_Process">Process</a></td><td>
Gets the `FFMPEG.exe`<a href="P_DevCase_ThirdParty_Ffmpeg_Converter_Process">Process</a> instance.</td></tr></table>&nbsp;
<a href="#converter-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Ffmpeg_Converter_DemuxAudio">DemuxAudio</a></td><td>
Demuxes the audio track of a video file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Ffmpeg_Converter_DemuxVideo">DemuxVideo</a></td><td>
Demuxes the video track of a video file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Ffmpeg_Converter_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Ffmpeg_Converter_RecompressAudio">RecompressAudio</a></td><td>
ReCompress the audio track of a video file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Ffmpeg_Converter_RemoveVideoMetadata">RemoveVideoMetadata</a></td><td>
Removes the metadata tags from a video file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Ffmpeg_Converter_SaveAudioAsWav">SaveAudioAsWav</a></td><td>
Demuxes the audio track of a video file to save it as WAV format.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Ffmpeg_Converter_VideoContainsMetadata">VideoContainsMetadata</a></td><td>
Determines whether a video file contains metadata fields.</td></tr></table>&nbsp;
<a href="#converter-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_Ffmpeg_Converter_Exited">Exited</a></td><td>
Event raised when the `FFMPEG.exe` process has exited.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_Ffmpeg_Converter_ProgressChanged">ProgressChanged</a></td><td>
Event raised when `FFMPEG.exe` task progress has been changed.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_Ffmpeg_Converter_Started">Started</a></td><td>
Event raised when the `FFMPEG.exe` process has been started.</td></tr></table>&nbsp;
<a href="#converter-class">Back to Top</a>

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
<a href="#converter-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Private WithEvents ff As New Converter(".\FFMPEG.exe")

Private Shadows Sub Shown() Handles MyBase.Shown

    ' Checks if FFMPEG executable is available.
    MsgBox(ff.Exists)

    ' Checks if a video has metadata
    MsgBox(ff.VideoContainsMetadata("C:\Video.mkv"))

    ' Remove metadata from video
    ff.RemoveVideoMetadata("C:\Input.mkv", "C:\Output.mkv", True, 4)

    ' reCompress the audio track of a video
    ff.RecompressAudio("C:\Input.mkv", "C:\Output.mkv", True, FfmpegAudioCodec.libmp3lame, FfmpegAudioBitrate.Kbps128, True, 4)

    ' Demuxes the audio track of file
    ff.DemuxAudio("C:\Input.wmv", "C:\Output.wma", True, 4)

    ' Demuxes the video track of file
    ff.DemuxVideo("C:\Input.mp4", "C:\Output.h264", True, 4)

    ' Demuxes the video track of file
    ff.SaveAudioAsWav("C:\Input.mkv", "C:\Output.wav", True, 4)

End Sub

Private Sub Ffmeg_Started(ByVal sender As Object, ByVal e As FfmpegStartedEventArgs) _
Handles ff.Started

    ProgressBar1.Value = ProgressBar1.Minimum

    Dim sb As New System.Text.StringBuilder

    sb.AppendLine(String.Format("Started an ""{0}"" operation", e.Task.ToString()))
    sb.AppendLine(String.Format("Input file is: ""{0}""", e.File))
    sb.AppendLine(String.Format("FFMPEG process PID is: ""{0}""", DirectCast(sender, Converter).Process.Id))

    MessageBox.Show(sb.ToString(), "FFMPEG", MessageBoxButtons.OK, MessageBoxIcon.Information)

End Sub

Private Sub Ffmeg_Exited(ByVal sender As Object, ByVal e As FfmpegExitedEventArgs) _
Handles ff.Exited

    Dim sb As New System.Text.StringBuilder

    sb.AppendLine(String.Format("Finished an ""{0}"" operation", e.Task.ToString()))
    sb.AppendLine(String.Format("Input file is: ""{0}""", e.File))
    sb.AppendLine(String.Format("FFMPEG process PID is: {0}", DirectCast(sender, Process).Id))

    If e.Errors.Count <> 0 Then
        sb.AppendLine(String.Format("Errors during operation: {0}", String.Join(Environment.NewLine, e.Errors)))
    End If

    MessageBox.Show(sb.ToString(), "FFMPEG", MessageBoxButtons.OK, MessageBoxIcon.Information)

End Sub

Private Sub Ffmeg_ProgressChanged(ByVal sender As Object, e As FfmpegProgressEventArgs) _
Handles ff.ProgressChanged

    ProgressBar1.Value = e.Percent

    Label1.Text = "Percent Done: " & CStr(e.Percent) & "%"
    Label2.Text = "Video Duration: " & e.VideoDuration.ToString("hh\:mm\:ss")
    Label3.Text = "Written Duration: " & e.Time.ToString("hh\:mm\:ss")
    Label4.Text = "Written Data: " & (e.WrittenBytes / 1024L * 1024L).ToString("n1") & "MB"

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_Ffmpeg">DevCase.ThirdParty.Ffmpeg Namespace</a><br />