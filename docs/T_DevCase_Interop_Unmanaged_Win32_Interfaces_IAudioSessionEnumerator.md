# IAudioSessionEnumerator Interface
 

Enumerates audio sessions on an audio device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("E2F5BB11-0570-40CA-ACDD-3AA01277DEE8")]
public interface IAudioSessionEnumerator
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("E2F5BB11-0570-40CA-ACDD-3AA01277DEE8")>
Public Interface IAudioSessionEnumerator
```

**VB Usage**<br />
``` VB Usage
Dim instance As IAudioSessionEnumerator
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"E2F5BB11-0570-40CA-ACDD-3AA01277DEE8")]
public interface class IAudioSessionEnumerator
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("E2F5BB11-0570-40CA-ACDD-3AA01277DEE8")>]
type IAudioSessionEnumerator =  interface end
```

The IAudioSessionEnumerator type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEnumerator_GetCount">GetCount</a></td><td>
Gets the total number of audio sessions that are open on the audio device.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionEnumerator_GetSession">GetSession</a></td><td>
Notifies the client that the display name for the session has changed.</td></tr></table>&nbsp;
<a href="#iaudiosessionenumerator-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nn-audiopolicy-iaudiosessionenumerator" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/audiopolicy/nn-audiopolicy-iaudiosessionenumerator</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />