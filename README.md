# jQuery KBox plugin

Display a pop box on page...

## Usage:

Step 1: Add jquery.js & jquery.kbox.js to your html file:

	<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
	<script type="text/javascript" src="jquery.kbox.js"></script>

Step 2: Add a anchor element to your html file, like this:

	<p>click <a id= "test" href="#">here</a> to test the plugin...</p>

Step 3: Call the KBox.show function like this:

`$.KBox.show()` takes a single string argument - the content you want to show, like this:

	$.KBox.show('jQuery is a cross-browser JavaScript library designed to simplify the client-side scripting of HTML. It was released in January 2006 at BarCamp NYC by John Resig. Used by over 55% of the 10,000 most visited websites, jQuery is the most popular JavaScript library in use today.');

Or takes a single Object argument, like this:

	$.KBox.show({
		boxContent   : 'jQuery is a cross-browser JavaScript library designed to simplify the client-side scripting of HTML. It was released in January 2006 at BarCamp NYC by John Resig. Used by over 55% of the 10,000 most visited websites, jQuery is the most popular JavaScript library in use today.',
		boxWidth     : '400px',
		boxHeight    : '200px'
	});

All default settings:

	$.KBox.show({
	boxContent   : 'jQuery is a cross-browser JavaScript library designed to simplify the client-side scripting of HTML. It was released in January 2006 at BarCamp NYC by John Resig. Used by over 55% of the 10,000 most visited websites, jQuery is the most popular JavaScript library in use today.',
		boxWidth     : '400px',
		boxHeight    : '200px',
		boxBgColor   : '#fff',
		boxSdColor   : '#666',
		boxFontFamily: 'Georgia',
		boxFontColor : '#000'
	});

## Screenshot

![jQuery KTwitter plugin widget](https://github.com/libuchao/KBox/raw/master/screenshop.jpg)