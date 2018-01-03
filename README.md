# summernote-lists
A [Summernote](http://summernote.org/) adds a button to the table popover to add a table heading when you click on the top table row.

### Usage

1. Include the js and css
2. Customize the Summernote table popover to include `tableHeader`
````
$(document).ready(function() {
  $('#summernote').summernote({
    popover: {
      table: [
        ['add', ['addRowDown', 'addRowUp', 'addColLeft', 'addColRight']],
        ['delete', ['deleteRow', 'deleteCol', 'deleteTable']],
        ['custom', ['tableHeader']]
      ],
    },
  });
});
````

### Working Example

https://rawgit.com/tylerecouture/summernote-table-headers/master/Example/example.html
