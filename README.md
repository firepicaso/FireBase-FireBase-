<h1> Atom keyboard shortcuts </h1>
<h3> Move cursor UP Down Left Right without arrow keys in Atom </h3>
______________________________________________________________________________________________________
<h3> Setting keyboard shortcuts for fast coding </h3>

<h2> From atom window click on File >> Settings >> Keybindings >> copy the code for "editor:move-to-previous-subword-boundary" then open the keymap file from file and paste on top and then change the shortcut keys. add the other shortcut keys one after another as shown below  </h2>
<h5> dont copy paste directly from this window </h5>


<h4>'atom-workspace atom-text-editor':</h4>
<h4>'alt-shift-j': 'editor:move-to-previous-subword-boundary'</h4>
<h4>'alt-shift-l': 'editor:move-to-next-subword-boundary'</h4>
<h4>'alt-j': 'core:move-left'</h4>
<h4>'alt-l': 'core:move-right'</h4>
<h4>'alt-i': 'core:move-up'</h4>
<h4>'alt-k': 'core:move-down'</h4>
<h4>'alt-u': 'editor:move-to-first-character-of-line'</h4>
<h4>'alt-o': 'editor:move-to-end-of-screen-line'</h4>

  
______________________________________________________________________________________________________

<h5> Now see the magic ! </h5>
<h5> alt + (i, k, j, l) is normal movement just as UP Down Left Right respectively </h5>
<h5> alt + (u, o) works as Home and End which moves the cursor to the beginning of the sentence or the end </h5>
<h5>  and finally alt + shift + (j, l) moves the cursor subword-wise left or right </h5>
