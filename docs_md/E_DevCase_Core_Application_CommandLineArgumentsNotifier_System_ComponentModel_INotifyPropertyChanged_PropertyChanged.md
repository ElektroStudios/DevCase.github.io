# CommandLineArgumentsNotifier.INotifyPropertyChanged.PropertyChanged Event
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
event PropertyChangedEventHandlerINotifyPropertyChanged.PropertyChanged
```

**VB**<br />
``` VB
Private Event PropertyChanged As PropertyChangedEventHandler
	Implements INotifyPropertyChanged.PropertyChanged
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineArgumentsNotifier
Dim handler As PropertyChangedEventHandler

AddHandler CType(instance, INotifyPropertyChanged).PropertyChanged, handler

```

**C++**<br />
``` C++
private:
virtual  event PropertyChangedEventHandler^ PropertyChanged {
	void add (PropertyChangedEventHandler^ value);
	void remove (PropertyChangedEventHandler^ value);
}
```

**F#**<br />
``` F#
private abstract PropertyChanged : IEvent<PropertyChangedEventHandler,
    PropertyChangedEventArgs>
private override PropertyChanged : IEvent<PropertyChangedEventHandler,
    PropertyChangedEventArgs>
```


#### Value
Type: System.ComponentModel.PropertyChangedEventHandler

#### Implements
INotifyPropertyChanged.PropertyChanged<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineArgumentsNotifier">CommandLineArgumentsNotifier Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />