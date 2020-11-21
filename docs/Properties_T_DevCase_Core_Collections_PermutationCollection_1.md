# PermutationCollection(*T*) Properties
 

The <a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T)</a> generic type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_PermutationCollection_1_Count">Count</a></td><td>
The count of all permutations that will be returned. 

 If type is <a href="T_DevCase_Core_Collections_MetaCollectionType">WithoutRepetition</a>, then this does not double count permutations with multiple identical values. 

 I.e. count of permutations of "`AAB`" will be `3` instead of `6`. If type is <a href="T_DevCase_Core_Collections_MetaCollectionType">WithRepetition</a>, then this is all combinations and is therefore `N!`, where `N` is the number of values.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_PermutationCollection_1_LowerIndex">LowerIndex</a></td><td>
The lower index of the meta-collection, equal to the number of items returned each iteration. 

 For Permutation, this is always equal to the <a href="P_DevCase_Core_Collections_PermutationCollection_1_UpperIndex">UpperIndex</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_PermutationCollection_1_Type">Type</a></td><td>
The type of Permutations set that is generated.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_PermutationCollection_1_UpperIndex">UpperIndex</a></td><td>
The upper index of the meta-collection, equal to the number of items in the initial set.</td></tr></table>&nbsp;
<a href="#permutationcollection(*t*)-properties">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Collections_PermutationCollection_1">PermutationCollection(T) Class</a><br /><a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />