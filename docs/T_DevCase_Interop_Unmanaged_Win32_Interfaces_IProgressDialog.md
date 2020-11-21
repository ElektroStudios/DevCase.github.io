# IProgressDialog Interface
 

Exposes methods that provide options for an application to display a progress dialog box. 

 This interface is exported by the progress dialog box object (CLSID_ProgressDialog). 

 This object is a generic way to show a user how an operation is progressing. 

 It is typically used when deleting, uploading, copying, moving, or downloading large numbers of files.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[GuidAttribute("EBBC7C04-315E-11d2-B62F-006097DF5BD4")]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
public interface IProgressDialog
```

**VB**<br />
``` VB
<ComImportAttribute>
<GuidAttribute("EBBC7C04-315E-11d2-B62F-006097DF5BD4")>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
Public Interface IProgressDialog
```

**VB Usage**<br />
``` VB Usage
Dim instance As IProgressDialog
```

**C++**<br />
``` C++
[ComImportAttribute]
[GuidAttribute(L"EBBC7C04-315E-11d2-B62F-006097DF5BD4")]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
public interface class IProgressDialog
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<GuidAttribute("EBBC7C04-315E-11d2-B62F-006097DF5BD4")>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
type IProgressDialog =  interface end
```

The IProgressDialog type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog_HasUserCancelled">HasUserCancelled</a></td><td>
Checks whether the user has canceled the operation.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog_SetAnimation">SetAnimation</a></td><td>
Specifies an Audio-Video Interleaved (AVI) clip that runs in the dialog box. 

 Note: Note This method is not supported in Windows Vista or later versions.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog_SetCancelMsg">SetCancelMsg</a></td><td>
Sets a message to be displayed if the user cancels the operation.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog_SetLine">SetLine</a></td><td>
Displays a message in the progress dialog.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog_SetProgress">SetProgress</a></td><td>
Updates the progress dialog box with the current state of the operation.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog_SetProgress64">SetProgress64</a></td><td>
Updates the progress dialog box with the current state of the operation.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog_SetTitle">SetTitle</a></td><td>
Sets the title of the progress dialog box.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog_StartProgressDialog">StartProgressDialog</a></td><td>
Starts the progress dialog box.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog_StopProgressDialog">StopProgressDialog</a></td><td>
Stops the progress dialog box and removes it from the screen.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog_Timer">Timer</a></td><td>
Resets the progress dialog box timer to zero.</td></tr></table>&nbsp;
<a href="#iprogressdialog-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nn-shlobj_core-iprogressdialog" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nn-shlobj_core-iprogressdialog</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />