# PermutationCollection(*T*) Constructor 
 


## Overload List
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_PermutationCollection_1__ctor">PermutationCollection(T)(IList(T))</a></td><td>
Initializes a new instance of the <a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T)</a> class. 

 Create a permutation set from the provided list of values. 

 The values `T` must implement IComparable. 

 If `T` does not implement IComparable use a constructor with an explict IComparer. 

 The repetition type defaults to <a href="T_DevCase_Core_Collections_MetaCollectionType">WithoutRepetition</a></td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_PermutationCollection_1__ctor_1">PermutationCollection(T)(IList(T), MetaCollectionType)</a></td><td>
Initializes a new instance of the <a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T)</a> class. 

 Create a permutation set from the provided list of values. 

 If type is <a href="T_DevCase_Core_Collections_MetaCollectionType">WithoutRepetition</a>, then values (`T`) must implement IComparable. 

 If T does not implement IComparable use a constructor with an explict IComparer.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_PermutationCollection_1__ctor_2">PermutationCollection(T)(IList(T), IComparer(T))</a></td><td>
Initializes a new instance of the <a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T)</a> class. 

 Create a permutation set from the provided list of values. 

 The values will be compared using the supplied IComparer. 

 The repetition type defaults to <a href="T_DevCase_Core_Collections_MetaCollectionType">WithoutRepetition</a></td></tr></table>&nbsp;
<a href="#permutationcollection(*t*)-constructor">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T) Class</a><br /><a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />