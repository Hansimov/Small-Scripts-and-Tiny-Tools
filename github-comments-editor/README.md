This userscript works at `https://github.com/*/issues/*`.
It enhances the capabilities of the original GitHub issue comments editor.

**Main features of this userscript:**

* Display the area of `Write` and `Preview` side by side at the same time
* Real-time preview the markdown of the writing content
* Freely resize the width of comments container with a slider (on the right of the `fork` button)
* Hide/show the sidebar with a button (on the right of the slider above)
* Remember the users' preferences at last time
* Auto-resize the textarea when the contents of comments are changed
* Show the originally hidden editor toolbar while previewing

**Todo:**

* Appearances:
    * [ ] Choose an appropriate icon
    * [ ] Modify the layout of the slider and button
    * [ ] Have a try at GitHub Wide
    * [ ] Hide `Preview` tab
    * [ ] Remove the `Styling with Markdown is supported` text
    
* Functions:
    * [ ] Apply this userscript to more GitHub websites
    * [ ] Clear preview content after the new comment is submitted
    * [x] Synchronize this userscript with Tampermonkey
    * [ ] Add a word counter
    * [ ] Improve markdown preview engine:
        * [x] Take a look at the preview render extension: https://github.com/DrewML/octo-preview
        * [ ] Update preview with fixed interval or after two or three inputs
        * [ ] Remove the `Loading preview ...` page
        * [ ] Use a new engine: https://github.com/markedjs/marked
    * [ ] Fix potential bugs
    
* Documents:
    * [ ] Add installation tutorials 
    * [ ] Add GIFs to show effects

* Miscellaneous 
    * [ ] Reply to Mottie's comment

**References:**

* https://github.com/Mottie/GitHub-userscripts/pull/38