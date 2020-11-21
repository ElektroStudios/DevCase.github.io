# CompilerSettings.LibraryPaths Property 
 

Gets or sets a value that specifies additional directories in which to search for assembly references.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public List<string> LibraryPaths { get; set; }
```

**VB**<br />
``` VB
Public Property LibraryPaths As List(Of String)
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerSettings
Dim value As List(Of String)

value = instance.LibraryPaths

instance.LibraryPaths = value
```

**C++**<br />
``` C++
public:
property List<String^>^ LibraryPaths {
	List<String^>^ get ();
	void set (List<String^>^ value);
}
```

**F#**<br />
``` F#
member LibraryPaths : List<string> with get, set

```


#### Property Value
Type: List(String)<br />A value that specifies additional directories in which to search for assembly references

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_CompilerSettings">CompilerSettings Class</a><br /><a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />