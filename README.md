# GitBook Theme for header and footer

This is a theme which adds header and footer in your gitbook.
It adds a logo of your company.
It also adds links to your header and footer if you need.

To use it in your gitbook, add it to your book.json

```
{
    "plugins": ["collapse-expand-chapters"]
}
```

To add links to header and footer, and logo to header

```
{
    "plugins": ["collapse-expand-chapters"],
    "pluginsConfig": {
		"theme-sectionfy": {
			"title": "Git Info book title",
			"logo": "/assets/300-dpi-high-resolution-logo.png",
			"favicon": "/assets/home.png",
			"footer": {
				"copyright-text": "©2017 Resereved for world",
				"links": [
					{
						"title": "Home",
						"link": "/home"
					},
					{
						"title": "About",
						"link": "/about"
					}
				]
			},
			"header":{
				"links": [
					{
						"title": "Home",
						"link": "/home"
					},
					{
						"title": "About",
						"link": "/about"
					}
				]
			}
		}
	}
}
```
