# CombinationCollection(*T*).GetEnumerator Method 
 

Gets an enumerator for collecting the list of combinations.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IEnumerator<IList<T>> GetEnumerator()
```

**VB**<br />
``` VB
Public Function GetEnumerator As IEnumerator(Of IList(Of T))
```

**VB Usage**<br />
``` VB Usage
Dim instance As CombinationCollection
Dim returnValue As IEnumerator(Of IList(Of T))

returnValue = instance.GetEnumerator()
```

**C++**<br />
``` C++
public:
virtual IEnumerator<IList<T>^>^ GetEnumerator() sealed
```

**F#**<br />
``` F#
abstract GetEnumerator : unit -> IEnumerator<IList<'T>> 
override GetEnumerator : unit -> IEnumerator<IList<'T>> 
```


#### Return Value
Type: IEnumerator(IList(<a href="T_DevCase_Core_Collections_CombinationCollection_1">*T*</a>))<br />The enumerator.

#### Implements
IEnumerable(T).GetEnumerator()<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Collections_CombinationCollection_1">CombinationCollection(T) Class</a><br /><a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />