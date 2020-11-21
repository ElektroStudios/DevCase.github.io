# ConsoleFontInfoEx Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx">ConsoleFontInfoEx</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx_FaceName">FaceName</a></td><td>
The name of the font typeface (such as Arial, Courier or Consolas).</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx_FontFamily">FontFamily</a></td><td>
The font pitch and family.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx_FontIndex">FontIndex</a></td><td>
The index of the font in the system's console font table.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx_FontSize">FontSize</a></td><td>
A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">ConsoleCoordinate</a> structure that contains the width and height of each character in the font, in logical units. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_X">X</a> member contains the width, while the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_Y">Y</a> member contains the height.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx_FontWeight">FontWeight</a></td><td>
The font weight. 

 The weight can range from 100 to 1000, in multiples of 100. For example, the normal weight is 400, while 700 is bold.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx_SizeOfStruct">SizeOfStruct</a></td><td>
The size of this structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of ConsoleFontInfoEx)` before calling any function.</td></tr></table>&nbsp;
<a href="#consolefontinfoex-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx">ConsoleFontInfoEx Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />