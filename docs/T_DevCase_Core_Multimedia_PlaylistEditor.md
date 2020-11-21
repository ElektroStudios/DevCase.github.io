# PlaylistEditor Class
 

Contains methods to manage the contents of a multimedia playlist file.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Multimedia.PlaylistEditor<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class PlaylistEditor : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class PlaylistEditor
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As PlaylistEditor
```

**C++**<br />
``` C++
public ref class PlaylistEditor sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type PlaylistEditor =  
    class
        inherit AestheticObject
    end
```

The PlaylistEditor type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_PlaylistEditor__ctor">PlaylistEditor</a></td><td>
Initializes a new instance of the PlaylistEditor class.</td></tr></table>&nbsp;
<a href="#playlisteditor-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_PlaylistEditor_Append">Append</a></td><td>
Gets a value indicating whether the append mode is activated.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_PlaylistEditor_Count">Count</a></td><td>
Gets the amount of track entries in the playlist.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_PlaylistEditor_FileEncoding">FileEncoding</a></td><td>
Gets the playlist file encoding.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_PlaylistEditor_FilePath">FilePath</a></td><td>
Gets the playlist filepath.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_PlaylistEditor_Tracks">Tracks</a></td><td>
Gets all the tracks and their extended track information (if any) in the playlist.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_PlaylistEditor_Type">Type</a></td><td>
Gets the playlist type.</td></tr></table>&nbsp;
<a href="#playlisteditor-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_PlaylistEditor_Add_1">Add(String, Boolean)</a></td><td>
Adds a new track entry in the playlist.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_PlaylistEditor_Add">Add(PlaylistTrackInfo, Boolean)</a></td><td>
Adds a new track entry in the playlist, with extended track information.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_PlaylistEditor_Add_2">Add(String, String, TimeSpan, Boolean)</a></td><td>
Adds a new track entry in the playlist, with extended track information.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_PlaylistEditor_Exist">Exist(Int32)</a></td><td>
Determines whether the specified track exists in the playlist.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_PlaylistEditor_Exist_1">Exist(String)</a></td><td>
Determines whether the specified track exists in the playlist.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_PlaylistEditor_GetTrack">GetTrack(Int32)</a></td><td>
Gets the track path and its extended track information (if any) of the specified track index in the playlist.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_PlaylistEditor_GetTrack_1">GetTrack(String)</a></td><td>
Gets the extended track information (if any) of the specified track in the playlist.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_PlaylistEditor_Remove">Remove(Int32)</a></td><td>
Removes the specified track entry from the playlist.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_PlaylistEditor_Remove_1">Remove(String)</a></td><td>
Removes the specified track entry from the playlist.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_PlaylistEditor_Set">Set(Int32, PlaylistTrackInfo)</a></td><td>
Sets the extended track info of the specified track.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_PlaylistEditor_Set_1">Set(String, PlaylistTrackInfo)</a></td><td>
Sets the extended track info of the specified track.</td></tr></table>&nbsp;
<a href="#playlisteditor-class">Back to Top</a>

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
<a href="#playlisteditor-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Private Sub Test

    ' *********************************
    ' Instance the PlaylistEditor Class
    ' *********************************
    Dim playlist As New PlaylistEditor(playlistFile:="C:\Playlist.pls",
                                       playlistType:=PlaylistType.Pls,
                                       append:=False,
                                       fileEncoding:=Encoding.Default)

    ' ******************************************
    ' Retrieve the instanced PlaylistEditor info
    ' ******************************************
    MessageBox.Show(playlist.FilePath)
    MessageBox.Show(playlist.Type.ToString())
    MessageBox.Show(CStr(playlist.Append))
    MessageBox.Show(String.Format("Encoding: {0}, CodePage: {1}",
                                  playlist.FileEncoding.BodyName,
                                  playlist.FileEncoding.CodePage))

    ' **************************
    ' Instance a TrackInfo Class
    ' **************************
    Dim tInfo As New PlaylistTrackInfo
    With tInfo
        .Path = "C:\Track1.ext"
        .Title = "Track1 Title"
        .Length = TimeSpan.Parse("00:05:30")
    End With

    ' ***************
    ' Add a new track
    ' ***************
    playlist.Add(TrackInfo:=tInfo)
    playlist.Add(filepath:="C:\Track2.ext", allowDuplicate:=False)
    playlist.Add(filepath:="C:\Track3.ext", title:="Track3 Title", length:=TimeSpan.Parse("01:35:20"))

    ' *************************************************
    ' Sets the extended track info of an existing track
    ' *************************************************
    Dim oldTrackPath As String = "C:\Track2.ext"

    Dim tInfoSet As New PlaylistTrackInfo
    With tInfoSet
        .Path = "C:\Modified Track2.ext"
        .Title = "My modified Track2 title"
        .Length = playlist.GetTrack(oldTrackPath).Length
    End With

    playlist.Set(filepath:=oldTrackPath, trackInfo:=tInfoSet)

    ' ************************
    ' Remove an existing track
    ' ************************
    playlist.Remove(filepath:="C:\Track3.ext")
    playlist.Remove(trackIndex:=2)

    ' ********************************
    ' Determine whether a track exists
    ' ********************************
    MessageBox.Show(CStr(playlist.Exist(filepath:="C:\Track3.ext")))
    MessageBox.Show(CStr(playlist.Exist(trackIndex:=3)))

    ' ************************************************
    ' Count the total amount of tracks in the playlist
    ' ************************************************
    MessageBox.Show(CStr(playlist.Count))

    ' ************************************
    ' Get extended track info from a track
    ' ************************************
    Dim trackInfo1 As PlaylistTrackInfo = playlist.GetTrack(filepath:="C:\Track1.ext")
    Dim trackInfo2 As PlaylistTrackInfo = playlist.GetTrack(trackIndex:=2)

    ' ******************************************
    ' Get all tracks and its extended track info
    ' ******************************************
    Dim tracks As ReadOnlyCollection(Of PlaylistTrackInfo) = playlist.Tracks()

    For Each track As PlaylistTrackInfo In tracks

        Dim sb As New Global.System.Text.StringBuilder
        With sb
            .AppendLine(String.Format("Track Index : {0}", CStr(track.Index)))
            .AppendLine(String.Format("Track Path  : {0}", track.Path))
            .AppendLine(String.Format("Track Title : {0}", track.Title))
            .AppendLine(String.Format("Track Length: {0}", Convert.ToString(track.Length)))
        End With

        MessageBox.Show(sb.ToString())

    Next track

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />