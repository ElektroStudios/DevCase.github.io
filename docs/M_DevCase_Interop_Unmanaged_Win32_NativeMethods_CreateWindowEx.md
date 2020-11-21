# NativeMethods.CreateWindowEx Method 
 

Creates an overlapped, pop-up, or child window with an extended window style.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr CreateWindowEx(
	WindowStylesEx exStyle,
	string className,
	string windowName,
	WindowStyles style,
	int x,
	int y,
	int width,
	int height,
	[OptionalAttribute] IntPtr hWndParent,
	[OptionalAttribute] IntPtr hMenu,
	IntPtr hInstance,
	[OptionalAttribute] IntPtr param
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function CreateWindowEx ( 
	exStyle As WindowStylesEx,
	className As String,
	windowName As String,
	style As WindowStyles,
	x As Integer,
	y As Integer,
	width As Integer,
	height As Integer,
	<OptionalAttribute> hWndParent As IntPtr,
	<OptionalAttribute> hMenu As IntPtr,
	hInstance As IntPtr,
	<OptionalAttribute> param As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim exStyle As WindowStylesEx
Dim className As String
Dim windowName As String
Dim style As WindowStyles
Dim x As Integer
Dim y As Integer
Dim width As Integer
Dim height As Integer
Dim hWndParent As IntPtr
Dim hMenu As IntPtr
Dim hInstance As IntPtr
Dim param As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateWindowEx(exStyle, 
	className, windowName, style, x, y, 
	width, height, hWndParent, hMenu, 
	hInstance, param)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr CreateWindowEx(
	WindowStylesEx exStyle, 
	String^ className, 
	String^ windowName, 
	WindowStyles style, 
	int x, 
	int y, 
	int width, 
	int height, 
	[OptionalAttribute] IntPtr hWndParent, 
	[OptionalAttribute] IntPtr hMenu, 
	IntPtr hInstance, 
	[OptionalAttribute] IntPtr param
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member CreateWindowEx : 
        exStyle : WindowStylesEx * 
        className : string * 
        windowName : string * 
        style : WindowStyles * 
        x : int * 
        y : int * 
        width : int * 
        height : int * 
        [<OptionalAttribute>] hWndParent : IntPtr * 
        [<OptionalAttribute>] hMenu : IntPtr * 
        hInstance : IntPtr * 
        [<OptionalAttribute>] param : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>exStyle</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowStylesEx">DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx</a><br />The extended window style of the window being created.</dd><dt>className</dt><dd>Type: System.String<br />A null-terminated string or a class atom created by a previous call to the RegisterClass or RegisterClassEx function. 

 The atom must be in the low-order word of *className*; the high-order word must be zero. 

 If *className* is a string, it specifies the window class name. 

 The class name can be any name registered with RegisterClass or RegisterClassEx, provided that the module that registers the class is also the module that creates the window. 

 The class name can also be any of the predefined system class names.</dd><dt>windowName</dt><dd>Type: System.String<br />The window name. 

 If the window style specifies a title bar, the window title pointed to by lpWindowName is displayed in the title bar. 

 When using CreateWindowEx(WindowStylesEx, String, String, WindowStyles, Int32, Int32, Int32, Int32, IntPtr, IntPtr, IntPtr, IntPtr) to create controls, such as buttons, check boxes, and static controls, use *windowName* to specify the text of the control. 

 When creating a static control with the SS_ICON style, use *windowName* to specify the icon name or identifier. 

 To specify an identifier, use the syntax "#num".</dd><dt>style</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowStyles">DevCase.Interop.Unmanaged.Win32.Enums.WindowStyles</a><br />The style of the window being created.</dd><dt>x</dt><dd>Type: System.Int32<br />The initial horizontal position of the window. 

 For an overlapped or pop-up window, the x parameter is the initial x-coordinate of the window's upper-left corner, in screen coordinates. 

 For a child window, x is the x-coordinate of the upper-left corner of the window relative to the upper-left corner of the parent window's client area. 

 If x is set to CW_USEDEFAULT, the system selects the default position for the window's upper-left corner and ignores the y parameter. 

 CW_USEDEFAULT is valid only for overlapped windows; if it is specified for a pop-up or child window, the x and y parameters are set to zero.</dd><dt>y</dt><dd>Type: System.Int32<br />The initial vertical position of the window. 

 For an overlapped or pop-up window, the y parameter is the initial y-coordinate of the window's upper-left corner, in screen coordinates. 

 For a child window, y is the initial y-coordinate of the upper-left corner of the child window relative to the upper-left corner of the parent window's client area. 

 For a list box y is the initial y-coordinate of the upper-left corner of the list box's client area relative to the upper-left corner of the parent window's client area. 

 If an overlapped window is created with the WS_VISIBLE style bit set and the x parameter is set to CW_USEDEFAULT, then the y parameter determines how the window is shown. 

 If the y parameter is CW_USEDEFAULT, then the window manager calls ShowWindow with the SW_SHOW flag after the window has been created. 

 If the y parameter is some other value, then the window manager calls <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ShowWindow">ShowWindow(IntPtr, NativeWindowState)</a> with that value as the `windowState` (`nCmdShow`) parameter.</dd><dt>width</dt><dd>Type: System.Int32<br />The width, in device units, of the window. 

 For overlapped windows, nWidth is the window's width, in screen coordinates, or CW_USEDEFAULT. 

 If *width* is CW_USEDEFAULT, the system selects a default width and height for the window; the default width extends from the initial x-coordinates to the right edge of the screen; the default height extends from the initial y-coordinate to the top of the icon area. 

 CW_USEDEFAULT is valid only for overlapped windows; if CW_USEDEFAULT is specified for a pop-up or child window, the nWidth and nHeight parameter are set to zero.</dd><dt>height</dt><dd>Type: System.Int32<br />The height, in device units, of the window. 

 For overlapped windows, nHeight is the window's height, in screen coordinates. 

 If the *width* parameter is set to CW_USEDEFAULT, the system ignores nHeight.</dd><dt>hWndParent (Optional)</dt><dd>Type: System.IntPtr<br />A handle to the parent or owner window of the window being created. 

 To create a child window or an owned window, supply a valid window handle. 

 This parameter is optional for pop-up windows. 

 To create a message-only window, supply HWND_MESSAGE or a handle to an existing message-only window.</dd><dt>hMenu (Optional)</dt><dd>Type: System.IntPtr<br />A handle to a menu, or specifies a child-window identifier, depending on the window style. 

 For an overlapped or pop-up window, *hMenu* identifies the menu to be used with the window; it can be NULL if the class menu is to be used. 

 For a child window, *hMenu* specifies the child-window identifier, an integer value used by a dialog box control to notify its parent about events. 

 The application determines the child-window identifier; it must be unique for all child windows with the same parent window.</dd><dt>hInstance</dt><dd>Type: System.IntPtr<br />A handle to the instance of the module to be associated with the window.</dd><dt>param (Optional)</dt><dd>Type: System.IntPtr<br />Pointer to a value to be passed to the window through the CREATESTRUCT structure (lpCreateParams member) pointed to by the lParam param of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Create</a> message. This message is sent to the created window by this function before it returns. 

 If an application calls CreateWindowEx(WindowStylesEx, String, String, WindowStyles, Int32, Int32, Int32, Int32, IntPtr, IntPtr, IntPtr, IntPtr) to create a MDI client window, *param* should point to a CLIENTCREATESTRUCT structure. 

 If an MDI client window calls CreateWindowEx(WindowStylesEx, String, String, WindowStyles, Int32, Int32, Int32, Int32, IntPtr, IntPtr, IntPtr, IntPtr) to create an MDI child window, *param* should point to a MDICREATESTRUCT structure. 

*param* may be Zero if no additional data is needed.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the new window. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-createwindowexa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-createwindowexa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />