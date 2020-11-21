# BBCodeHtmlRenderException.GetObjectData Method 
 

Populates a SerializationInfo with the data needed to serialize the target object.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Exceptions">DevCase.Core.NET.Exceptions</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override void GetObjectData(
	SerializationInfo info,
	StreamingContext context
)
```

**VB**<br />
``` VB
Public Overrides Sub GetObjectData ( 
	info As SerializationInfo,
	context As StreamingContext
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As BBCodeHtmlRenderException
Dim info As SerializationInfo
Dim context As StreamingContext

instance.GetObjectData(info, context)
```

**C++**<br />
``` C++
public:
virtual void GetObjectData(
	SerializationInfo^ info, 
	StreamingContext context
) override
```

**F#**<br />
``` F#
abstract GetObjectData : 
        info : SerializationInfo * 
        context : StreamingContext -> unit 
override GetObjectData : 
        info : SerializationInfo * 
        context : StreamingContext -> unit 
```


#### Parameters
&nbsp;<dl><dt>info</dt><dd>Type: System.Runtime.Serialization.SerializationInfo<br />The SerializationInfo to populate with data.</dd><dt>context</dt><dd>Type: System.Runtime.Serialization.StreamingContext<br />The destination (see StreamingContext) for this serialization.</dd></dl>

#### Implements
ISerializable.GetObjectData(SerializationInfo, StreamingContext)<br />_Exception.GetObjectData(SerializationInfo, StreamingContext)<br />

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>info</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Exceptions_BBCodeHtmlRenderException">BBCodeHtmlRenderException Class</a><br /><a href="N_DevCase_Core_NET_Exceptions">DevCase.Core.NET.Exceptions Namespace</a><br />