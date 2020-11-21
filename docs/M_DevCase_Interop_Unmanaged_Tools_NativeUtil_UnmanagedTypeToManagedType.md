# NativeUtil.UnmanagedTypeToManagedType Method 
 

Translates a value of the UnmanagedType enumeration to an appropriated .NET managed type equivalent.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Type UnmanagedTypeToManagedType(
	UnmanagedType unmanaged
)
```

**VB**<br />
``` VB
Public Shared Function UnmanagedTypeToManagedType ( 
	unmanaged As UnmanagedType
) As Type
```

**VB Usage**<br />
``` VB Usage
Dim unmanaged As UnmanagedType
Dim returnValue As Type

returnValue = NativeUtil.UnmanagedTypeToManagedType(unmanaged)
```

**C++**<br />
``` C++
public:
static Type^ UnmanagedTypeToManagedType(
	UnmanagedType unmanaged
)
```

**F#**<br />
``` F#
static member UnmanagedTypeToManagedType : 
        unmanaged : UnmanagedType -> Type 

```


#### Parameters
&nbsp;<dl><dt>unmanaged</dt><dd>Type: System.Runtime.InteropServices.UnmanagedType<br />The unmanaged Windows type.</dd></dl>

#### Return Value
Type: Type<br />The .NET managed type.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td>unmanaged</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />