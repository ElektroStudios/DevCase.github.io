# ShellAddToRecentDocsFlags Enumeration
 

Specifies the interpretation of the data passed by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHAddToRecentDocs">SHAddToRecentDocs(ShellAddToRecentDocsFlags, PIDL)</a> function in its `path` parameter to identify the item whose usage statistics are being tracked.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ShellAddToRecentDocsFlags
```

**VB**<br />
``` VB
Public Enumeration ShellAddToRecentDocsFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellAddToRecentDocsFlags
```

**C++**<br />
``` C++
public enum class ShellAddToRecentDocsFlags
```

**F#**<br />
``` F#
type ShellAddToRecentDocsFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellAddToRecentDocsFlags.Pidl">**Pidl**</td><td>1</td><td>A `PIDL` that identifies the document's file object. 

`PIDLs` that identify non-file objects are not accepted.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellAddToRecentDocsFlags.PathA">**PathA**</td><td>2</td><td>A null-terminated ANSI string with the path and file name of the object</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellAddToRecentDocsFlags.PathW">**PathW**</td><td>3</td><td>A null-terminated Unicode string with the path and file name of the object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellAddToRecentDocsFlags.AppIdInfo">**AppIdInfo**</td><td>4</td><td>A `SHARDAPPIDINFO` structure that pairs an `IShellItem` that identifies the item with an AppUserModelID that associates it with a particular process or application.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellAddToRecentDocsFlags.AppIdInfoIdList">**AppIdInfoIdList**</td><td>5</td><td>A `SHARDAPPIDINFOIDLIST` structure that pairs an absolute `PIDL` that identifies the item with an AppUserModelID that associates it with a particular process or application.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellAddToRecentDocsFlags.Link">**Link**</td><td>6</td><td>An interface pointer to an IShellLink object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellAddToRecentDocsFlags.AppIdInfoLink">**AppIdInfoLink**</td><td>7</td><td>A `SHARDAPPIDINFOLINK` structure that pairs an `IShellLink` that identifies the item with an AppUserModelID that associates it with a particular process or application.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellAddToRecentDocsFlags.ShellItem">**ShellItem**</td><td>8</td><td>An interface pointer to an `IShellItem` object.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd378453(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd378453(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />