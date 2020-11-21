# MP3File Class
 

Reads, writes or removes the tags (ID3v1, ID3v2, APEv2) of a MP3 file.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.TagLibSharp.MP3File<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class MP3File : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class MP3File
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3File
```

**C++**<br />
``` C++
public ref class MP3File sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type MP3File =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The MP3File type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_TagLibSharp_MP3File__ctor">MP3File(FileInfo)</a></td><td>
Initializes a new instance of the MP3File class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_TagLibSharp_MP3File__ctor_1">MP3File(String)</a></td><td>
Initializes a new instance of the MP3File class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_TagLibSharp_MP3File__ctor_2">MP3File(AudioFile)</a></td><td>
Initializes a new instance of the MP3File class.</td></tr></table>&nbsp;
<a href="#mp3file-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_MP3File_CorruptionReasons">CorruptionReasons</a></td><td>
Gets the reasons, if any, for which the file is corrupt.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_MP3File_Cover">Cover</a></td><td>
Gets or sets the cover of the audio file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_MP3File_File">File</a></td><td>
Gets the audio file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_MP3File_IsCorrupt">IsCorrupt</a></td><td>
Gets a value indicating whether the audio file is possibly corrupt.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_MP3File_IsWriteable">IsWriteable</a></td><td>
Gets a value indicating whether the tags can be written or not in the audio file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_MP3File_Lyrics">Lyrics</a></td><td>
Gets or sets the lyrics of the audio file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_MP3File_Tags">Tags</a></td><td>
Gets the MP3 tags.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_MP3File_TagTypes">TagTypes</a></td><td>
Gets the tag types of the audio file (Id3v1, Id3v2, APE, etc).</td></tr></table>&nbsp;
<a href="#mp3file-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_TagLibSharp_MP3File_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_TagLibSharp_MP3File_SaveFile">SaveFile</a></td><td>
Saves any tag modifications to the audio file.</td></tr></table>&nbsp;
<a href="#mp3file-class">Back to Top</a>

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
<a href="#mp3file-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using file As New Mp3File("C:\File.mp3")

    If file.IsCorrupt Then
        MsgBox(file.CorruptionReasons)
    End If

    file.Cover = Image.FromFile("C:\Cover.jpg")

    With file.Tags.ID3v1
        .Title = "Title ID3v1"
        .Album = "Album ID3v1"
        .Artist = "Artist ID3v1"
        .Genre = "Pop"
        .Year = 2001
        .Track = 1
        .Comment = "Comment ID3v1"
    End With

    With file.Tags.ID3v2
        .Title = "Title ID3v2"
        .Album = "Album ID3v2"
        .Artist = "Artist ID3v2"
        .Composer = "Composer ID3v2"
        .Genre = "Pop"
        .Year = 2002
        .Bpm = 202
        .Disc = 2
        .Track = 2
        .Comment = "Comment ID3v2"
        .Copyright = "Copyright ID3v2"
    End With

    If file.TagTypes.HasFlag(Mp3TagTypes.Apev2) Then
        file.Tags.APEv2.Remove()
    End If

    file.SaveFile()

End Using
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp Namespace</a><br />