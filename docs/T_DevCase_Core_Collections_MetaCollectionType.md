# MetaCollectionType Enumeration
 

Specifies whether or not a <a href="T_DevCase_Core_Collections_CombinationCollection_1">CombinationCollection(T)</a> or <a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T)</a> meta-collections will generate repetition sets.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum MetaCollectionType
```

**VB**<br />
``` VB
Public Enumeration MetaCollectionType
```

**VB Usage**<br />
``` VB Usage
Dim instance As MetaCollectionType
```

**C++**<br />
``` C++
public enum class MetaCollectionType
```

**F#**<br />
``` F#
type MetaCollectionType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Collections.MetaCollectionType.WithoutRepetition">**WithoutRepetition**</td><td>0</td><td>Do not generate additional sets. 

 This is the typical implementation.</td></tr><tr><td /><td target="F:DevCase.Core.Collections.MetaCollectionType.WithRepetition">**WithRepetition**</td><td>1</td><td>Generate additional sets even if repetition is required.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />