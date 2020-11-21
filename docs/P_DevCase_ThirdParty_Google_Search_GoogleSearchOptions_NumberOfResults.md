# GoogleSearchOptions.NumberOfResults Property 
 

Gets or sets the number of search results to return. 

 The maximum allowed value is <a href="F_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_MaxNumberOfResults">MaxNumberOfResults</a>. 

 Default value: `100`

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(100)]
public int NumberOfResults { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(100)>
Public Property NumberOfResults As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As GoogleSearchOptions
Dim value As Integer

value = instance.NumberOfResults

instance.NumberOfResults = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(100)]
property int NumberOfResults {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(100)>]
member NumberOfResults : int with get, set

```


#### Property Value
Type: Int32<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.Google.Search.GoogleSearchOptions.NumberOfResults"\]

## Remarks
<a href="https://developers.google.com/custom-search/docs/xml_results#numsp" target="_blank">https://developers.google.com/custom-search/docs/xml_results#numsp</a>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Search_GoogleSearchOptions">GoogleSearchOptions Class</a><br /><a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search Namespace</a><br />