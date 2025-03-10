## [0.5.2] - 2021.03.25
* Fix typo on metadata files and update README.md.

## [0.5.1] - 2021.03.25
* Enable to set initial cropping area with `initialArea` property.

## [0.5.0] - 2021.03.18
* Enable to configure corner Dots with whatever Widget.
* Enable to configure cropping mask colors and base colors.

## [0.4.0] - 2021.03.18
* Enable to change original image via `CropController`
* Add callback when cropping area moves.
* Enable to control cropping area programmatically via `CropController`
* Fix bug that wrong cropping area is calculated when image is smaller than display.

## [0.3.0] - 2021.03.17
* Add example project in `example` directory.

## [0.2.3] - 2021.03.17
* Fix a bug of wrong cropping rect when vertically longer image is set.
* Make the size of dots smaller.

## [0.2.2] - 2021.03.16
* Rename `isCircle` flag into `withCircleUi`. This flag no more affects the result of the shape of cropped images.
* Add `CropController.cropCircle` method so that images are cropped with circle shape.

## [0.2.1] - 2021.03.16
* Enable to pass `isCircle` property to crop with circle shape. This flag can also be changed via `CropController`.

## [0.2.0] - 2021.03.16
* Enable to change `aspectRatio` dynamically via `CropController`.
* Enable to set `initialSize` via `Crop` constructor.

## [0.1.4] - 2021.03.16
* Bug fixed. and improve performance.

## [0.1.3] - 2021.03.16
* Fix not to block UI update when cropping image.

## [0.1.2] - 2021.03.15
* Enable to fix aspect ratio if `aspectRatio` property is given.

## [0.1.1] - 2021.03.14
* Fix README.md

## [0.1.0] - 2021.03.14

* prevent Dot controls from exceeding thier horizontal / vertical limits.

## [0.0.6] - 2021.03.12

* change the type of `image` parameters to `UInt8List`.
* return cropped data via `onCropped` callback.
* now Crop Widget is available at any place and any size.

## [0.0.5] - 2021.03.12

* Enable controling crop actions via CropController.

## [0.0.4] - 2021.03.12

* Rename classes.

## [0.0.3] - 2021.03.12

* Add first implementation of crop_your_image.

## [0.0.2] - 2021.03.12

* Update information about this package.
