# IAudioSessionNotification Interface
 

Provides notification when an audio session is created.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("641DD20B-4D41-49CC-ABA3-174B9477BB08")]
public interface IAudioSessionNotification
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("641DD20B-4D41-49CC-ABA3-174B9477BB08")>
Public Interface IAudioSessionNotification
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionNotification
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"641DD20B-4D41-49CC-ABA3-174B9477BB08")]
public interface class IAudioSessionNotification
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("641DD20B-4D41-49CC-ABA3-174B9477BB08")>]
type IAudioSessionNotification =  interface end
```

The IAudioSessionNotification type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionNotification_OnSessionCreated">OnSessionCreated</a></td><td>
Notifies the registered processes that the audio session has been created.</td></tr></table>&nbsp;
<a href="#iaudiosessionnotification-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nn-audiopolicy-iaudiosessionnotification" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nn-audiopolicy-iaudiosessionnotification</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />