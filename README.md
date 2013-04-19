# ArrayToTable.js

## Usage

Include the file in your html page
```
<script src="arrayToTable.js"></script>
```

Create an empty table that will contain the data
```
<table id="tableID"></table>
```

Launch the rendering with the following scritp
```
<script>
    var myArray = [{name:'Thibaut', age:22, randomNumber:0.314}, {name:'Joe', age:43, randomNumber:0.256}, {name:'Jane', age:27, randomNumber:0.1337}];
    arrayToTable.setTable('tableID', myArray);
</script>
```

## License

MIT
