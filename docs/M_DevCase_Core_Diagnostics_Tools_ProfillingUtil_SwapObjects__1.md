# ProfillingUtil.SwapObjects(*T*) Method (*T*, *T*)
 

Swaps the given objects.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SwapObjects<T>(
	ref T refObj1,
	ref T refObj2
)

```

**VB**<br />
``` VB
Public Shared Sub SwapObjects(Of T) ( 
	ByRef refObj1 As T,
	ByRef refObj2 As T
)
```

**VB Usage**<br />
``` VB Usage
Dim refObj1 As T
Dim refObj2 As T

ProfillingUtil.SwapObjects(refObj1, refObj2)
```

**C++**<br />
``` C++
public:
generic<typename T>
static void SwapObjects(
	T% refObj1, 
	T% refObj2
)
```

**F#**<br />
``` F#
static member SwapObjects : 
        refObj1 : 'T byref * 
        refObj2 : 'T byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>refObj1</dt><dd>Type: *T*<br />The first object.</dd><dt>refObj2</dt><dd>Type: *T*<br />The second object.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The Type parameter.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim a As Integer = 10
Dim b As Integer = 20

SwapObjects(a, b)
Console.WriteLine("a: {0}, b: {1}", a, b)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_ProfillingUtil">ProfillingUtil Class</a><br /><a href="Overload_DevCase_Core_Diagnostics_Tools_ProfillingUtil_SwapObjects">SwapObjects Overload</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />