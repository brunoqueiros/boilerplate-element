# &lt;youtube&gt;

TODO: Write a project description

> Maintained by [Your Name](https://github.com/yourname).

## Demo

![My Element]()

> [Check it live](http://brunoqueiros.github.io/youtube-element/).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="lib/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/youtube.html">
	```

3. Start using it!

	```html
	<youtube></youtube>
	```

## Options

Attribute    | Options         | Default                                    | Description
---          | ---             | ---                                        | ---
`src`        | *string*        | `http://www.youtube.com/embed/M7lc1UVf-VE` | URL specifies the content that the player will load 
`theme`      | `dark`, `light` | `dark`                                     | Player controls theme
`width`      | *int*           | `640`                                      | The width of the player
`height`     | *int*           | `390`                                      | The height of the player
`showinfo`   | `0`, `1`        | `1`                                        | Display information like the video title and uploader before the video starts playing.
`loop`       | `0`, `1`        | `0`                                        | Loop the video
`end`        | `0`, `1`        | `0`                                        | This parameter specifies the time, measured in seconds from the start of the video, when the player should stop playing the video
`color`      | *string*        | `red`                                      | The color that will be used in the player's video progress bar
`autoplay`   | `0`, `1`        | `0`                                        | Sets whether or not the initial video will autoplay when the player loads
`autohide`   | `0`, `1`, `2`   | `2`                                        | This parameter indicates whether the video controls will automatically hide after a video begins playing


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 August 21, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)