# SHChangeNotifyFlags Enumeration
 

Flags for `uFlags` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHChangeNotify">SHChangeNotify(SHChangeNotifyEventID, SHChangeNotifyFlags, IntPtr, IntPtr)</a> method.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SHChangeNotifyFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SHChangeNotifyFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As SHChangeNotifyFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SHChangeNotifyFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SHChangeNotifyFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyFlags.Dword">**Dword**</td><td>3</td><td>The `dwItem1` and `dwItem2` parameters are DWORD values.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyFlags.ItemIdList">**ItemIdList**</td><td>0</td><td>`dwItem1` and `dwItem2` are the addresses of `ITEMIDLIST` structures that represent the item(s) affected by the change. 

 Each `ITEMIDLIST` must be relative to the desktop folder.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyFlags.PathA">**PathA**</td><td>1</td><td>`dwItem1` and `dwItem2` are the addresses of null-terminated strings, of maximum length MAX_PATH that contain the full path names of the items affected by the change.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyFlags.PathW">**PathW**</td><td>5</td><td>`dwItem1` and `dwItem2` are the addresses of null-terminated strings, of maximum length MAX_PATH that contain the full path names of the items affected by the change.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyFlags.PrinterA">**PrinterA**</td><td>2</td><td>`dwItem1` and `dwItem2` are the addresses of null-terminated strings, that represent the friendly names of the printer(s) affected by the change.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyFlags.PrinterW">**PrinterW**</td><td>6</td><td>`dwItem1` and `dwItem2` are the addresses of null-terminated strings, that represent the friendly names of the printer(s) affected by the change.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyFlags.Flush">**Flush**</td><td>4096</td><td>The function should not return until the notification has been delivered to all affected components. 

 As this flag modifies other data-type flags it cannot by used by itself.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyFlags.FlushNoWait">**FlushNoWait**</td><td>8192</td><td>The function should begin delivering notifications to all affected components, but should return as soon as the notification process has begun. 

 As this flag modifies other data-type flags it cannot by used by itself.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762118%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762118%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />