# Filter-Copy Note Levels: *Plugin for MuseScore 4.x*
 A MuseScore 4.x plugin that extends and copies selection to notes with the similar chord-level(s) and/or voices over a selected range.  

 ## Usage
 - Select a note at a chord level(s) you wish to filter/select/copy.
   
 - Select an end note to which you want the selection extended.
    
 - If no end note is selected then, the selection will be extended to cover the current measure.

 - Running the plugin twice consecutively will extend the selection to the whole staff.
   
 - The selection is automatically copied to clipboard.
   
 - Just paste normally using Ctrl+V in any measure you like.  

 - The plugin supports multiple selections across multiple staves and voices simultaneously. 

 - However, if the selected notes are not in adjacent staves, the plugin will only filter/select, but not copy (limitation from Musescore not allowing copying non adjacent staves).

 ## Download and install
 You only need to download "Filter-Copy Note Levels.qml" and put it in your MuseScore plugin folder.  
 For more details on installation see [link](https://musescore.org/en/handbook/3/plugins#installation).

  ## Demo
 https://github.com/Ash-86/Select-Copy-Chord-Levels/assets/108089527/d7b92861-de82-4efb-9167-f7e60b75e5b6

 ## Configuration options
 You can choose the counting direction the code follows. Just comment out the corresponding ***"var counting"*** at the beginning of the code to suit your preference. 
 This is useful when having chords with different sizes.
 
 *example:  
 If var counting= "up", you can select 2nd notes from the bottom.*
 
 ![up](https://github.com/Ash-86/Select-Copy-Chord-Levels/assets/108089527/eab7cf17-fb43-4bd8-bd2d-ba731680d3f2)

*If var counting= "down", you can select 2nd notes from the top.*
  
 ![down](https://github.com/Ash-86/Select-Copy-Chord-Levels/assets/108089527/cddca06c-08fc-498e-8975-93858a3d651b)




 In both cases, top and bottom notes can be selected. 
 
 ## Feedback
 Please feel free to send any suggestions, bug reports, or just let me know if you find the plugin helpful  :)

 ## Support 
 Making this plugin took time, effort and love.   
 If you appreciate this plugins and find it helpful, you can buy me a beer
 [here](https://www.paypal.com/donate/?hosted_button_id=BH676KMHGVHC8) :)


