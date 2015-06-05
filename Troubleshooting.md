# Troubleshooting #
## Common errors ##

If you are having trouble running the plugin, start by checking these basic points:

  * The slider main container must have defined width and height values in the CSS (height can be null if the "freeheight" option is activated). Otherwise, default values (500x350) will be taken.
  * The CSS class names over the HTML tags must be respected (check the <a href='#htmlelements'>HTML elements</a> section).
  * If you are testing a gallery, the panels number must be equal to the navigation thumbnails number.
  * If you are imbricating sliders, they must have different 'cssprefix' values.
  * Globally, many errors come from CSS bugs. In doubt, checking the demos CSS file might help.

## Debug mode ##
To help you finding what's wrong with your plugin installation, you can activate the debug mode option:
debug:true
The script will stop on errors during its execution and display codes:

  * `Error #01`: (HTML issue) At least a carousel or a panel set must be found in the HTML.
  * `Error #02`: (CSS issue) You must define the slider height or width values in the CSS. Default values are taken if not.
  * `Error #03`: (HTML issue) If you are testing a gallery, the panels number must be equal to the navigation thumbnails number.
  * `TypeError: this.Counter is not a function...`: (JS issue) The Slider Kit Counter add-on is missing.
  * `TypeError: this.DelayCaption is not a function...`: (JS issue) The Slider Kit DelayCaption add-on is missing.
  * `TypeError: this.Timer is not a function...`: (JS issue) The Slider Kit Timer add-on is missing.
  * `TypeError: this.ImageFx is not a function...`: (JS issue) The Slider Kit ImageFx add-on is missing.
  * `DelayCaption #01`: (HTML issue) No textbox found in the slider.
  * `DelayCaption #02`: (CSS issue) The textbox element must have specified width/height values in the CSS.
  * `DelayCaption #03`: (JS Info) 'obj.options.autospeed' option value has been increased to fit animation duration.
  * `ImageFx #01`: (HTML issue) No image was found in the panels container. ImageFx only applies on images.
  * `ImageFx #02`: (JS issue) The image effect name doesn't exist. Default name is taken instead.
  * `ImageFx #03`: (HTML issue) No image was found in the current panel container. The transition is aborted.


## Report an issue ##
If you find an issue using Slider Kit, thanks to <a href='http://code.google.com/p/sliderkit/issues/list'>report it</a>.

## Online help ##
If you still can't find a solution to your problem, try the <a href='http://groups.google.com/group/sliderkit'>Slider Kit jQuery plugin Google Group</a>.