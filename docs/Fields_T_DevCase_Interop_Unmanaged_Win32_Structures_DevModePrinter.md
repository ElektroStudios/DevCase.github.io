# DevModePrinter Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter">DevModePrinter</a> type exposes the following members.


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
<a href="#devmodeprinter-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter">DevModePrinter Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />