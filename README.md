# Firefox CSS Tweaks:

A list of tweaks I use for tweaking the UI of Firefox to match my style and mood.


### Extension Alert Fix

Fixes the extension box in the URL Bar:
```css
/*==Extension-alert-fix==*/
#identity-box > .identity-box-button,
.tab-secondary-label {
  display: none !important;
}
```

### Removing the Caption Buttons

Allows you to remove the window control buttons:
```css
/* MIN MAX CLOSE Remove */
#TabsToolbar > .titlebar-buttonbox-container {
  visibility: collapse !important;}
```

<hr>

## Contributing:

If you wanna contribute to this repository, then just edit `readme.md` and open a pull request, and specify the function of the tweak, and an appropriate reference image. We'll merge it after that.
