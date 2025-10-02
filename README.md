# OCC UIKit Custom Theme

---

The purpose of this project is to produce a customized version of the UIKit front-end CSS and JS framework for use with the Canvas Learning Mangagement System.

## How to Customize

The occ-theme.less file is where native variables are overridden and new classes can be made. Then run `pnpm compile` and find the `/dist/css/uikit.occ-theme.min.css` file. Use this file along with the `/dist/js/uikit.min.js` file in your Canvas theme.

## How to Work with UIKit

Clone the UIKit repository into a new project on your local machine. Create a `/custom` folder in your project's root directory. Then clone this repository into the custom directory you just created. Run `pnpm install`. You can now run the `pnpm compile` command.
