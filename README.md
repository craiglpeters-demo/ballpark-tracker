# ⚾ Ballpark Tracker

A simple application used for tracking which MLB and AAA stadiums a [Ballpark Chaser](https://www.ballparkchasers.com/) has been to.

![Ballpark Tracker App](screenshot.png)

---

## How to Contribute

> NOTE: This project requires [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/). Only pull requests that statisfy the [ESLint rules](https://github.com/codespaces-contrib/ballpark-tracker/blob/master/.eslintrc.json) will be accepted. 

Contributions to this repository have been made easy! Simply click the "**Code > Open with Codespaces > New codespace**" button above to have a complete development environment, including Node.js, MongoDB, and all other dependencies, spun up on your behalf.

> NOTE: You can optionally setup a `dotfiles` repo so that your codespaces feel ergonomic and immediately familiar. If you dont have a `dotfiles` repo, then [generate one](https://github.com/codespaces-contrib/dotfiles/generate) with the name `dotfiles` before moving on.

### Things to Try:

- [ ] **Debug the App**: Open `index.js` and place a breakpoint on any line. Press `F5` to start the debugger. The breakpoint will be hit, and you can explore the state of the application in the `Variables`, `Watch`, and `Call Stack` panels. 
- [ ] **View the App**: Continue the debugging session by pressing `F5` again. The application will launch in a new tab.
- [ ] **Make a Change**: Open `views/index.ejs`. Change the text on line 31 (`<span>Ball Park Tracker</span>`) and save the file. View the app, and it will have automatically updated to show your change.
- [ ] **Try the Terminal**: Press ``Ctrl+Shift+` ``to open a new terminal window. Try entering commands like `node -v` or `uname` to interact with the codespace. If you setup a `dotfiles` repo, you should see your terminal setup fully intact. If you're using the sample dotefiles, then check out the awesome `PS1` prompt and/or try running `l` or `cls` (these are custom aliases!).
- [ ] **Install an Extension**: Press `Ctrl+Shift+X` to open the Extensions bar. Search for `RandomFractalsInc.geo-data-viewer`, and press `Install`. Then, open the `public/data/ballparks.geojson` file. With the file open, press `F1` to open the command pallet, search for and run the `Geo: View Map` command to see the extension viualize the `.geojson` information in the file.

---

### Links

- [Sports Venue Datasource](https://hifld-geoplatform.opendata.arcgis.com/datasets/major-sport-venues/data)
- [Sports Venue Usage Datasource](https://hifld-geoplatform.opendata.arcgis.com/datasets/major-sport-venues-usage/data)
- [Sports Logo Compilation](http://www.sportslogos.net/)
- [Base App](https://docs.microsoft.com/en-us/azure/azure-maps/tutorial-create-store-locator)
