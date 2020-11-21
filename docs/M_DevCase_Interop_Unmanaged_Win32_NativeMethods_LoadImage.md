# NativeMethods.LoadImage Method 
 

Loads an icon, cursor, animated cursor, or bitmap.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static IntPtr LoadImage(
	IntPtr hInstance,
	string name,
	LoadImageType type,
	int width,
	int height,
	LoadImageFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Unicode, SetLastError := true>]
Public Shared Function LoadImage ( 
	hInstance As IntPtr,
	name As String,
	type As LoadImageType,
	width As Integer,
	height As Integer,
	flags As LoadImageFlags
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hInstance As IntPtr
Dim name As String
Dim type As LoadImageType
Dim width As Integer
Dim height As Integer
Dim flags As LoadImageFlags
Dim returnValue As IntPtr

returnValue = NativeMethods.LoadImage(hInstance, 
	name, type, width, height, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Unicode, SetLastError = true)]
static IntPtr LoadImage(
	IntPtr hInstance, 
	String^ name, 
	LoadImageType type, 
	int width, 
	int height, 
	LoadImageFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Unicode, SetLastError = true)>]
static member LoadImage : 
        hInstance : IntPtr * 
        name : string * 
        type : LoadImageType * 
        width : int * 
        height : int * 
        flags : LoadImageFlags -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hInstance</dt><dd>Type: System.IntPtr<br />A handle to the module of either a DLL or executable (.exe) that contains the image to be loaded. 

 Note that as of 32-bit Windows, an instance handle (`HINSTANCE`), such as the application instance handle exposed by system function call of WinMain, and a module handle (`HMODULE`) are the same thing. 

 To load a stand-alone resource (icon, cursor, or bitmap file), like for example `c:\myimage.bmp`, set this parameter to Zero.</dd><dt>name</dt><dd>Type: System.String<br />The image to be loaded. 

 If the *hInstance* parameter is non-Zero and the *flags* parameter omits <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_LoadImageFlags">LoadFromFile</a>, *name* specifies the image resource in the *hInstance* module. 

 If the image resource is to be loaded by name from the module, the *name* parameter is a pointer to a null-terminated string that contains the name of the image resource. 

 If the image resource is to be loaded by ordinal from the module, use the `MAKEINTRESOURCE` macro to convert the image ordinal into a form that can be passed to the LoadImage(IntPtr, String, LoadImageType, Int32, Int32, LoadImageFlags) function. 



 If the *flags* parameter includes the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_LoadImageFlags">LoadFromFile</a> value, *name* is the name of the file that contains the stand-alone resource (icon, cursor, or bitmap file). 

 Therefore, set hinst to a null reference (`Nothing` in Visual Basic).</dd><dt>type</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_LoadImageType">DevCase.Interop.Unmanaged.Win32.Enums.LoadImageType</a><br />The type of image to be loaded.</dd><dt>width</dt><dd>Type: System.Int32<br />The width, in pixels, of the icon or cursor. 

 If this parameter is zero and the fuLoad parameter is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_LoadImageFlags">DefaultSize</a>, the function uses the `SM_CXICON` or `SM_CXCURSOR` system metric value to set the width. 

 If this parameter is zero and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_LoadImageFlags">DefaultSize</a> is not used, the function uses the actual resource width.</dd><dt>height</dt><dd>Type: System.Int32<br />The height, in pixels, of the icon or cursor. 

 If this parameter is zero and the fuLoad parameter is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_LoadImageFlags">DefaultSize</a>, the function uses the `SM_CYICON` or `SM_CYCURSOR` system metric value to set the height. 

 If this parameter is zero and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_LoadImageFlags">DefaultSize</a> is not used, the function uses the actual resource height.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_LoadImageFlags">DevCase.Interop.Unmanaged.Win32.Enums.LoadImageFlags</a><br />Flags that determines how the image is loaded.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the handle of the newly loaded image. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648045%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648045%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />