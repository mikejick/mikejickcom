# RLStevenson - Bootstrap Clone of Hyde

RLStevenson was built for people who like the original Jekyll theme [Hyde](https://github.com/poole/hyde) but would like to use [Bootstrap](http://getbootstrap.com).

The theme was built from an empty Bootstrap 3 template with the goal of easy modification for end users. The code is as simple as possible - clearly formatted HTML and a single stylesheet. It's a two column responsive design and currently includes version 3.3.7 of Bootstrap.


The `description` variable will also appear below the title in your sidebar.

The `freetext` will appear in a free paragraph below the Title & sidebarDescription and above the menu links. Set it to "" if you don't want it.

	freetext: 'A optional paragraph of free text. Set to blank in _config.yml to clear...'

### Sidebar Menu Links

Take a look at `_data/menu.yml` file to see how you can add menu items to your sidebar.

### Pagination

Simply set the `paginate:` option in your `_config.yml` file to the number of articles you want to show per page. You may need to use the `bundle install` command with Jekyll 3 to make sure you have the `jekyll-paginate` gem.

Alternatively you can disable pagination by not including the `paginate:` option.

### Color Schemes

Using a theme is as simple as changing the `colorscheme` param in your `_config.yml`.

The themes are:

- Dark Brown (`colorscheme:	'scheme-darkbrown'`)
- Light Brown (`colorscheme:	'scheme-lightbrown'`)
- Green (`colorscheme:		'scheme-green'`)
- Orange (`colorscheme:		'scheme-orange'`)
- Slate (`colorscheme:		'scheme-slate'`)

- Gulf Racing (`colorscheme:	'scheme-gulfracing'`)

#### Creating Your Own Color Scheme

To create your own custom color scheme simply scroll to the end of the `rlstevenson.scss` stylesheet in the `_sass` folder and edit the template we've left there.

We'll happily accept pull requests for quality color schemes.

### Analytics

This theme supports GA & Piwik integration.

For Google Analytics, simply set your UA number in your `_config.yml` file. Example:

	ga:		'UA-123-456'

For Piwik, use the following two variables:

	piwikSiteID:	''
	piwikURL:	''

## Example Config

Here is a full example `_config.yml`:

	##
	# RLStevenson Theme Options
	####

	title:		RLStevenson
	description:	'A Bootstrap based clone of the Hyde theme by mdo.'
	freetext:	'Released under an MIT license - feel free to make pull requests.'
	url:		/
	baseurl:	/
	paginate:	5
	version:	0.1.0
	colorscheme:	scheme-lightbrown

	ga:		'UA-123-456'
	piwikSiteID:	''
	piwikURL:	''

	author:
	 url:		
	 name:		

	gems:		[jekyll-paginate]

	exclude:	['README.md', 'Gemfile.lock', 'Gemfile', 'rlstevenson.gemspec']


## Author

**ExchangeRate-API.com**

- <https://github.com/ExchangeRate-API/>
- <https://www.exchangerate-api.com>

#### RLStevenson Uses Bootstrap

**Bootstrap**

 - <http://getbootstrap.com>


## Inspired By

**Mark Otto** - creator of the Hyde theme

- <https://github.com/mdo>
- <https://twitter.com/mdo>


## Contributing

Bug reports and pull requests are welcomed.


## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
