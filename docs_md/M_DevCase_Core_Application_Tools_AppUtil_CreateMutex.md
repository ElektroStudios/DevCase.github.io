# AppUtil.CreateMutex Method (MutexScope, String, Boolean)
 

Initializes a new instance of the Mutex class with a Boolean value that indicates whether the calling thread should have initial ownership of the Mutex, and a String that is the name of the mutex.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Mutex CreateMutex(
	MutexScope scope,
	string name,
	bool initiallyOwned
)
```

**VB**<br />
``` VB
Public Shared Function CreateMutex ( 
	scope As MutexScope,
	name As String,
	initiallyOwned As Boolean
) As Mutex
```

**VB Usage**<br />
``` VB Usage
Dim scope As MutexScope
Dim name As String
Dim initiallyOwned As Boolean
Dim returnValue As Mutex

returnValue = AppUtil.CreateMutex(scope, 
	name, initiallyOwned)
```

**C++**<br />
``` C++
public:
static Mutex^ CreateMutex(
	MutexScope scope, 
	String^ name, 
	bool initiallyOwned
)
```

**F#**<br />
``` F#
static member CreateMutex : 
        scope : MutexScope * 
        name : string * 
        initiallyOwned : bool -> Mutex 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Application_MutexScope">DevCase.Core.Application.MutexScope</a><br />The visibility scope for the Mutex object to be created.</dd><dt>name</dt><dd>Type: System.String<br />The name of the system mutex. 

 If the value is a null reference (`Nothing` in Visual Basic), the Mutex is unnamed.</dd><dt>initiallyOwned</dt><dd>Type: System.Boolean<br />`true` (`True` in Visual Basic) to give the calling thread initial ownership of the named system mutex if the named system mutex is created as a result of this call; otherwise, `false` (`False` in Visual Basic).</dd></dl>

#### Return Value
Type: Mutex<br />The resulting Mutex object.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mutexName As String = Guid.NewGuid().ToString()
Dim initiallyOwned As Boolean = True

Dim mutex As Mutex = CreateMutex(MutexScope.Global, mutexName, initiallyOwned)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_AppUtil_CreateMutex">CreateMutex Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />