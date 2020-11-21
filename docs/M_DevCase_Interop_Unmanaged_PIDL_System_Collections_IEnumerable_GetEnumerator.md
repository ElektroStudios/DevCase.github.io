# PIDL.IEnumerable.GetEnumerator Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
IEnumeratorIEnumerable.GetEnumerator()
```

**VB**<br />
``` VB
Private Function IEnumerable_GetEnumerator As IEnumerator
	Implements IEnumerable.GetEnumerator
```

**VB Usage**<br />
``` VB Usage
Dim instance As PIDL
Dim returnValue As IEnumerator

returnValue = CType(instance, IEnumerable).GetEnumerator()
```

**C++**<br />
``` C++
private:
virtual IEnumerator^ IEnumerable_GetEnumerator() sealed = IEnumerable::GetEnumerator
```

**F#**<br />
``` F#
private abstract IEnumerable_GetEnumerator : unit -> IEnumerator 
private override IEnumerable_GetEnumerator : unit -> IEnumerator 
```


#### Return Value
Type: IEnumerator<br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.PIDL.System#Collections#IEnumerable#GetEnumerator"\]

#### Implements
IEnumerable.GetEnumerator()<br />

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL Class</a><br /><a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged Namespace</a><br />