# IShellLinkW.Resolve Method 
 

Attempts to find the target of a Shell link, even if it has been moved or renamed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void Resolve(
	IntPtr hWnd,
	IShellLinkResolveFlags flags
)
```

**VB**<br />
``` VB
Sub Resolve ( 
	hWnd As IntPtr,
	flags As IShellLinkResolveFlags
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim hWnd As IntPtr
Dim flags As IShellLinkResolveFlags

instance.Resolve(hWnd, flags)
```

**C++**<br />
``` C++
void Resolve(
	IntPtr hWnd, 
	IShellLinkResolveFlags flags
)
```

**F#**<br />
``` F#
abstract Resolve : 
        hWnd : IntPtr * 
        flags : IShellLinkResolveFlags -> unit 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window that the Shell will use as the parent for a dialog box. 

 The Shell displays the dialog box if it needs to prompt the user for more information while resolving a link.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_IShellLinkResolveFlags">DevCase.Interop.Unmanaged.Win32.Enums.IShellLinkResolveFlags</a><br />Action flags.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />