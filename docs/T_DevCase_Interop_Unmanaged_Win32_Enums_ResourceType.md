# ResourceType Enumeration
 

Specifies a resource type of a resource table. 

 Used by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FindResource">FindResource(SafeModuleHandle, IntPtr, ResourceType)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FindResourceEx">FindResourceEx(SafeModuleHandle, ResourceType, IntPtr, UInt16)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_UpdateResource">UpdateResource(SafeModuleHandle, ResourceType, IntPtr, UInt16, IntPtr, UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ResourceType
```

**VB**<br />
``` VB
Public Enumeration ResourceType
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResourceType
```

**C++**<br />
``` C++
public enum class ResourceType
```

**F#**<br />
``` F#
type ResourceType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.Accelerator">**Accelerator**</td><td>9</td><td>Accelerator table.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.AnimatedCursor">**AnimatedCursor**</td><td>21</td><td>Animated cursor.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.AnimatedIcon">**AnimatedIcon**</td><td>22</td><td>Animated icon.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.Bitmap">**Bitmap**</td><td>2</td><td>Bitmap resource.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.Cursor">**Cursor**</td><td>1</td><td>Hardware-dependent cursor resource.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.Dialog">**Dialog**</td><td>5</td><td>Dialog box.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.DialogInclude">**DialogInclude**</td><td>17</td><td>Allows a resource editing tool to associate a string with an .rc file. 

 Typically, the string is the name of the header file that provides symbolic names. 

 The resource compiler parses the string but otherwise ignores the value.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.Font">**Font**</td><td>8</td><td>Font resource.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.FontDirectory">**FontDirectory**</td><td>7</td><td>Font directory resource.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.GroupCursor">**GroupCursor**</td><td>12</td><td>Hardware-independent cursor resource.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.GroupIcon">**GroupIcon**</td><td>14</td><td>Hardware-independent icon resource.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.Html">**Html**</td><td>23</td><td>HTML resource.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.Icon">**Icon**</td><td>3</td><td>Hardware-dependent icon resource.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.Manifest">**Manifest**</td><td>24</td><td>Side-by-Side Assembly Manifest.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.Menu">**Menu**</td><td>4</td><td>Menu resource.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.MessageTable">**MessageTable**</td><td>11</td><td>Message-table entry.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.PlugAndPlay">**PlugAndPlay**</td><td>19</td><td>Plug and Play resource.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.ResourceData">**ResourceData**</td><td>10</td><td>Application-defined resource (raw data).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.String">**String**</td><td>6</td><td>String-table entry.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.Version">**Version**</td><td>16</td><td>Version resource.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ResourceType.Vxd">**Vxd**</td><td>20</td><td>VXD.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648009(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648009(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />