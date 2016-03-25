Welcome to the Playground. Home base for all references to trendy frameworks. Learn't structure and Practiced methods.

Have fun Nigel!

- npm install -g yo bower grunt gulp-cli		/// NO SUDO ON THIS?
- yo --version && bower --version && grunt --version && gulp-cli --version
- npm install --global generator-webapp
- run: yo		/// in iTerm for project generation & dependencies
	- gulp serve			/// Launch project to local
	- gulp serve:test		/// to run the tests in the browser
	- gulp 					/// to build your webapp for production /// Build Dist folder
	- gulp serve:dist 		/// to preview the production build

- Node.js
	- Install Yeoman /// Schaffolding tool Index, App, Style folder ///


- Bower   /// Package Manager | Plugins, Libraries (ie: animate.css)

- Grunt   /// Task runner, Reloading, repeative stuff
	- Install Grunt
		- npm init
		- npm install grunt
		- npm install grunt --save-dev
		- sudo npm install -g grunt-init
		& sudo npm install -g grunt-cli

		- Live reload
		- Build to concat & min JS&CSS
		- Create Dist Folder for deployment
		- Build Controller to deploy to heroku


Yeoman, grunt/gulp, deployment <- Deploying only /dist!

- yo in command line from _ _ dirname
	◉ webapp
	◉ angular 1
	◉ karma

- Config to:
	◉ Sass
	◉ Bootstrap
	◉ Modernizr

- gulp serve /// launch project to localhost

Best Practices for DEPLOYMENT

	- Install dependencies: npm install --global yo gulp-cli bower
	- Install the generator: npm install --global generator-webapp
	- Run yo webapp to scaffold your webapp
	- Run gulp serve to preview and watch for changes
	- Run bower install --save <package> to install frontend dependencies
	- Run gulp serve:test to run the tests in the browser
	- Run gulp to build your webapp for production
	- Run gulp serve:dist to preview the production build
