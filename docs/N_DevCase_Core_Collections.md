# DevCase.Core.Collections Namespace
 




## Classes
&nbsp;<table><tr><th></th><th>Class</th><th>Description</th></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Collections_CombinationCollection_1">CombinationCollection(T)</a></td><td>
Combinations defines a meta-collection, typically a list of lists, of all possible subsets of a particular size from the set of values. 

 This list is enumerable and allows the scanning of all possible combinations using a simple `For Each` loop. 

 Within the returned set, there is no prescribed order. This follows the mathematical concept of choose. 

 For example, put 10 dominoes in a hat and pick 5. The number of possible combinations is defined as "`10 choose 5`", which is calculated as `(10!) / ((10 - 5)! * 5!)`.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Collections_FixedQueue_1">FixedQueue(T)</a></td><td>
Represents a Queue(T) with a fixed capacity.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Collections_FixedStack_1">FixedStack(T)</a></td><td>
Represents a Stack(T) with a fixed capacity.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T)</a></td><td>
Permutations defines a meta-collection, typically a list of lists, of all possible orderings of a set of values. 

 This list is enumerable and allows the scanning of all possible permutations using a simple `For Each` loop.</td></tr></table>

## Structures
&nbsp;<table><tr><th></th><th>Structure</th><th>Description</th></tr><tr><td>![Public structure](media/pubstructure.gif "Public structure")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Collections_ReadOnlyValuePair_1">ReadOnlyValuePair(TValue)</a></td><td>
Represents a read-only pair of values of the same Type.</td></tr><tr><td>![Public structure](media/pubstructure.gif "Public structure")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Collections_ReadOnlyValuePair_2">ReadOnlyValuePair(TValue1, TValue2)</a></td><td>
Represents a read-only pair of values.</td></tr><tr><td>![Public structure](media/pubstructure.gif "Public structure")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Collections_ValuePair_1">ValuePair(TValue)</a></td><td>
Represents a pair of values of the same Type.</td></tr><tr><td>![Public structure](media/pubstructure.gif "Public structure")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Collections_ValuePair_2">ValuePair(TValue1, TValue2)</a></td><td>
Represents a pair of values.</td></tr></table>

## Interfaces
&nbsp;<table><tr><th></th><th>Interface</th><th>Description</th></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Core_Collections_IMetaCollection_1">IMetaCollection(T)</a></td><td>
Interface for Permutations, Combinations and any other classes that present a collection of collections based on an input collection. 

 The enumerators that this class inherits defines the mechanism for enumerating through the collections.</td></tr></table>

## Enumerations
&nbsp;<table><tr><th></th><th>Enumeration</th><th>Description</th></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Collections_EnumFindDirection">EnumFindDirection</a></td><td>
Specifies a direction to find a value in a Enum.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Collections_MetaCollectionType">MetaCollectionType</a></td><td>
Specifies whether or not a <a href="T_DevCase_Core_Collections_CombinationCollection_1">CombinationCollection(T)</a> or <a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T)</a> meta-collections will generate repetition sets.</td></tr></table>&nbsp;
