# LoadLibraryFlags Enumeration
 

Specifies the action to be taken when loading the module through the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadLibraryEx">LoadLibraryEx(String, IntPtr, LoadLibraryFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum LoadLibraryFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration LoadLibraryFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As LoadLibraryFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class LoadLibraryFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type LoadLibraryFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadLibraryFlags.None">**None**</td><td>0</td><td>Define no flags.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadLibraryFlags.DontResolveDllReferences">**DontResolveDllReferences**</td><td>1</td><td>If this value is used, and the executable module is a DLL, the system does not call DllMain for process and thread initialization and termination. 

 Also, the system does not load additional executable modules that are referenced by the specified module. 

 Do not use this value; it is provided only for backward compatibility. 

 If you are planning to access only data or resources in the DLL, use LoadLibraryAsDataFileExclusive or LoadLibraryAsImageResource or both. Otherwise, load the library as a DLL or executable module using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadLibrary">LoadLibrary(String)</a> function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadLibraryFlags.IgnoreCodeAuthzLevel">**IgnoreCodeAuthzLevel**</td><td>16</td><td>If this value is used, the system does not check AppLocker rules or apply Software Restriction Policies for the DLL. This action applies only to the DLL being loaded and not to its dependencies. 

 This value is recommended for use in setup programs that must run extracted DLLs during installation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadLibraryFlags.LoadLibraryAsDataFile">**LoadLibraryAsDataFile**</td><td>2</td><td>If this value is used, the system maps the file into the calling process's virtual address space as if it were a data file. Nothing is done to execute or prepare to execute the mapped file. Therefore, you cannot call functions like `GetModuleFileName`, `GetModuleHandle` or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetProcAddress">GetProcAddress(SafeModuleHandle, String)</a> with this DLL. 

 Using this value causes writes to read-only memory to raise an access violation. 

 Use this flag when you want to load a DLL only to extract messages or resources from it. 

 This value can be used with LoadLibraryAsImageResource.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadLibraryFlags.LoadLibraryAsDataFileExclusive">**LoadLibraryAsDataFileExclusive**</td><td>64</td><td>Similar to LoadLibraryAsDataFile, except that the DLL file is opened with exclusive write access for the calling process. 

 Other processes cannot open the DLL file for write access while it is in use. 

 However, the DLL can still be opened by other processes. 

 This value can be used with LoadLibraryAsImageResource.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadLibraryFlags.LoadLibraryAsImageResource">**LoadLibraryAsImageResource**</td><td>32</td><td>If this value is used, the system maps the file into the process's virtual address space as an image file. However, the loader does not load the static imports or perform the other usual initialization steps. 

 Use this flag when you want to load a DLL only to extract messages or resources from it. 

 Unless the application depends on the file having the in-memory layout of an image, this value should be used with either LoadLibraryAsDataFile or LoadLibraryAsDataFileExclusive.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadLibraryFlags.LoadLibrarySearchApplicationDir">**LoadLibrarySearchApplicationDir**</td><td>512</td><td>If this value is used, the application's installation directory is searched for the DLL and its dependencies. 

 Directories in the standard search path are not searched. 

 This value cannot be combined with LoadWithAlteredSearchPath.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadLibraryFlags.LoadLibrarySearchDefaultDirs">**LoadLibrarySearchDefaultDirs**</td><td>4096</td><td>This value is a combination of LoadLibrarySearchApplicationDir, LoadLibrarySearchSystem32, and LoadLibrarySearchUserDirs. Directories in the standard search path are not searched. 

 This value cannot be combined with LoadWithAlteredSearchPath. 

 This value represents the recommended maximum number of directories an application should include in its DLL search path.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadLibraryFlags.LoadLibrarySearchDllLoadDir">**LoadLibrarySearchDllLoadDir**</td><td>256</td><td>If this value is used, the directory that contains the DLL is temporarily added to the beginning of the list of directories that are searched for the DLL's dependencies. 

 Directories in the standard search path are not searched. 

 The `fileName` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadLibraryEx">LoadLibraryEx(String, IntPtr, LoadLibraryFlags)</a> function must specify a fully qualified path. This value cannot be combined with LoadWithAlteredSearchPath.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadLibraryFlags.LoadLibrarySearchSystem32">**LoadLibrarySearchSystem32**</td><td>2048</td><td>If this value is used, `%windows%\system32` is searched for the DLL and its dependencies. Directories in the standard search path are not searched. 

 This value cannot be combined with LoadWithAlteredSearchPath.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadLibraryFlags.LoadLibrarySearchUserDirs">**LoadLibrarySearchUserDirs**</td><td>1024</td><td>If this value is used, directories added using the AddDllDirectory or the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetDllDirectory">SetDllDirectory(String)</a> function are searched for the DLL and its dependencies. 

 If more than one directory has been added, the order in which the directories are searched is unspecified. Directories in the standard search path are not searched. 

 This value cannot be combined with LoadWithAlteredSearchPath.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadLibraryFlags.LoadWithAlteredSearchPath">**LoadWithAlteredSearchPath**</td><td>8</td><td>If this value is used and lpFileName specifies an absolute path, the system uses the alternate file search strategy to find associated executable modules that the specified module causes to be loaded. 

 If this value is used and lpFileName specifies a relative path, the behavior is undefined.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms684179(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms684179(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />