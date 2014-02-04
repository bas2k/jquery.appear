# jQuery plugin to call a function when an element appears

## Usage

Mimics a custom 'appear' event, which fires when an element scrolls into view or otherwise becomes visible to the user.

    $('#foo').appear(function() {
      $(this).text('Hello world');
    });
This plugin can be used to prevent unnecessary requests for content that's hidden or outside the viewable area.

## Usage with additional options

    $('#foo').appear(function() {
      $(this).text('Hello world');
    },{accX: 50, accY: 100});
Will fire 'appear' event with accuracy 50px in X and 100px in Y

http://bas2k.ru/
