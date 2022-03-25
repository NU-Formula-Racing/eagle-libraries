# eagle-libraries
This is the repository for all the commonly used EAGLE libraries in our designs.  
Before adding any new libraries, please ensure that they have all of the following:
* File name that helps people understand what it's for
* Library description that expands upon the file name & provides more helpful information
    * Open the library -> click "Library" in the top-left of the screen -> click "Description" -> enter your description using HTML syntax
* All the obligatory stuff (device, footprint, symbol)
* A functional 3D package
    * The vast majority of the time, a pre-existing 3D package will be available online so you won't need to CAD
* Silkscreen in the footprint that helps you determine orientation of the component
    * Make sure you're adding the lines to the right layer (should be tPlace)

## Libraries
1206cap: 1206 capacitor library  
1206res: 1206 resistor library
