# DevCase.Interop.Unmanaged.Win32.Interfaces Namespace
 




## Classes
&nbsp;<table><tr><th></th><th>Class</th><th>Description</th></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ActiveDesktop">ActiveDesktop</a></td><td></td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_COpenControlPanel">COpenControlPanel</a></td><td>
`CLSID_OpenControlPanel` from `Shobjidl.h` headers.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_CShellLink">CShellLink</a></td><td>
`CLSID_ShellLink` from `ShlGuid.h` headers.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_CTaskbarList">CTaskbarList</a></td><td>
`CLSID_TaskbarList` from `shobjidl.h` headers.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_MMDeviceEnumerator">MMDeviceEnumerator</a></td><td>
`CLSID_MMDeviceEnumerator`.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ProgressDialog">ProgressDialog</a></td><td /></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_TaskbarList">TaskbarList</a></td><td>
Provides internal access to the functions provided by the ITaskbarList4 interface, without being forced to refer to it through another singleton.</td></tr></table>

## Interfaces
&nbsp;<table><tr><th></th><th>Interface</th><th>Description</th></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IActiveDesktop">IActiveDesktop</a></td><td>
Allows a client program to manage the desktop items and wallpaper on a local computer.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAssemblyCache">IAssemblyCache</a></td><td>
Represents the global assembly cache for use by the fusion technology.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl">IAudioSessionControl</a></td><td>
Enables a client to configure the control parameters for an audio session and to monitor events in the session. 

 The IAudioClient.Initialize method initializes a stream object and assigns the stream to an audio session.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl2">IAudioSessionControl2</a></td><td>
Enables a client to configure the control parameters for an audio session and to monitor events in the session. 

 The IAudioClient.Initialize method initializes a stream object and assigns the stream to an audio session.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEnumerator">IAudioSessionEnumerator</a></td><td>
Enumerates audio sessions on an audio device.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents">IAudioSessionEvents</a></td><td>
Provides notifications of session-related events such as changes in the volume level, display name, and session state. 

 Unlike the other interfaces in this section, which are implemented by the WASAPI system component, a WASAPI client implements the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents">IAudioSessionEvents</a> interface. 

 To receive event notifications, the client passes a pointer to its <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEvents">IAudioSessionEvents</a> interface to the <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionControl_RegisterAudioSessionNotification">RegisterAudioSessionNotification(IAudioSessionEvents)</a> function.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager">IAudioSessionManager</a></td><td>
Enables a client to access the session controls and volume controls for both cross-process and process-specific audio sessions.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager2">IAudioSessionManager2</a></td><td>
Enables an application to manage submixes for the audio device.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionNotification">IAudioSessionNotification</a></td><td>
Provides notification when an audio session is created.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioVolumeDuckNotification">IAudioVolumeDuckNotification</a></td><td>
Provides notification about stream attenuation changes. Stream Attenuation, or ducking.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName</a></td><td>
Provides basic global static functions for signing assemblies with strong names.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IDropSource">IDropSource</a></td><td>
The <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IDropSource">IDropSource</a> interface is one of the interfaces you implement to provide drag-and-drop operations in your application. 

 It contains methods used in any application used as a data source in a drag-and-drop operation. The data source application in a drag-and-drop operation is responsible for: 

 - Determining the data being dragged based on the user's selection. 

 - Initiating the drag-and-drop operation based on the user's mouse actions. 

 - Generating some of the visual feedback during the drag-and-drop operation, such as setting the cursor and highlighting the data selected for the drag-and-drop operation. 

 - Canceling or completing the drag-and-drop operation based on the user's mouse actions. 

 - Performing any action on the original data caused by the drop operation, such as deleting the data on a drag move.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IEnumIDList">IEnumIDList</a></td><td>
Exposes a standard set of methods used to enumerate the pointers to item identifier lists (PIDLs) of the items in a Shell folder. 

 When a folder's <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder_EnumObjects">EnumObjects(IntPtr, ShellFolderEnumObjectsFlags)</a> method is called, it creates an enumeration object and passes a pointer to the object's <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IEnumIDList">IEnumIDList</a> interface back to the calling application.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice">IMMDevice</a></td><td>
Provides methods for enumerating multimedia device resources. 

 In the current implementation of the MMDevice API, the only device resources that this interface can enumerate are audio endpoint devices. 

 A client obtains a reference to an <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator">IMMDeviceEnumerator</a> interface by calling the CoCreateInstance. 

 The device resources enumerated by the methods in the IMMDeviceEnumerator interface are represented as collections of objects with <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice">IMMDevice</a> interfaces. 

 A collection has an IMMDeviceCollection interface. The IMMDeviceEnumerator.EnumAudioEndpoints method creates a device collection.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceCollection">IMMDeviceCollection</a></td><td>
Represents a collection of multimedia device resources. 

 In the current implementation, the only device resources that the MMDevice API can create collections of are audio endpoint devices.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator">IMMDeviceEnumerator</a></td><td>
Provides methods for enumerating multimedia device resources. 

 In the current implementation of the MMDevice API, the only device resources that this interface can enumerate are audio endpoint devices. 

 A client obtains a reference to an <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator">IMMDeviceEnumerator</a> interface by calling the CoCreateInstance. 

 The device resources enumerated by the methods in the IMMDeviceEnumerator interface are represented as collections of objects with <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice">IMMDevice</a> interfaces. 

 A collection has an IMMDeviceCollection interface. The IMMDeviceEnumerator.EnumAudioEndpoints method creates a device collection.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMNotificationClient">IMMNotificationClient</a></td><td>
Provides notifications when an audio endpoint device is added or removed, when the state or properties of an endpoint device change, or when there is a change in the default role assigned to an endpoint device. 

 Unlike the other interfaces in this section, which are implemented by the MMDevice API system component, an MMDevice API client implements the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMNotificationClient">IMMNotificationClient</a> interface. 

 To receive notifications, the client passes a pointer to its <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMNotificationClient">IMMNotificationClient</a> interface instance as a parameter to the <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDeviceEnumerator_RegisterEndpointNotificationCallback">RegisterEndpointNotificationCallback(IMMNotificationClient)</a> method.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IOpenControlPanel">IOpenControlPanel</a></td><td>
Exposes methods that retrieve the view state of the Control Panel, the path of individual Control Panel items, and that open either the Control Panel itself or an individual Control Panel item.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersist">IPersist</a></td><td>
Provides the CLSID of an object that can be stored persistently in the system. 

 Allows the object to specify which object handler to use in the client process, as it is used in the default implementation of marshaling.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile">IPersistFile</a></td><td>
Enables an object to be loaded from or saved to a disk file, rather than a storage object or stream. 

 Because the information needed to open a file varies greatly from one application to another, the implementation of <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_Load">Load(String, UInt32)</a> on the object must also open its disk file.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog">IProgressDialog</a></td><td>
Exposes methods that provide options for an application to display a progress dialog box. 

 This interface is exported by the progress dialog box object (CLSID_ProgressDialog). 

 This object is a generic way to show a user how an operation is progressing. 

 It is typically used when deleting, uploading, copying, moving, or downloading large numbers of files.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPropertyStore">IPropertyStore</a></td><td>
Exposes methods for enumerating, getting, and setting property values.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap</a></td><td>
Exposes memory-efficient methods for accessing bitmaps. 

 This interface is used as a thin wrapper around HBITMAP objects, allowing those objects to be reference counted and protected from having their underlying data changed.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder</a></td><td>
Exposed by all Shell namespace folder objects, its methods are used to manage folders.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem</a></td><td>
Exposes a method to return either icons or thumbnails for Shell items. 

 If no thumbnail or icon is available for the requested item, a per-class icon may be provided from the Shell</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItemImageFactory">IShellItemImageFactory</a></td><td>
Exposes a method to return either icons or thumbnails for Shell items. 

 If no thumbnail or icon is available for the requested item, a per-class icon may be provided from the Shell</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW</a></td><td>
The `IShellLink` interface allows Shell links to be created, modified, or resolved.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISimpleAudioVolume">ISimpleAudioVolume</a></td><td>
Enables a client to control the master volume level of an audio session. 

 The IAudioClient.Initialize method initializes a stream object and assigns the stream to an audio session.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ITaskbarList4">ITaskbarList4</a></td><td>
Exposes methods that control the taskbar.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IThumbnailCache">IThumbnailCache</a></td><td>
Exposes methods for a system thumbnail cache that is shared across applications.</td></tr></table>&nbsp;
