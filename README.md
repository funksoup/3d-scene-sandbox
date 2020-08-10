
# 3d-scene-sandbox

3d-scene-sandbox is a sandbox for exploring WebVR space creation using A-Frame. A combination of 3D models and 360-degree photospheres are used to create the immersive space.


Live demos: 
https://funksoup.github.io/3d-scene-sandbox/loft.html
https://funksoup.github.io/3d-scene-sandbox/loft-beach.html
https://funksoup.github.io/3d-scene-sandbox/classroom.html

------

## Tech/Framework Used

Project is created with:

* HTML
* A-Frame
* 3D models 


## Usage

Describe the application's functionality:

The application will run in the browser by going to `loft.html`

Navigating the space: 
* on desktop: Use arrow keys or W-A-S-D keys. For example, to walk forward, press the up arrow; to walk backward, use the down arrow. Left arrow to go left, and right arrow to go right. Similarly, you can also use the W key to walk forward and the S key to walk backward; the A key moves left and the D key moves right.
* on mobile: Hold the phone or mobile device in front of you and turn right or left to move right or left. Walk forward or backward to move forward or backward in the space.

Linking 3D assets and photospheres:
Links to the 3D scene/models and 360-degree photosphere are within the `loft.html` file.

For example, the link to the loft scene is witin the `<a-asset-item>` tag:
`<a-asset-item id="loft" src="loft-scene/scene.gltf"></a-asset-item>`

If you'd like to rotate the scene, do so within the `<a-entity>` tag:
`<a-entity rotation="0 180 0" position="-2 0 2">`


The 360-degree photosphere of the lake is what creates the sky and is held within the `img id="sky"` tag:
`<img id="sky" src="loft-scene/lac-barbue.jpg" >`

Additionally, if you'd like to rotate the photosphere/sky, do so within the `<a-sky>` tag:
`<a-sky src="#sky" rotation="0 75 0"></a-sky>`



This gif demonstrates the application's functionality:

<img src = "/loft-scene/images/loft-lake-view.gif" width="600">



## License

This project is licensed under the MIT license.


## Contributors

Forked from Frans' <a href="https://github.com/Frans/A-Frame-Doodles">A-Frame-Doodles repo</a>.

360-degree photosphere of <a href="https://flic.kr/p/P7AuQk">Lac à la Barbue by Martin Bélair via Flickr</a>.

3D design of <a href="https://sketchfab.com/3d-models/apartment-interior-design-vr-ready-ce102c29aaf84a05a8607b2ac947728d">loft space by Marcin Lubecki via Sketchfab</a>.


Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


### Step 1

* Option 1:🍴 Fork this repo!

* Option 2: 👯 Clone this repo to your local machine using https://github.com/funksoup/3d-scene-sandbox.git

### Step 2

* HACK AWAY! 🔨🔨🔨

### Step 3

* 🔃 Create a new pull request using https://github.com/funksoup/3d-scene-sandbox/compare


