# PathOptions Enumeration
 

Flags that determine ho to construct a path.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum PathOptions
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration PathOptions
```

**VB Usage**<br />
``` VB Usage
Dim instance As PathOptions
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class PathOptions
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type PathOptions
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PathOptions.None">**None**</td><td>0</td><td>Do not allow for the construction of \\?\ paths (ie, long paths) longer than MAX_PATH.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PathOptions.AllowLongPaths">**AllowLongPaths**</td><td>1</td><td>Allow the building of \\?\ paths longer than MAX_PATH.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PathOptions.ForceEnableLongNameProcess">**ForceEnableLongNameProcess**</td><td>2</td><td>Forces the API to treat the caller as long path enabled, independent of the process's long name enabled state. 

 This option can be used only when AllowLongPaths is specified, and cannot be used with ForceDisableLongNameProcess

 Note: This value is available starting in Windows 10, version 1703.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PathOptions.ForceDisableLongNameProcess">**ForceDisableLongNameProcess**</td><td>4</td><td>Forces the API to treat the caller as long path disabled, independent of the process's long name enabled state. 

 This option can be used only when AllowLongPaths is specified, and cannot be used with ForceEnableLongNameProcess

 Note: This value is available starting in Windows 10, version 1703.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PathOptions.DoNotNormalizeSegments">**DoNotNormalizeSegments**</td><td>8</td><td>Disables the normalization of path segments that includes removing trailing dots and spaces. 

 This enables access to paths that win32 path normalization will block. 

 Note: This value is available starting in Windows 10, version 1703.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PathOptions.EnsureIsExtendedLengthPath">**EnsureIsExtendedLengthPath**</td><td>16</td><td>Converts the input path into the extended length DOS device path form (with the \\?\ prefix) If not already in that form. 

 This enables access to paths that are otherwise not addressable due to Win32 normalization rules (that can strip trailing dots and spaces) and path length limitations. 

 This option implies the same behavior of DoNotNormalizeSegments. 

 Note: This value is available starting in Windows 10, version 1703.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PathOptions.EnsureTrailingSlash">**EnsureTrailingSlash**</td><td>32</td><td>When combining or normalizing a path, ensure there is a trailing backslash. 

 Note: This value is available starting in Windows 10, version 1703.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />