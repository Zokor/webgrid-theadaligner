# webgrid-theadaligner
To align header on Web Grid in asp.net mvc through javascript

```
var arr= []
var count = 0;
$($('table.report ').find('tbody tr:first-child td')).each(function() {
 arr[count]=$(this).attr("class");
 count+=1;
});
count = 0;
$($('table.report').find('thead tr:first-child th')).each(function() {
 $(this).addClass(arr[count]);
 count+=1;  
});
```
