# NativeMethods.FindWindowEx Method (SafeHandle, SafeHandle, String, String)
 

Retrieves a handle to a window whose class name and window name match the specified strings. 

 The function searches child windows, beginning with the one following the specified child window. 

 This function does not perform a case-sensitive search.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr FindWindowEx(
	SafeHandle hWndParent,
	SafeHandle hWndChildAfter,
	string className,
	string windowName
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function FindWindowEx ( 
	hWndParent As SafeHandle,
	hWndChildAfter As SafeHandle,
	className As String,
	windowName As String
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWndParent As SafeHandle
Dim hWndChildAfter As SafeHandle
Dim className As String
Dim windowName As String
Dim returnValue As IntPtr

returnValue = NativeMethods.FindWindowEx(hWndParent, 
	hWndChildAfter, className, windowName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr FindWindowEx(
	SafeHandle^ hWndParent, 
	SafeHandle^ hWndChildAfter, 
	String^ className, 
	String^ windowName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member FindWindowEx : 
        hWndParent : SafeHandle * 
        hWndChildAfter : SafeHandle * 
        className : string * 
        windowName : string -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWndParent</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A IntPtr handle to the parent window whose child windows are to be searched. 

 If *hwndParent* is Zero, the function uses the desktop window as the parent window. 

 The function searches among windows that are child windows of the desktop.</dd><dt>hWndChildAfter</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A IntPtr handle to a child window. 

 The search begins with the next child window in the Z order. 

 The child window must be a direct child window of hwndParent, not just a descendant window. 

 If *hwndChildAfter* is Zero, the search begins with the first child window of *hwndParent*.</dd><dt>className</dt><dd>Type: System.String<br />The window class name.</dd><dt>windowName</dt><dd>Type: System.String<br />The window name (the window title). 

 If this parameter is a null reference (`Nothing` in Visual Basic), all window names match.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a IntPtr handle to the window that has the specified class and window names. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633500%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633500%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_FindWindowEx">FindWindowEx Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />