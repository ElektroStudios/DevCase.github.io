# DelphiUtil.DelphiTypeToManagedType Method 
 

Translates a value of the <a href="T_DevCase_Interop_Unmanaged_DelphiDataTypes">DelphiDataTypes</a> enumeration to an appropriated managed type equivalent.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Type DelphiTypeToManagedType(
	DelphiDataTypes unmanaged
)
```

**VB**<br />
``` VB
Public Shared Function DelphiTypeToManagedType ( 
	unmanaged As DelphiDataTypes
) As Type
```

**VB Usage**<br />
``` VB Usage
Dim unmanaged As DelphiDataTypes
Dim returnValue As Type

returnValue = DelphiUtil.DelphiTypeToManagedType(unmanaged)
```

**C++**<br />
``` C++
public:
static Type^ DelphiTypeToManagedType(
	DelphiDataTypes unmanaged
)
```

**F#**<br />
``` F#
static member DelphiTypeToManagedType : 
        unmanaged : DelphiDataTypes -> Type 

```


#### Parameters
&nbsp;<dl><dt>unmanaged</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_DelphiDataTypes">DevCase.Interop.Unmanaged.DelphiDataTypes</a><br />The unmanaged Delphi type.</dd></dl>

#### Return Value
Type: Type<br />The .NET managed type.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td>unmanaged</td></tr></table>

## Remarks
<a href="http://netcoole.com/delphi2cs/datatype.htm" target="_blank">http://netcoole.com/delphi2cs/datatype.htm</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_DelphiUtil">DelphiUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />