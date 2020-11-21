# MediaInfoFile Class
 

Exposes the `MediaInfo.dll` functionalities in a friendly object to use with the specified file.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.MediaInfo.MediaInfoFile<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MediaInfo">DevCase.ThirdParty.MediaInfo</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class MediaInfoFile : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class MediaInfoFile
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As MediaInfoFile
```

**C++**<br />
``` C++
public ref class MediaInfoFile sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type MediaInfoFile =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The MediaInfoFile type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MediaInfo_MediaInfoFile__ctor">MediaInfoFile(FileInfo)</a></td><td>
Initializes a new instance of the MediaInfoFile class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MediaInfo_MediaInfoFile__ctor_1">MediaInfoFile(String)</a></td><td>
Initializes a new instance of the MediaInfoFile class.</td></tr></table>&nbsp;
<a href="#mediainfofile-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MediaInfo_MediaInfoFile_FieldCount">FieldCount</a></td><td>
Gets the count of information fields available in the specified stream of the open file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MediaInfo_MediaInfoFile_Fields">Fields(StreamType, Fields)</a></td><td>
Gets the value of the specified information field in the open file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MediaInfo_MediaInfoFile_Fields_3">Fields(StreamType, String)</a></td><td>
Gets the value of the specified information field in the open file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MediaInfo_MediaInfoFile_Fields_1">Fields(StreamType, Int32, Fields)</a></td><td>
Gets the value of the specified information field in the open file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MediaInfo_MediaInfoFile_Fields_2">Fields(StreamType, Int32, String)</a></td><td>
Gets the value of the specified information field in the open file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MediaInfo_MediaInfoFile_Inform">Inform</a></td><td>
Gets all the details about the open file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MediaInfo_MediaInfoFile_StreamCount">StreamCount</a></td><td>
Gets the count of streams in the open file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MediaInfo_MediaInfoFile_StreamCount_1">StreamCount(StreamType)</a></td><td>
Gets the count of streams of the specified <a href="T_DevCase_ThirdParty_MediaInfo_StreamType">StreamType</a> type in the open file.</td></tr></table>&nbsp;
<a href="#mediainfofile-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MediaInfo_MediaInfoFile_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MediaInfo_MediaInfoFile_GetStreamCount">GetStreamCount</a></td><td>
Gets the count of streams of the specified <a href="T_DevCase_ThirdParty_MediaInfo_StreamType">StreamType</a> type in the open file.</td></tr></table>&nbsp;
<a href="#mediainfofile-class">Back to Top</a>

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
<a href="#mediainfofile-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Sub Test()

    ' Track position
    Dim streamIndex As Integer = 0

    ' Open a file.
    Dim mi As New MediaInfoFile("C:\File.mkv")

    ' Get full inform of file.
    MsgBox(mi.Inform)

    MsgBox(String.Format("Fullpath: {0}", mi.Fields(StreamType.General, Fields.CompleteName)))
    MsgBox(String.Format("Directory: {0}", mi.Fields(StreamType.General, Fields.FolderName)))
    MsgBox(String.Format("Filename: {0}", mi.Fields(StreamType.General, Fields.FileName)))
    MsgBox(String.Format("Extension: {0}", mi.Fields(StreamType.General, Fields.FileExtension).ToLower()))
    MsgBox(String.Format("Format: {0}", mi.Fields(StreamType.General, Fields.Format)))
    MsgBox(String.Format("Size (bytes): {0}", mi.Fields(StreamType.General, Fields.FileSize)))
    MsgBox(String.Format("Title (metadata): {0}", mi.Fields(StreamType.General, Fields.Title)))
    MsgBox(String.Format("Audio format: {0}", mi.Fields(StreamType.Audio, streamIndex, Fields.Format)))
    MsgBox(String.Format("Audio BitRate (bps): {0}", mi.Fields(StreamType.Audio, Fields.BitRate)))
    MsgBox(String.Format("Audio duration (HH:MM:SS): {0}", mi.Fields(StreamType.Audio, Fields.Duration__String3).Split("."c)(0)))
    MsgBox(String.Format("Video format: {0}", mi.Fields(StreamType.Video, streamIndex, Fields.Format)))
    MsgBox(String.Format("Video BitRate (bps): {0}", mi.Fields(StreamType.Video, Fields.BitRate)))
    MsgBox(String.Format("Video duration (HH:MM:SS): {0}", mi.Fields(StreamType.Video, Fields.Duration__String3).Split("."c)(0)))
    MsgBox(String.Format("Video Framecount (Total frames): {0}", mi.Fields(StreamType.Video, streamIndex, Fields.FrameCount)))
    MsgBox(String.Format("Video Contains Attachments?: {0}", mi.Fields(StreamType.Video, Fields.Attachment)))
    MsgBox(String.Format("Audio track count: {0}", mi.StreamCount(StreamType.Audio)))

    ' Processes all the audio tracks of a video file
    While Not streamIndex = mi.StreamCount(StreamType.Audio)
        MsgBox(mi.Fields(StreamType.Audio, streamIndex, Fields.Format))
        streamIndex += 1
    End While

    ' Close the file by disposing the instance.
    mi.Dispose()

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_MediaInfo">DevCase.ThirdParty.MediaInfo Namespace</a><br />