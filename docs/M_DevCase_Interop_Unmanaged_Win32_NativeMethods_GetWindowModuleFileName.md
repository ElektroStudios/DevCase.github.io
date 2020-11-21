# NativeMethods.GetWindowModuleFileName Method (IntPtr, StringBuilder, UInt32)
 

Retrieves the full path and file name of the module associated with the specified window handle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static uint GetWindowModuleFileName(
	IntPtr hWnd,
	StringBuilder fileName,
	uint fileNameMax
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function GetWindowModuleFileName ( 
	hWnd As IntPtr,
	fileName As StringBuilder,
	fileNameMax As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim fileName As StringBuilder
Dim fileNameMax As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetWindowModuleFileName(hWnd, 
	fileName, fileNameMax)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static unsigned int GetWindowModuleFileName(
	IntPtr hWnd, 
	StringBuilder^ fileName, 
	unsigned int fileNameMax
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member GetWindowModuleFileName : 
        hWnd : IntPtr * 
        fileName : StringBuilder * 
        fileNameMax : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window whose module file name is to be retrieved.</dd><dt>fileName</dt><dd>Type: System.Text.StringBuilder<br />The path and file name.</dd><dt>fileNameMax</dt><dd>Type: System.UInt32<br />The maximum number of characters that can be copied into the *fileName* buffer.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getwindowmodulefilenamea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getwindowmodulefilenamea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowModuleFileName">GetWindowModuleFileName Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />