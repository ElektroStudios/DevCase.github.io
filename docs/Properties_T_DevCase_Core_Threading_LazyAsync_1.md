# LazyAsync(*T*) Properties
 

The <a href="T_DevCase_Core_Threading_LazyAsync_1">LazyAsync(T)</a> generic type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Threading_LazyAsync_1_IsValueCreated">IsValueCreated</a></td><td>
Gets a value that indicates whether a value has been created for this <a href="T_DevCase_Core_Threading_LazyAsync_1">LazyAsync(T)</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Threading_LazyAsync_1_Value">Value</a></td><td>
Gets the lazily initialized value of the current <a href="T_DevCase_Core_Threading_LazyAsync_1">LazyAsync(T)</a>. 

 If the value have not been initialized, blocks the calling thread until the value get initialized. 

 If during initialization an exception have been thrown, it will wrapped into AggregateException and rethrowned on accessing this property.</td></tr></table>&nbsp;
<a href="#lazyasync(*t*)-properties">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Threading_LazyAsync_1">LazyAsync(T) Class</a><br /><a href="N_DevCase_Core_Threading">DevCase.Core.Threading Namespace</a><br />