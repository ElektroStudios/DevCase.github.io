# ShortcutFileInfo.Resolve Method 
 

Resolves the target of a shortcut. 

 This is useful when the target of a shortcut file is changed from a drive letter to another, for example. 

 If the target can't be resolved, an error message would be displayed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Resolve(
	IntPtr owner,
	IShellLinkResolveFlags flags
)
```

**VB**<br />
``` VB
Public Sub Resolve ( 
	owner As IntPtr,
	flags As IShellLinkResolveFlags
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShortcutFileInfo
Dim owner As IntPtr
Dim flags As IShellLinkResolveFlags

instance.Resolve(owner, flags)
```

**C++**<br />
``` C++
public:
void Resolve(
	IntPtr owner, 
	IShellLinkResolveFlags flags
)
```

**F#**<br />
``` F#
member Resolve : 
        owner : IntPtr * 
        flags : IShellLinkResolveFlags -> unit 

```


#### Parameters
&nbsp;<dl><dt>owner</dt><dd>Type: System.IntPtr<br />A handle used to show an error message If the target can't be resolved. 

 This value can be Zero

 Add <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_IShellLinkResolveFlags">NoUI</a> flag to *flags* parameter to don't show any error message.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_IShellLinkResolveFlags">DevCase.Interop.Unmanaged.Win32.Enums.IShellLinkResolveFlags</a><br />Flags that determine the resolve behavior.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />