**Image Gallery**

This is a simple image gallery web app that allows users to upload images, add captions, view images fullscreen, and delete images.

**Features**

Upload images from local device
Add captions to images
View images full-screen with zoom
Delete images
Progress bar loading animation


**Usage**

To use the gallery:

-Click the "Add Image" button to upload an image from your device

-Images will display in a responsive grid layout

-Click on an image to view it fullscreen

-Use mouse wheel to zoom in/out on the fullscreen image

-Click again to exit fullscreen mode

-Double click on the caption to edit it

-Click the "Delete Images" button to enter delete mode

-Selected images will be highlighted

-Press delete key to delete selected images

-Page will show a loading animation on startup while images load



**Built With:**

-HTML

-CSS

-JavaScript

-LocalStorage API

The gallery displays a grid of images uploaded from local device. When an image is clicked, a fullscreen view is launched using a cloned image node.

Captions can be added to images on upload, and edited after the fact.

Image data and captions are stored in LocalStorage to persist across sessions.

A loading animation is displayed on startup while the image data is retrieved from LocalStorage and rendered.
