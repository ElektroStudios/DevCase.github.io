# SoftwareUtil.Winamp Class
 

Contains Winamp info.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.Tools.SoftwareUtil.Winamp<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class Winamp : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class Winamp
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As SoftwareUtil.Winamp
```

**C++**<br />
``` C++
public ref class Winamp sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type Winamp =  
    class
        inherit AestheticObject
    end
```

The SoftwareUtil.Winamp type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_CurrentPlaybackPosition">CurrentPlaybackPosition</a></td><td>
Gets or sets the position, in milliseconds, of the current playback in the Winamp process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_CurrentPlaybackState">CurrentPlaybackState</a></td><td>
Gets the current playback state of the Winamp process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_CurrentSongFilename">CurrentSongFilename</a></td><td>
Gets the filename of the current song that is playing in Winamp process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_CurrentSongTitle">CurrentSongTitle</a></td><td>
Gets the title of the current song that is playing in Winamp process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_CurrentTrackBitrate">CurrentTrackBitrate</a></td><td>
Gets the bitrate of the current track in the Winamp process. (i.e: 320, 256, 192, 128, etc...)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_CurrentTrackChannels">CurrentTrackChannels</a></td><td>
Gets the channel count of the current track in the Winamp process. (i.e: 2, 1)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_CurrentTrackLength">CurrentTrackLength</a></td><td>
Gets the length, in milliseconds, of the current track in the Winamp process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_CurrentTrackSampleRate">CurrentTrackSampleRate</a></td><td>
Gets the sample rate of the current track in the Winamp process. (i.e: 48, 44, 22, etc...)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_CurrentVolume">CurrentVolume</a></td><td>
Gets or sets the volume level, from 0 to 100, of the current playback in the Winamp process.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_ExecutablePath">ExecutablePath</a></td><td>
Gets the filepath of the Winamp executabl file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_Handle">Handle</a></td><td>
Gets a window handle to the Winamp process main window.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_IsRunning">IsRunning</a></td><td>
Gets a value indicating whether Winamp process is running.</td></tr></table>&nbsp;
<a href="#softwareutil.winamp-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_ClearPlaylist">ClearPlaylist</a></td><td>
Clears the songs playlist.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_FastForward">FastForward</a></td><td>
Fast forwards the current song by 5 seconds.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_JumpToNextSong">JumpToNextSong</a></td><td>
Jumps to the next song in the playlist.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_JumpToPreviousSong">JumpToPreviousSong</a></td><td>
Jumps to the previous song in the playlist.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_Minimize">Minimize</a></td><td>
Minimizes the Winamp window</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_Pause">Pause</a></td><td>
Pause or resume the song playback.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_Play">Play</a></td><td>
Starts the song playback.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_Quit">Quit</a></td><td>
Quits from Winamp.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_Rewind">Rewind</a></td><td>
Rewinds the current song by 5 seconds.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_Stop">Stop</a></td><td>
Stops the song playback.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_VolumeDown">VolumeDown</a></td><td>
Decreases the volume level</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_VolumeUp">VolumeUp</a></td><td>
Increases the volume level</td></tr></table>&nbsp;
<a href="#softwareutil.winamp-class">Back to Top</a>

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
<a href="#softwareutil.winamp-class">Back to Top</a>

## Remarks
Winamp messages were took from this: <a href="http://sourceforge.net/p/wacc/code/HEAD/tree/" target="_blank">http://sourceforge.net/p/wacc/code/HEAD/tree/</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />