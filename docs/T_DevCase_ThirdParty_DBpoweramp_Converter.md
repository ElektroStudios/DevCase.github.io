# Converter Class
 

A wrapper of `CoreConverter.exe` application.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.DBpoweramp.Converter<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

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
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DBpoweramp_Converter__ctor">Converter</a></td><td>
Initializes a new instance of the Converter class.</td></tr></table>&nbsp;
<a href="#converter-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_DBpoweramp_Converter_Exists">Exists</a></td><td>
Gets a value indicating whether the `CoreConverter.exe` file Exists.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_DBpoweramp_Converter_FilePath">FilePath</a></td><td>
Gets the `CoreConverter.exe` filepath.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_DBpoweramp_Converter_Process">Process</a></td><td>
Gets the `CoreConverter.exe`<a href="P_DevCase_ThirdParty_DBpoweramp_Converter_Process">Process</a> instance.</td></tr></table>&nbsp;
<a href="#converter-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DBpoweramp_Converter_ConvertToMP3">ConvertToMP3(FileInfo, String, LameBitrate, LameBitrateMode, LameFrequency, LameProfile, LameQuality, LameChannelMode, CoreConverterDspEffect, Boolean, CoreConverterPriority, Int32)</a></td><td>
Converts a file to MP3 using LAME codec.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DBpoweramp_Converter_ConvertToMP3_1">ConvertToMP3(String, String, LameBitrate, LameBitrateMode, LameFrequency, LameProfile, LameQuality, LameChannelMode, CoreConverterDspEffect, Boolean, CoreConverterPriority, Int32)</a></td><td>
Converts a file to MP3 using LAME codec.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DBpoweramp_Converter_ConvertToWav">ConvertToWav(FileInfo, String, WavBitdepth, WavFrequency, WavChannelMode, CoreConverterDspEffect, Boolean, CoreConverterPriority, Int32)</a></td><td>
Converts a file to uncompressed WAV.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DBpoweramp_Converter_ConvertToWav_1">ConvertToWav(String, String, WavBitdepth, WavFrequency, WavChannelMode, CoreConverterDspEffect, Boolean, CoreConverterPriority, Int32)</a></td><td>
Converts a file to uncompressed WAV.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DBpoweramp_Converter_ConvertToWma">ConvertToWma(FileInfo, String, Wma9Bitrate, Wma9Frequency, Wma9ChannelMode, CoreConverterDspEffect, Boolean, CoreConverterPriority, Int32)</a></td><td>
Converts a file to WMA v9.2</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DBpoweramp_Converter_ConvertToWma_1">ConvertToWma(String, String, Wma9Bitrate, Wma9Frequency, Wma9ChannelMode, CoreConverterDspEffect, Boolean, CoreConverterPriority, Int32)</a></td><td>
Converts a file to WMA v9.2</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_DBpoweramp_Converter_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#converter-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_DBpoweramp_Converter_Exited">Exited</a></td><td>
Event raised when the `CoreConverter.exe` process has exited.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_DBpoweramp_Converter_ProgressChanged">ProgressChanged</a></td><td>
Event raised when `CoreConverter.exe` task progress has been changed.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_DBpoweramp_Converter_Started">Started</a></td><td>
Event raised when the `CoreConverter.exe` process has been started.</td></tr></table>&nbsp;
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
Sub Test()

Private WithEvents converter As New Converter(".\CoreConverter.exe")

Private Sub Test() Handles MyBase.Shown

    If Not converter.Exists Then
        MessageBox.Show(String.Format("Coreconverter.exe not found in {0}", converter.FilePath))
    End If

    ' Convert a file to MP3.
    converter.ConvertToMP3("C:\Input.wav", "C:\Output.mp3",
                           LameBitrate.Kbps320,
                           LameBitrateMode.Cbr,
                           LameFrequency.SameAsSource,
                           LameProfile.Slow,
                           LameQuality.Maximum,
                           LameChannelMode.Auto,
                           CoreConverterDspEffect.DeleteOutputFileOnError Or CoreConverterDspEffect.RecycleSourceFileAfterConversion,
                           False,
                           CoreConverterPriority.Normal)

    ' Convert a file to WAV.
    converter.ConvertToWav("C:\Input.mp3", "C:\Output.wav",
                           WavBitdepth.SameAsSource,
                           WavFrequency.SameAsSource,
                           WavChannelMode.SameAsSource,
                           CoreConverterDspEffect.None,
                           False,
                           CoreConverterPriority.Normal)

    ' Convert a file to WMA.
    converter.ConvertToWma("C:\Input.mp3", "C:\Output.wma",
                           Wma9Bitrate.Kbps128,
                           Wma9Frequency.Khz44100,
                           Wma9ChannelMode.Stereo,
                           CoreConverterDspEffect.None,
                           False,
                           CoreConverterPriority.Normal)

End Sub

''' ----------------------------------------------------------------------------------------------------
''' <summary>
''' Handles the Started event of the converter object instance.
''' </summary>
''' ----------------------------------------------------------------------------------------------------
''' <param name="sender">
''' The source of the event.
''' </param>
''' 
''' <param name="e">
''' The <see cref="CoreConverterStartedEventArgs"/> instance containing the event data.
''' </param>
''' ----------------------------------------------------------------------------------------------------
Private Sub Converter_Started(ByVal sender As Object, ByVal e As CoreConverterStartedEventArgs) _
Handles converter.Started

    ProgressBar1.Value = ProgressBar1.Minimum

    Dim sb As New System.Text.StringBuilder
    With sb
        .AppendLine(String.Format("Started an ""{0}"" operation", e.Task.ToString()))
        .AppendLine(String.Format("Input file is: ""{0}""", e.InputFile))
        .AppendLine(String.Format("CoreConverter.exe process id (PID) is: {0}", CStr(DirectCast(sender, Converter).Process.Id)))
    End With

    Debug.WriteLine(String.Format("Start Time: {0}", Date.Now.ToLongTimeString))
    Debug.WriteLine(sb.ToString())

End Sub

''' ----------------------------------------------------------------------------------------------------
''' <summary>
''' Handles the Exited event of the converter object instance.
''' </summary>
''' ----------------------------------------------------------------------------------------------------
''' <param name="sender">
''' The source of the event.
''' </param>
''' 
''' <param name="e">
''' The <see cref="CoreConverterExitedEventArgs"/> instance containing the event data.
''' </param>
''' ----------------------------------------------------------------------------------------------------
Private Sub Converter_Exited(ByVal sender As Object, ByVal e As CoreConverterExitedEventArgs) _
Handles converter.Exited

    Dim sb As New System.Text.StringBuilder
    With sb
        .AppendLine(String.Format("Finished an ""{0}"" operation", e.Task.ToString()))
        .AppendLine(String.Format("Input file is: ""{0}""", e.InputFile))
        .AppendLine(String.Format("Output file is: ""{0}""", e.OutputFile))
    End With

    If Not String.IsNullOrEmpty(e.ErrorMessage) Then
        sb.AppendLine(String.Format("Error Information: {0}", e.ErrorMessage))
    End If

    If Not String.IsNullOrEmpty(e.ElapsedTime) Then
        sb.AppendLine(String.Format("Total elapsed time: {0}", e.ElapsedTime))
    End If

    Debug.WriteLine(sb.ToString())
    Debug.WriteLine(String.Format("End Time: {0}", Date.Now.ToLongTimeString))

End Sub

''' ----------------------------------------------------------------------------------------------------
''' <summary>
''' Handles the ProgressUpdated event of the converter object instance.
''' </summary>
''' ----------------------------------------------------------------------------------------------------
''' <param name="sender">
''' The source of the event.
''' </param>
''' 
''' <param name="e">
''' The <see cref="CoreConverterProgressEventArgs"/> instance containing the event data.
''' </param>
''' ----------------------------------------------------------------------------------------------------
Private Sub Converter_ProgressChanged(ByVal sender As Object, ByVal e As CoreConverterProgressEventArgs) _
Handles converter.ProgressChanged

    ProgressBar1.Value = e.Percent
    Label1.Text = CStr(e.Percent)
    Application.DoEvents()

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp Namespace</a><br />