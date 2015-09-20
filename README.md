# exif-image-auto-rotation
Auto rotate uploaded images based on their exif data.

Example 1 - pass an array of image paths to auto-rotate:
```
var autoRotate = require('exif-image-auto-rotation');
var images = [
	'/var/image_uploads/image_one.jpeg',
	'/var/image_uploads/image_two.jpeg',
];
autoRotate( images );
```

Example 2 - pass a single image to correct
```
var autoRotate = require('exif-image-auto-rotation');
var images = [
	'/var/image_uploads/image_one.jpeg',
	'/var/image_uploads/image_two.jpeg',
];
autoRotate( images );
```

Example 3 - run callback after rotation
```
var autoRotate = require('exif-image-auto-rotation');
var images = [
	'/var/image_uploads/image_one.jpeg',
	'/var/image_uploads/image_two.jpeg',
];
autoRotate( images, function(){
	//something really cool!
} );
```