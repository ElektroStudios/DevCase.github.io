# VolumeUtil Fields
 

The <a href="T_DevCase_Core_Shell_Tools_VolumeUtil">VolumeUtil</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedPathPrefix">ExtendedPathPrefix</a></td><td>
In `Windows` system, the maximum length for a path is composed of `260` characters, however, the `Windows API` has many functions that also have `Unicode` versions to permit an extended-length path for a maximum total path length of approximately `32.767` characters. 

 To specify an extended-length path, you must use the "`\\?\`" prefix when calling a `Windows API` function, for example: "`\\?\C:\very long path`".</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedUncPathPrefix">ExtendedUncPathPrefix</a></td><td>
In `Windows` system, the maximum length for a path is composed of `260` characters, however, the `Windows API` has many functions that also have `Unicode` versions to permit an extended-length path for a maximum total path length of approximately `32.767` characters. 

 The extended-length path prefix is defined in the <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedPathPrefix">ExtendedPathPrefix</a> property, read the property description for further details about its usage. 

 The extended-length path prefix can also be used with paths constructed according to the universal naming convention (`UNC`). To specify such a path using `UNC`, you must use the "`\\?\UNC\`" prefix, for example: "`\\?\UNC\server\Very long path`".</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Shell_Tools_VolumeUtil_MaxExtendedPathLength">MaxExtendedPathLength</a></td><td>
In `Windows` system, the maximum length for a path is composed of `260` characters, however, the `Windows API` has many functions that also have `Unicode` versions to permit an extended-length path for a maximum total path length of approximately `32.767` characters. 

 The extended-length path prefix is defined in the <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedPathPrefix">ExtendedPathPrefix</a> property, read the property description for further details about its usage. 

 Note that the maximum path of `32.767` characters is approximate, because the extended-length path prefix may be expanded to a longer string by the system at run time, and this expansion applies to the total length.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Shell_Tools_VolumeUtil_MaxPathLength">MaxPathLength</a></td><td>
In `Windows` system, the maximum length for a path is composed of `260` characters. 

 A local path is structured in the following order: drive letter, colon, backslash, name components separated by backslashes, and a terminating null character. 

 For example, the maximum path on drive `C:\` is "`C:\some 256-character path string{NUL}`" where "`{NUL}`" represents the invisible terminating null character for the current system codepage.</td></tr></table>&nbsp;
<a href="#volumeutil-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_VolumeUtil">VolumeUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />