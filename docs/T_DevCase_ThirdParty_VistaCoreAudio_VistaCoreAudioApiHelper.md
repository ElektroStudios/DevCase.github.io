# VistaCoreAudioApiHelper Class
 

Contains VistaCoreAudioAPI related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.VistaCoreAudio.VistaCoreAudioApiHelper<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class VistaCoreAudioApiHelper : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class VistaCoreAudioApiHelper
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As VistaCoreAudioApiHelper
```

**C++**<br />
``` C++
public ref class VistaCoreAudioApiHelper sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type VistaCoreAudioApiHelper =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The VistaCoreAudioApiHelper type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper__ctor">VistaCoreAudioApiHelper</a></td><td>
Initializes a new instance of the VistaCoreAudioApiHelper class.</td></tr></table>&nbsp;
<a href="#vistacoreaudioapihelper-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_ChannelsCount">ChannelsCount</a></td><td>
Gets the total amount of device channels.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_DeviceMonitorsEnabled">DeviceMonitorsEnabled</a></td><td>
Gets or sets a value indicating whether the audio device timers that monitors and reports changes are enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_IsLocked">IsLocked</a></td><td>
Gets a value indicating whether the device is locked.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_IsMuted">IsMuted</a></td><td>
Gets a value indicating whether the device is muted.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_Name">Name</a></td><td>
Gets the audio device name.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_TimerChannelsVolumeChangedDetectionInterval">TimerChannelsVolumeChangedDetectionInterval</a></td><td>
Gets or sets the Channels-Volume changed detection interval, in milliseconds. This interval is associated with a timer that monitors and reports Channels-Volume changes on the device.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_TimerMasterVolumeChangedDetectionInterval">TimerMasterVolumeChangedDetectionInterval</a></td><td>
Gets or sets the Master-Volume changed detection interval, in milliseconds. This interval is associated with a timer that monitors and reports Master-Volume changes on the device.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_TimerMuteDetectionInterval">TimerMuteDetectionInterval</a></td><td>
Gets or sets the mute detection interval, in milliseconds. This interval is associated with a timer that monitors and reports Mute changes on the device.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_Volume">Volume</a></td><td>
Gets or sets the current device volume.</td></tr></table>&nbsp;
<a href="#vistacoreaudioapihelper-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_GetAllChannelVolume">GetAllChannelVolume</a></td><td>
Gets the volume of all the device channels.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_GetChannelVolume">GetChannelVolume</a></td><td>
Gets the volume of an specific device channel.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_LockDevice">LockDevice</a></td><td>
Locks the device, disabling to mute or change the volume.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_MuteDevice">MuteDevice</a></td><td>
Mutes the device.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_SetAllChannelVolume">SetAllChannelVolume</a></td><td>
Sets the volume for all the device channels.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_SetChannelVolume">SetChannelVolume</a></td><td>
Sets the volume for an specific device channel.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_UnlockDevice">UnlockDevice</a></td><td>
Unlocks the device, enabling to mute or change the volume.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_UnmuteDevice">UnmuteDevice</a></td><td>
Unmutes the device.</td></tr></table>&nbsp;
<a href="#vistacoreaudioapihelper-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_ChannelVolumeChanged">ChannelVolumeChanged</a></td><td>
Event raised when a device channel(s) volume changes</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_MasterVolumeChanged">MasterVolumeChanged</a></td><td>
Event raised when device master-volume changes.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper_MutedChanged">MutedChanged</a></td><td>
Event raised when device muting changes.</td></tr></table>&nbsp;
<a href="#vistacoreaudioapihelper-class">Back to Top</a>

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
<a href="#vistacoreaudioapihelper-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
' Instance the Class:
' ###################
Friend WithEvents AudioDevice As New VistaCoreAudioApiHelper(EnableDeviceMonitors:=True)

' Disable or enable Monitors, and/or it's intervals:
' ##################################################
AudioDevice.DeviceMonitorsEnabled = True
AudioDevice.Timer_MasterVolumeChanged_DetectionInterval = 100I
AudioDevice.Timer_ChannelsVolumeChanged_DetectionInterval = 100I
AudioDevice.Timer_Mute_DetectionInterval = 100I

' Get the DeviceName
' ##################
MessageBox.Show(String.Format("Device Name: {0}", AudioDevice.Name),
                "CoreAudip API", MessageBoxButtons.OK, MessageBoxIcon.Information)

' Get a value indicating whether the Device is muted:
' ###################################################
MessageBox.Show(String.Format("Device Is Muted?: {0}", CStr(AudioDevice.IsMuted)),
                "CoreAudip API", MessageBoxButtons.OK, MessageBoxIcon.Information)

' Mute the device:
' ################
AudioDevice.Mute()

' Unmute the device:
' ##################
AudioDevice.Unmute()

' Set the master-volume:
' ######################
AudioDevice.Volume = 50I

' Get the channel count:
' ######################
MessageBox.Show(String.Format("Device Total Channels: {0}", AudioDevice.ChannelsCount),
                "CoreAudip API", MessageBoxButtons.OK, MessageBoxIcon.Information)

' Set the volume for an specific channel:
' #######################################
AudioDevice.ChannelVolumeSet(MasterVolume.DeviceChannel.Channel0, 50I)

' Set the volume for all channels:
' ################################
AudioDevice.ChannelVolumeSetAll(50I)

' Get the volume of an specific channel:
' ######################################
MessageBox.Show(String.Format("Channel: 0, Volume: {0}",
                              AudioDevice.ChannelVolumeGet(MasterVolume.DeviceChannel.Channel0)),
                "CoreAudip API", MessageBoxButtons.OK, MessageBoxIcon.Information)

' Get the volume of all channels:
' ###############################
Dim ChannelsInfo As Dictionary(Of MasterVolume.DeviceChannel, Integer) = AudioDevice.ChannelVolumeGetAll

Dim sb As New System.Text.StringBuilder

With sb
    For Each Channel As KeyValuePair(Of MasterVolume.DeviceChannel, Integer) In ChannelsInfo
        .AppendLine(String.Format("Channel: {0}, Volume: {1}", CStr(Channel.Key), CStr(Channel.Value)))
    Next
End With

MessageBox.Show(sb.ToString(), "CoreAudip API", MessageBoxButtons.OK, MessageBoxIcon.Information)

' Lock the audio device:
' ######################
AudioDevice.LockDevice()

' Unlock the audio device:
' ########################
AudioDevice.UnlockDevice()

Private Sub AudioDevice_OnMutedChanged(ByVal sender As Object, ByVal e As MasterVolume.MuteArgs) _
Handles AudioDevice.OnMutedChanged

    ' Do something here...
    Debug.WriteLine(String.Format("Device Muted changed to: {0}", CStr(e.IsMuted)))

End Sub

Private Sub AudioDevice_OnVolumeChanged(ByVal sender As Object, ByVal e As MasterVolume.MasterVolumeArgs) _
Handles AudioDevice.OnMasterVolumeChanged

    ' Do something here...
    Debug.WriteLine(String.Format("Device Master-Volume changed to: {0}", CStr(e.Volume)))

End Sub

Private Sub AudioDevice_OnVolumeChanged(ByVal sender As Object, ByVal e As MasterVolume.ChannelVolumeArgs) _
Handles AudioDevice.OnChannelVolumeChanged

    ' Do something here...
    Debug.WriteLine(String.Format("Device volume in channel '{0}' changed to: {1}", e.Channel.ToString(), CStr(e.Volume)))

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio Namespace</a><br />