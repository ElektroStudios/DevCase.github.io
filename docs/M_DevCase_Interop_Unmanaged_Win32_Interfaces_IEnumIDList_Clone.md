# IEnumIDList.Clone Method 
 

Creates a new item enumeration object with the same contents and state as the current one.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
IEnumIDList Clone()
```

**VB**<br />
``` VB
Function Clone As IEnumIDList
```

**VB Usage**<br />
``` VB Usage
Dim instance As IEnumIDList
Dim returnValue As IEnumIDList

returnValue = instance.Clone()
```

**C++**<br />
``` C++
IEnumIDList^ Clone()
```

**F#**<br />
``` F#
abstract Clone : unit -> IEnumIDList 

```


#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IEnumIDList">IEnumIDList</a><br />The address of a pointer to the new enumeration object. 

 The calling application must eventually free the new object by calling its Release member function.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IEnumIDList">IEnumIDList Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />