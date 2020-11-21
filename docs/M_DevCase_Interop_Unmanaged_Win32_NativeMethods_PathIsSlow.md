# NativeMethods.PathIsSlow Method 
 

Determines whether a file path is a high-latency network connection.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool PathIsSlow(
	string file,
	uint attr = 4294967295
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function PathIsSlow ( 
	file As String,
	Optional attr As UInteger = 4294967295
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim file As String
Dim attr As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.PathIsSlow(file, 
	attr)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool PathIsSlow(
	String^ file, 
	unsigned int attr = 4294967295
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PathIsSlow : 
        file : string * 
        ?attr : uint32 
(* Defaults:
        let _attr = defaultArg attr 4294967295
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.String<br />A pointer to a null-terminated string that contains the fully qualified path of the file.</dd><dt>attr (Optional)</dt><dd>Type: System.UInt32<br />The file attributes, if known; otherwise, pass –1 and this function gets the attributes by calling GetFileAttributes function.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if the connection is high-latency; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj/nf-shlobj-pathisslowa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj/nf-shlobj-pathisslowa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />