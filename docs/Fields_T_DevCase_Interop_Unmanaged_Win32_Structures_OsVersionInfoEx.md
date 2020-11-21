# OsVersionInfoEx Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx">OsVersionInfoEx</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx_BuildNumber">BuildNumber</a></td><td>
The build number of the operating system.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx_CsdVersion">CsdVersion</a></td><td>
A null-terminated string, such as "`Service Pack 3`", that indicates the latest Service Pack installed on the system. 

 If no Service Pack has been installed, the string is empty.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx_MajorVersion">MajorVersion</a></td><td>
The major version number of the operating system.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx_MinorVersion">MinorVersion</a></td><td>
The minor version number of the operating system</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx_PlatformId">PlatformId</a></td><td>
The operating system platform.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx_ProductType">ProductType</a></td><td>
Any additional information about the system.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx_Reserved">Reserved</a></td><td>
Reserved for future use.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx_ServicePackMajor">ServicePackMajor</a></td><td>
The major version number of the latest Service Pack installed on the system. 

 For example, for `Service Pack 3`, the major version number is `3`. 

 If no Service Pack has been installed, the value is zero.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx_ServicePackMinor">ServicePackMinor</a></td><td>
The minor version number of the latest Service Pack installed on the system. 

 For example, for `Service Pack 3`, the minor version number is `0`.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx_SizeOfStruct">SizeOfStruct</a></td><td>
The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of OsVersionInfoEx)` before calling any function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx_SuiteMask">SuiteMask</a></td><td>
A bit mask that identifies the product suites available on the system.</td></tr></table>&nbsp;
<a href="#osversioninfoex-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_OsVersionInfoEx">OsVersionInfoEx Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />