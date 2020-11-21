# AestheticEventArgs Class
 

This is a class to consume for aesthetic purposes. 

 A default (emptyness) class that inherits from EventArgs, with these base members hidden: 

GetHashCode(), GetType(), Equals(Object), Equals(Object, Object), ReferenceEquals(Object, Object), ToString().


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.EventArgs<br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Design.AestheticEventArgs<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#inheritance-hierarchy">More...</a>
**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComVisibleAttribute(true)]
public abstract class AestheticEventArgs : EventArgs
```

**VB**<br />
``` VB
<ComVisibleAttribute(true)>
Public MustInherit Class AestheticEventArgs
	Inherits EventArgs
```

**VB Usage**<br />
``` VB Usage
Dim instance As AestheticEventArgs
```

**C++**<br />
``` C++
[ComVisibleAttribute(true)]
public ref class AestheticEventArgs abstract : public EventArgs
```

**F#**<br />
``` F#
[<AbstractClassAttribute>]
[<ComVisibleAttribute(true)>]
type AestheticEventArgs =  
    class
        inherit EventArgs
    end
```

The AestheticEventArgs type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Design_AestheticEventArgs__ctor">AestheticEventArgs</a></td><td>
Initializes a new instance of the AestheticEventArgs class.</td></tr></table>&nbsp;
<a href="#aestheticeventargs-class">Back to Top</a>

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
<a href="#aestheticeventargs-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />

## Inheritance HierarchySystem.Object<br />&nbsp;&nbsp;System.EventArgs<br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Design.AestheticEventArgs<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_Eventing_ColorChangedEventArgs">DevCase.Controls.Eventing.ColorChangedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_Eventing_ItemAddedEventArgs_1">DevCase.Controls.Eventing.ItemAddedEventArgs(T)</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_Eventing_ItemRemovedEventArgs_1">DevCase.Controls.Eventing.ItemRemovedEventArgs(T)</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Controls_Eventing_ValueChangedEventArgs_1">DevCase.Controls.Eventing.ValueChangedEventArgs(T)</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Application_Eventing_CommandLineArgumentsEventArgs">DevCase.Core.Application.Eventing.CommandLineArgumentsEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Application_Eventing_HotkeyPressEventArgs">DevCase.Core.Application.Eventing.HotkeyPressEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Application_UserInterface_Eventing_MenuItemClickedEventArgs">DevCase.Core.Application.UserInterface.Eventing.MenuItemClickedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_DateAndTime_Eventing_TimeMeasurerUpdatedEventArgs">DevCase.Core.DateAndTime.Eventing.TimeMeasurerUpdatedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Diagnostics_Eventing_ProcessMonitorEventArgs">DevCase.Core.Diagnostics.Eventing.ProcessMonitorEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Imaging_Eventing_RegionSelectedEventArgs">DevCase.Core.Imaging.Eventing.RegionSelectedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_IO_Eventing_DriveStatusChangedEventArgs">DevCase.Core.IO.Eventing.DriveStatusChangedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_IO_Eventing_FileCopyProgressChangedEventArgs">DevCase.Core.IO.Eventing.FileCopyProgressChangedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_IO_Eventing_FileSplitterProgressChangedEventArgs">DevCase.Core.IO.Eventing.FileSplitterProgressChangedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_IO_Eventing_HotkeyPastePressedEventArgs">DevCase.Core.IO.Eventing.HotkeyPastePressedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_IO_Eventing_KeyPressedEventArgs">DevCase.Core.IO.Eventing.KeyPressedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_IO_Eventing_MouseButtonClickEventArgs">DevCase.Core.IO.Eventing.MouseButtonClickEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_IO_Eventing_MouseButtonDoubleClickEventArgs">DevCase.Core.IO.Eventing.MouseButtonDoubleClickEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_IO_Eventing_MouseMoveEventArgs">DevCase.Core.IO.Eventing.MouseMoveEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_IO_Eventing_MouseWheelScrollEventArgs">DevCase.Core.IO.Eventing.MouseWheelScrollEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_NET_Eventing_MailMessageArrivedEventArgs">DevCase.Core.NET.Eventing.MailMessageArrivedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_NET_Eventing_NetworkStatusChangedEventArgs">DevCase.Core.NET.Eventing.NetworkStatusChangedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_NET_Eventing_TrafficChangedEventArgs">DevCase.Core.NET.Eventing.TrafficChangedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Shell_Eventing_BatteryStatusChangedEventArgs">DevCase.Core.Shell.Eventing.BatteryStatusChangedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterExitedEventArgs">DevCase.ThirdParty.DBpoweramp.Eventing.CoreConverterExitedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterProgressEventArgs">DevCase.ThirdParty.DBpoweramp.Eventing.CoreConverterProgressEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterStartedEventArgs">DevCase.ThirdParty.DBpoweramp.Eventing.CoreConverterStartedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegExitedEventArgs">DevCase.ThirdParty.Ffmpeg.Eventing.FfmpegExitedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegProgressEventArgs">DevCase.ThirdParty.Ffmpeg.Eventing.FfmpegProgressEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegStartedEventArgs">DevCase.ThirdParty.Ffmpeg.Eventing.FfmpegStartedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_FHM_Eventing_PageCrawlBeginEventArgs">DevCase.ThirdParty.FHM.Eventing.PageCrawlBeginEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_FHM_Eventing_PageCrawlEndEventArgs">DevCase.ThirdParty.FHM.Eventing.PageCrawlEndEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_Imgur_Eventing_UploadCompletedEventArgs">DevCase.ThirdParty.Imgur.Eventing.UploadCompletedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_Imgur_Eventing_UploadErrorEventArgs">DevCase.ThirdParty.Imgur.Eventing.UploadErrorEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_MkvToolnix_Eventing_MkvMergeExitedEventArgs">DevCase.ThirdParty.MkvToolnix.Eventing.MkvMergeExitedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_MkvToolnix_Eventing_MkvMergeStartedEventArgs">DevCase.ThirdParty.MkvToolnix.Eventing.MkvMergeStartedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainExitedEventArgs">DevCase.ThirdParty.MP3Gain.Eventing.MP3GainExitedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainProgressChangedEventArgs">DevCase.ThirdParty.MP3Gain.Eventing.MP3GainProgressChangedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainStartedEventArgs">DevCase.ThirdParty.MP3Gain.Eventing.MP3GainStartedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_MP3Val_Eventing_MP3ValExitedEventArgs">DevCase.ThirdParty.MP3Val.Eventing.MP3ValExitedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_MP3Val_Eventing_MP3ValStartedEventArgs">DevCase.ThirdParty.MP3Val.Eventing.MP3ValStartedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_ResHacker_Eventing_ResHackerExitedEventArgs">DevCase.ThirdParty.ResHacker.Eventing.ResHackerExitedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_ResHacker_Eventing_ResHackerStartedEventArgs">DevCase.ThirdParty.ResHacker.Eventing.ResHackerStartedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_SetAcl_Eventing_SetAclExitedEventArgs">DevCase.ThirdParty.SetAcl.Eventing.SetAclExitedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_SetAcl_Eventing_SetAclStartedEventArgs">DevCase.ThirdParty.SetAcl.Eventing.SetAclStartedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_VistaCoreAudio_Eventing_ChannelVolumeChangedEventArgs">DevCase.ThirdParty.VistaCoreAudio.Eventing.ChannelVolumeChangedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_VistaCoreAudio_Eventing_MasterVolumeChangedEventArgs">DevCase.ThirdParty.VistaCoreAudio.Eventing.MasterVolumeChangedEventArgs</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_VistaCoreAudio_Eventing_MutedChangedEventArgs">DevCase.ThirdParty.VistaCoreAudio.Eventing.MutedChangedEventArgs</a><br />