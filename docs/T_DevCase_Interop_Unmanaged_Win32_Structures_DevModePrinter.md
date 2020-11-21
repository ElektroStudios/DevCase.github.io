# DevModePrinter Structure
 

Contains information about a printer device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct DevModePrinter
```

**VB**<br />
``` VB
Public Structure DevModePrinter
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevModePrinter
```

**C++**<br />
``` C++
public value class DevModePrinter
```

**F#**<br />
``` F#
[<SealedAttribute>]
type DevModePrinter =  struct end
```

The DevModePrinter type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_Copies">Copies</a></td><td>
Selects the number of copies printed if the device supports multiple-page copies.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_DefaultSource">DefaultSource</a></td><td>
Specifies the paper source. 

 To retrieve a list of the available paper sources for a printer, use the `DeviceCapabilities` function with the `DC_BINS` flag.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_Orientation">Orientation</a></td><td>
For printer devices only, selects the orientation of the paper. 

 This member can be either `DMORIENT_PORTRAIT` (1) or `DMORIENT_LANDSCAPE` (2).</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_PaperLength">PaperLength</a></td><td>
For printer devices only, overrides the length of the paper specified by the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_PaperSize">PaperSize</a> member, either for custom paper sizes or for devices such as dot-matrix printers that can print on a page of arbitrary length. 

 These values, along with all other values in this structure that specify a physical length, are in tenths of a millimeter.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_PaperSize">PaperSize</a></td><td>
For printer devices only, selects the size of the paper to print on. 

 This member can be set to zero if the length and width of the paper are both set by the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_PaperLength">PaperLength</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_PaperWidth">PaperWidth</a> members. 

 Otherwise, the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_PaperSize">PaperSize</a> member can be set to a device specific value greater than or equal to `DMPAPER_USER`.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_PaperWidth">PaperWidth</a></td><td>
For printer devices only, overrides the width of the paper specified by the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_PaperSize">PaperSize</a> member.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_PrintQuality">PrintQuality</a></td><td>
Specifies the printer resolution.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_Scale">Scale</a></td><td>
Specifies the factor by which the printed output is to be scaled. 

 The apparent page size is scaled from the physical page size by a factor of dmScale /100. For example, a letter-sized page with a dmScale value of 50 would contain as much data as a page of 17- by 22-inches because the output text and graphics would be half their original height and width.</td></tr></table>&nbsp;
<a href="#devmodeprinter-structure">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#devmodeprinter-structure">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183565%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183565%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />