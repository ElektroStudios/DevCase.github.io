# ListViewColumnSorter Class
 

Performs a sorting operation in a ListView.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.ListViewColumnSorter<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ListViewColumnSorter : AestheticObject, 
	IComparer
```

**VB**<br />
``` VB
Public NotInheritable Class ListViewColumnSorter
	Inherits AestheticObject
	Implements IComparer
```

**VB Usage**<br />
``` VB Usage
Dim instance As ListViewColumnSorter
```

**C++**<br />
``` C++
public ref class ListViewColumnSorter sealed : public AestheticObject, 
	IComparer
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ListViewColumnSorter =  
    class
        inherit AestheticObject
        interface IComparer
    end
```

The ListViewColumnSorter type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ListViewColumnSorter__ctor">ListViewColumnSorter</a></td><td>
Initializes a new instance of the ListViewColumnSorter class.</td></tr></table>&nbsp;
<a href="#listviewcolumnsorter-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ListViewColumnSorter_ColumnIndex">ColumnIndex</a></td><td>
Gets or sets the index of the column to which to apply the sorting operation (default index is `0`).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ListViewColumnSorter_Order">Order</a></td><td>
Gets or sets the order of sorting to apply.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ListViewColumnSorter_SortModifier">SortModifier</a></td><td>
Gets or sets the sort modifier.</td></tr></table>&nbsp;
<a href="#listviewcolumnsorter-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ListViewColumnSorter_Compare">Compare</a></td><td>
Compares two objects and returns a value indicating whether one is less than, equal to, or greater than the other.</td></tr></table>&nbsp;
<a href="#listviewcolumnsorter-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#listviewcolumnsorter-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    Friend WithEvents MyListView As New ListView
    Private sorter As New ListViewColumnSorter

    Public Sub New()

        MyClass.InitializeComponent()

        With Me.MyListView

            ' Set the sorter, our ListViewColumnSorter.
            .ListViewItemSorter = sorter

            ' The initial direction for the sorting.
            .Sorting = SortOrder.Ascending

            ' Set the initial sort-modifier.
            sorter.SortModifier = SortModifiers.SortByText

            ' Add some columns.
            .Columns.Add("Text").Tag = SortModifiers.SortByText
            .Columns.Add("Numbers").Tag = SortModifiers.SortByNumber
            .Columns.Add("Dates").Tag = SortModifiers.SortByDate

            ' Adjust the column sizes.
            For Each col As ColumnHeader In Me.MyListView.Columns
                col.Width = 100
            Next

            ' Add some items.
            .Items.Add("hello").SubItems.AddRange({"2", "11/11/2000"})
            .Items.Add("yeehaa!").SubItems.AddRange({"1", "9/9/1999"})
            .Items.Add("El3ktr0").SubItems.AddRange({"100", "21/08/2014"})
            .Items.Add("wow").SubItems.AddRange({"10", "11-11-2000"})

            ' Styling things.
            .Dock = DockStyle.Fill
            .View = View.Details
            .FullRowSelect = True
        End With

        With Me ' Styling things.
            .Size = New Size(400, 200)
            .FormBorderStyle =WinForms.FormBorderStyle.FixedSingle
            .MaximizeBox = False
            .StartPosition = FormStartPosition.CenterScreen
            .Text = "ListViewColumnSorter TestForm"
        End With

        Me.Controls.Add(Me.MyListView)

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Handles the <see cref="ListView.ColumnClick"/> event of the <see cref="MyListView"/> control.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="sender">
    ''' The source of the event.
    ''' </param>
    ''' 
    ''' <param name="e">
    ''' The <see cref="ColumnClickEventArgs"/> instance containing the event data.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Private Sub MyListView_ColumnClick(ByVal sender As Object, ByVal e As ColumnClickEventArgs) _
    Handles MyListView.ColumnClick

        Dim lv As ListView = DirectCast(sender, ListView)

        ' Dinamycaly sets the sort-modifier to sort the column by text, number, or date.
        sorter.SortModifier = DirectCast(lv.Columns(e.Column).Tag, SortModifiers)

        ' Determine whether clicked column is already the column that is being sorted.
        If (e.Column = sorter.ColumnIndex) Then

            ' Reverse the current sort direction for this column.
            If (sorter.Order = SortOrder.Ascending) Then
                sorter.Order = SortOrder.Descending

            Else
                sorter.Order = SortOrder.Ascending

            End If

        Else
            ' Set the column number that is to be sorted, default to ascending.
            sorter.ColumnIndex = e.Column
            sorter.Order = SortOrder.Ascending

        End If ' e.Column

        ' Perform the sort.
        lv.Sort()

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />