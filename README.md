# Plotters crate

https://docs.rs/plotters/0.3.1/plotters/index.html

Basis of useable plotting module, where we can pass collections of coords to create a line series, and to specify drawing of points.

Since we are aiming to connect every coord with a line, to investigate 'shortest path' algos, we should probably combine point & line drawing into one action. But, let's do this in another repo & leave this as is, since this repo is a useful template for other plotting projects.

Note: Examples presume (without mentioning) that the image path directory already exists. If it does not, the image file will not be created (saved).