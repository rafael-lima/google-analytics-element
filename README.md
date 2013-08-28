# &lt;google-analytics-element&gt;

Web Component wrapper for Google Analytics code using Polymer.

> Maintained by [Cesar William](https://github.com/cesarwbr).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130711/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/google-analytics-element.html">
	```

3. Start using it!

	```html
	<google-analytics-element domain="example.com" code="UA-XXXXX-Y"></google-analytics-element>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`domain`   | *string*                  | `example.com`       | Lorem ipsum
`bar`      | `abc`, `def`, `ghi` 	   | `foo`               | Lorem ipsum
`height`   | *int*                     | `100`               | Lorem ipsum


> See Google Analytics [official documentation](https://support.google.com/analytics/?hl=pt-BR&utm_medium=et&utm_campaign=pt-BR&utm_source=ww-pt_BR-et-b2bfooter_analytics).

## History

* v0.0.1 August 28, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)