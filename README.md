# [Meny](https://github.com/hakimel/Meny) skeleton for [DocPad](https://github.com/bevry/docpad)
Build a simple site/blog with a 3D transition menu. Utilizes [DocPad HTML5Boilerplate skeleton](https://github.com/docpad/html5-boilerplate.docpad) as a start point.

See th online demo [on Heroku](http://meny.herokuapp.com/).


## Getting Started

1. [Install DocPad](https://github.com/bevry/docpad)

1. Clone the project and run the server

	``` bash
	git clone git://github.com/TravelingTechGuy/Meny.docpad.git
	cd Meny.docpad
	npm install
	docpad run
	```

1. [Open http://localhost:9778/](http://localhost:9778/)

1. Start hacking away by modifying the `src` directory
	1. The src/files/layouts/default.html.eco controls the 2 sections of the page
		1. `meny` - the menu area
		2. `contents` - the page contents, further divided into:
			1. Header - can be provided on site/document level
			2. Article - provided on the page level
			3. Footer - can be provided on site/document level
	2. The menu is built from src/files/layouts/menu.json, where you can select:
		1. The name of the menu item
		2. The class it'd have, if you want it different from the other items (leave empty otherwise)
		3. The URL it'll point to
		4. Whether to open the URL in a new page (deafult: false)
2. Read the instructions in the [Meny repository](https://github.com/hakimel/Meny) to change the parameters and look-and-feel.

See [LICENSE.md](https://github.com/TravelingTechGuy/Meny.docpad/blob/master/LICENSE.md) file for full license info.