### Themes Folder
* This folder contains Application specific themes.
  * `ApplicationStyles.ts`: It contains the common styles of the project. Any styles which are used in two or more files must be kept inside this file.
  * `Fonts.ts`: It contains the font declaration and some basic font styles. All the third party fonts must declared in this file.
  * `Metrics.ts`: It contains common dimensions of the project. Eg. basic vertical and horizontal margins of all the screens.
  * `Colors.ts`: It contains all the colors used inside the project. All the colors to be used in the project must be defined in this file.
  * `Images.ts`: It exports all the local images of the project. Any local image that is to be used in the project must be imported in this file first and then can be used from it.
  * `index.ts`: All the above files are exported using this file. It will reduce the import code for each file. Eg. Fonts can be imported by `import { Fonts } from '../Themes'`.