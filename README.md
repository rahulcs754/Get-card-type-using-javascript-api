# Get-card-type-using-javascript-api
You can check our card type details

#link 
https://binlist.net/

#code
```jquery
var number = "card number here";
$.get("https://lookup.binlist.net/"+number, function(data, status){
	var apires =  JSON.stringify(data);
	console.log(apires.scheme);
});
```

