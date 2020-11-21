# NativeMethods.SetDllDirectory Method 
 

Adds a directory to the search path used to locate DLLs for the application.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool SetDllDirectory(
	string pathName
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function SetDllDirectory ( 
	pathName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim pathName As String
Dim returnValue As Boolean

returnValue = NativeMethods.SetDllDirectory(pathName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool SetDllDirectory(
	String^ pathName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member SetDllDirectory : 
        pathName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>pathName</dt><dd>Type: System.String<br />The directory to be added to the search path. 

 If this parameter is an empty string (""), the call removes the current directory from the default DLL search order. 

 If this parameter is NULL, the function restores the default search order.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/ms686203(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/ms686203(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />