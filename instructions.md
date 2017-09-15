# Intructions on how to program Vortex Pok3r mechanical keyboard

The POK3R built in 4-layers. The default layer can not be programmed. Only layer 2~4 can be. `Fn`-`Right_Ctrl`/`M`/`<`/`>` and `?` keys are fixed can not be programmed.

- **Step 1:** Choose the layer (`Fn`+`<`,`>` or `?` key) that you want to program.
- **Step 2:** Press `Fn-Right_Ctrl` to enter the programming mode (spacebar right LED steadily lit). 
- **Step 3:** Press the key you want to program (spacebar right LED flashing).
- **Step 4:** Key in the programming content and then press `Pn` (spacebar right LED steadily lit again). 
- **Step 5:** Repeat step 2 and step 3 to program other keys.
- **Step 6:** Press `Fn-Right_Ctrl` to exit programming mode (spacebar right LED off).

## Restore to default

- **Current layer:** Press and hold `Fn-R` (Spacebar left LED is flashing at the after 5 seconds, then the layer will restore to default).

- **All layers:** Press and hold both `Alt` (Right and Left) to clean all layers program key codes that you had programmed. 

**Note:** If you have changed the `Fn` position and forgot where it was, you still can press the original `Fn` (at the right side of the right Alt) position and `R` to restore it.

## Special keys

In order to change the mapping for the `Fn` key, you need to follow these steps:

- Unplug keyboard.
- Flip DIP 4 to "on" (on the back of the keyboard's base).
- Plug the keyboard back in (careful, mistakes here usually require you to reset your layer, losing all that stuff you did before).
- First press `Fn`. Then press `Left_Ctrl` (that `Left_Ctrl` key is now bound to `Fn`).
- Now press `Pn`. Then press `Pn` again, assuming you don't want to move it. If you want to move it, then press that key instead.
- Now flip DIP 4 back to "off".

**Notes:**

- Once you've flipped DIP 4, you must bind both `Fn` and `Pn` or else you can end up with one of them completely unbound which will require a reset of ALL layers.
- Once you move your `Fn` to `Left_Ctrl`, your "real" `Fn` key will automatically function as a Win key. In the case that you move your `Pn` key, it gets replaced by an `App` key.
- `Right_Ctrl` can't be changed to `FN` or `PN`.