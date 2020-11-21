# NativeMethods.ShellAbout Method (SafeHandle, String, String, IntPtr)
 

Displays a ShellAbout dialog box.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Unicode)]
public static bool ShellAbout(
	SafeHandle hWnd,
	string app,
	string otherStuff,
	IntPtr hicon
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Unicode>]
Public Shared Function ShellAbout ( 
	hWnd As SafeHandle,
	app As String,
	otherStuff As String,
	hicon As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim app As String
Dim otherStuff As String
Dim hicon As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.ShellAbout(hWnd, 
	app, otherStuff, hicon)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Unicode)]
static bool ShellAbout(
	SafeHandle^ hWnd, 
	String^ app, 
	String^ otherStuff, 
	IntPtr hicon
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Unicode)>]
static member ShellAbout : 
        hWnd : SafeHandle * 
        app : string * 
        otherStuff : string * 
        hicon : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A window handle to a parent window. This parameter can be Zero.</dd><dt>app</dt><dd>Type: System.String<br />A pointer to a null-terminated string that contains text to be displayed in the title bar of the ShellAbout dialog box and on the first line of the dialog box after the text "Microsoft". 

 If the text contains a separator char (`#`) that divides it into two parts, the function displays the first part in the title bar and the second part on the first line after the text "Microsoft".</dd><dt>otherStuff</dt><dd>Type: System.String<br />A pointer to a null-terminated string that contains text to be displayed in the dialog box after the version and copyright information. This parameter can be String.</dd><dt>hicon</dt><dd>Type: System.IntPtr<br />The handle of an icon that the function displays in the dialog box. 

 This parameter can be Zero, in which case the function displays the Windows icon.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if successful; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762152%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762152%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ShellAbout">ShellAbout Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />