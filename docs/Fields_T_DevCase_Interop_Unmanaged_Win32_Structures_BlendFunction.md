# BlendFunction Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_BlendFunction">BlendFunction</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BlendFunction_AlphaFormat">AlphaFormat</a></td><td>
This member controls the way the source and destination bitmaps are interpreted.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BlendFunction_BlendFlags">BlendFlags</a></td><td>
Must be zero.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BlendFunction_BlendOp">BlendOp</a></td><td>
The source blend operation. 

 Currently, the only source and destination blend operation that has been defined is `AC_SRC_OVER`.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BlendFunction_SourceConstantAlpha">SourceConstantAlpha</a></td><td>
Specifies an alpha transparency value to be used on the entire source bitmap. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BlendFunction_SourceConstantAlpha">SourceConstantAlpha</a> value is combined with any per-pixel alpha values in the source bitmap. 

 If you set <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BlendFunction_SourceConstantAlpha">SourceConstantAlpha</a> to 0, it is assumed that your image is transparent. 

 Set the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BlendFunction_SourceConstantAlpha">SourceConstantAlpha</a> value to 255 (opaque) when you only want to use per-pixel alpha values.</td></tr></table>&nbsp;
<a href="#blendfunction-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_BlendFunction">BlendFunction Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />