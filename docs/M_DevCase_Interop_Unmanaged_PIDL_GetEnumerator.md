# PIDL.GetEnumerator Method 
 

Returns an enumerator that iterates through the collection.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IEnumerator<PIDL> GetEnumerator()
```

**VB**<br />
``` VB
Public Function GetEnumerator As IEnumerator(Of PIDL)
```

**VB Usage**<br />
``` VB Usage
Dim instance As PIDL
Dim returnValue As IEnumerator(Of PIDL)

returnValue = instance.GetEnumerator()
```

**C++**<br />
``` C++
public:
virtual IEnumerator<PIDL^>^ GetEnumerator() sealed
```

**F#**<br />
``` F#
abstract GetEnumerator : unit -> IEnumerator<PIDL> 
override GetEnumerator : unit -> IEnumerator<PIDL> 
```


#### Return Value
Type: IEnumerator(<a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a>)<br />A IEnumerator(T) that can be used to iterate through the collection.

#### Implements
IEnumerable(T).GetEnumerator()<br />

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL Class</a><br /><a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged Namespace</a><br />