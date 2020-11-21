# NativeMethods.SHDoDragDrop Method 
 

Executes a drag-and-drop operation. Supports drag source creation on demand, as well as drag images.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll")]
public static HResult SHDoDragDrop(
	IntPtr hWnd,
	IDataObject dataObject,
	[OptionalAttribute] IDropSource dropSource,
	DragDropEffects effect,
	ref DragDropEffects refEffect
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll">]
Public Shared Function SHDoDragDrop ( 
	hWnd As IntPtr,
	dataObject As IDataObject,
	<OptionalAttribute> dropSource As IDropSource,
	effect As DragDropEffects,
	ByRef refEffect As DragDropEffects
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim dataObject As IDataObject
Dim dropSource As IDropSource
Dim effect As DragDropEffects
Dim refEffect As DragDropEffects
Dim returnValue As HResult

returnValue = NativeMethods.SHDoDragDrop(hWnd, 
	dataObject, dropSource, effect, refEffect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll")]
static HResult SHDoDragDrop(
	IntPtr hWnd, 
	IDataObject^ dataObject, 
	[OptionalAttribute] IDropSource^ dropSource, 
	DragDropEffects effect, 
	DragDropEffects% refEffect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll")>]
static member SHDoDragDrop : 
        hWnd : IntPtr * 
        dataObject : IDataObject * 
        [<OptionalAttribute>] dropSource : IDropSource * 
        effect : DragDropEffects * 
        refEffect : DragDropEffects byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />The handle of the window used to obtain the drag image. This value can be Zero.</dd><dt>dataObject</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IDataObject<br />A IDataObject interface on a data object that contains the data being dragged.</dd><dt>dropSource (Optional)</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IDropSource">DevCase.Interop.Unmanaged.Win32.Interfaces.IDropSource</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IDropSource">IDropSource</a> interface, which is used to communicate with the source during the drag operation. If this value is a null reference (`Nothing` in Visual Basic), the shell creates a drop source object for you.</dd><dt>effect</dt><dd>Type: System.Windows.Forms.DragDropEffects<br />The effects that the source allows in the drag-and-drop operation. The most significant effect is whether the drag-and-drop operation permits a move. For a list of possible values, see DROPEFFECT.</dd><dt>refEffect</dt><dd>Type: System.Windows.Forms.DragDropEffects<br />A value that indicates how the drag-and-drop operation affected the source data. 

 The parameter is set only if the operation is not canceled.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the drag-and-drop operation was successful, returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">DRAGDROP_S_DROP</a>. 

 If the drag-and-drop operation was canceled, returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">DRAGDROP_S_CANCEL</a>. 

 If an error occurs, returns a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shdodragdrop" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shdodragdrop</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />