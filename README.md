## GIMP Python AutoComplete API for VS Code

This extension covers __1000+__ Functions available in GIMP's Python plugin API. All these functions are now just a few keys away. Simply type some letters of a function name and press `Tab`/`Enter`. The full function signature together with arguments (if any) shall appear at cursor location. Imagine how much typing that would save you.


### Examples

 Text Entered  |  Result
-------------- | -----------------------------------------------------------------------------------------
 `undst`       | `pdb.gimp_image_undo_group_start(image)`
 `flus`        | `pdb.gimp_displays_flush()`
 `thwl`        | `pdb.gimp_image_thaw_layers(image)`
 `gactl`       | `pdb.gimp_image_get_active_layer(image)`
 `itsn`        | `pdb.gimp_item_set_name(item, name)`
 `gau`         | `pdb.plug_in_gauss(image, drawable, horizontal, vertical, method)`
 `cub`         | `pdb.plug_in_cubism(image, drawable, tile_size, tile_saturation, bg_color)`
 `gsa`         | `pdb.python_fu_gradient_save_as_css(gradient, file_name)`
 `fog`         | `pdb.python_fu_foggify(image, drawable, name, colour, turbulence, opacity)`
 `stcm`        | `pdb.script_fu_set_cmap(image, drawable, palette)`
 `bla`         | `pdb.script_fu_blend_anim(image, drawable, value, value, toggle)`


### Tips

* You don't need to type `pdb` or any of the prefixes, like `gimp`, `python_fu`, `script_fu`, etc. Just type a few letters from the "true name" of a function. Observe the patterns used in examples.
* You could use `Tab` and `Shift+Tab` to cycle forward and backward through arguments.
* If you accidentally invoke an undesirable completion, performing a simple Undo `ctrl + z` might be a better fix, rather than manually deleting the unwanted bits.


### Notes

* The data is based upon GIMP 2.10.20 r1.
* All deprecated functions have been filtered out.
* This plugin is released under ... GNU General Public License (v3).


### Other Useful Extensions

* __AutoFill Arrays__ ... https://marketplace.visualstudio.com/items?itemName=civAnimal.autofill-arrays


### Feedback & Comments

* Email:     civanimal@gmail.com
* Twitter:  `civAnimal`


Copyright © 2021 civAnimal
