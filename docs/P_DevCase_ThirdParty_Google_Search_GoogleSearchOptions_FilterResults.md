# GoogleSearchOptions.FilterResults Property 
 

Gets or sets a value indicating whether to exclude similar website results from the search pages. 

 Default value: `false` (`False` in Visual Basic)

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(false)]
public bool FilterResults { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(false)>
Public Property FilterResults As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As GoogleSearchOptions
Dim value As Boolean

value = instance.FilterResults

instance.FilterResults = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(false)]
property bool FilterResults {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(false)>]
member FilterResults : bool with get, set

```


#### Property Value
Type: Boolean<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.Google.Search.GoogleSearchOptions.FilterResults"\]

## Remarks
<a href="https://developers.google.com/custom-search/docs/xml_results#filtersp" target="_blank">https://developers.google.com/custom-search/docs/xml_results#filtersp</a>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Search_GoogleSearchOptions">GoogleSearchOptions Class</a><br /><a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search Namespace</a><br />