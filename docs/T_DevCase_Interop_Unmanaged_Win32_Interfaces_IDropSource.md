# IDropSource Interface
 

The IDropSource interface is one of the interfaces you implement to provide drag-and-drop operations in your application. 

 It contains methods used in any application used as a data source in a drag-and-drop operation. The data source application in a drag-and-drop operation is responsible for: 

 - Determining the data being dragged based on the user's selection. 

 - Initiating the drag-and-drop operation based on the user's mouse actions. 

 - Generating some of the visual feedback during the drag-and-drop operation, such as setting the cursor and highlighting the data selected for the drag-and-drop operation. 

 - Canceling or completing the drag-and-drop operation based on the user's mouse actions. 

 - Performing any action on the original data caused by the drop operation, such as deleting the data on a drag move.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[GuidAttribute("00000121-0000-0000-C000-000000000046")]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
public interface IDropSource
```

**VB**<br />
``` VB
<ComImportAttribute>
<GuidAttribute("00000121-0000-0000-C000-000000000046")>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
Public Interface IDropSource
```

**VB Usage**<br />
``` VB Usage
Dim instance As IDropSource
```

**C++**<br />
``` C++
[ComImportAttribute]
[GuidAttribute(L"00000121-0000-0000-C000-000000000046")]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
public interface class IDropSource
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<GuidAttribute("00000121-0000-0000-C000-000000000046")>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
type IDropSource =  interface end
```

The IDropSource type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IDropSource_GiveFeedback">GiveFeedback</a></td><td>
Enables a source application to give visual feedback to the end user during a drag-and-drop operation by providing the DoDragDrop function with an enumeration value specifying the visual effect.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IDropSource_QueryContinueDrag">QueryContinueDrag</a></td><td>
Determines whether a drag-and-drop operation should be continued, canceled, or completed. 

 You do not call this method directly. The OLE DoDragDrop function calls this method during a drag-and-drop operation.</td></tr></table>&nbsp;
<a href="#idropsource-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/oleidl/nn-oleidl-idropsource" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/oleidl/nn-oleidl-idropsource</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />