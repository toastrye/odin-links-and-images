# odin-links-and-images

## Description

The odin-links-and-images project uses an "a" element as an anchors to create hyperlinks for both absolute and relative paths. Links are anchored to clickable links such as "About" or "About the odin project". Absolute paths point to specific location on the web. This means a domain name is needed, usually starting with "https://". Relative paths are relative to the current page or directory. The "target" attribute uses the value "_blank" to open the link in a new tab. Fore this project we focus on relative hyperlinks. Attribute and value rel="noopener noreferrer" prevents potential security risks. the img (image) element uses the src (source) attribute to call upon an image from a relative path. The alt value gives a description for screen readers.

In the about.html file we have a relative link as well but we have to move up in the directory to be able to access the images compared to that from the index.html file.