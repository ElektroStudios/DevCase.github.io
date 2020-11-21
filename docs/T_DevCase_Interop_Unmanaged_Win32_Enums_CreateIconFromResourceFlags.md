# CreateIconFromResourceFlags Enumeration
 

Flags that determine how the icon is created by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateIconFromResourceEx">CreateIconFromResourceEx(Byte, UInt32, Boolean, UInt32, Int32, Int32, CreateIconFromResourceFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum CreateIconFromResourceFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration CreateIconFromResourceFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As CreateIconFromResourceFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class CreateIconFromResourceFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type CreateIconFromResourceFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateIconFromResourceFlags.DefaultColor">**DefaultColor**</td><td>0</td><td>The default flag; it does nothing. 

 All it means is "not Monochrome".</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateIconFromResourceFlags.DefaultSize">**DefaultSize**</td><td>64</td><td>Uses the width or height specified by the system metric values for cursors or icons, if the `width` or `height` parameters are set to zero. 

 If this flag is not specified and `width` or `height` parameters are set to zero, the function uses the actual resource size. 

 If the resource contains multiple images, the function uses the size of the first image.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateIconFromResourceFlags.Monochrome">**Monochrome**</td><td>1</td><td>Creates a monochrome icon or cursor.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CreateIconFromResourceFlags.Shared">**Shared**</td><td>32768</td><td>Shares the icon or cursor handle if the icon or cursor is created multiple times. 

 If Shared is not set, a second call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateIconFromResourceEx">CreateIconFromResourceEx(Byte, UInt32, Boolean, UInt32, Int32, Int32, CreateIconFromResourceFlags)</a> for the same resource will create the icon or cursor again and return a different handle. 

 When you use this flag, the system will destroy the resource when it is no longer needed.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648061(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648061(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />