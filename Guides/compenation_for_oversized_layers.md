### Setting layer size compensation - Elephants Foot

Elephants foot is the oversized initial layers that are caused by the longer exposure time used for these layers. You can enable compensation in the slicer to help reduce these layers. With some calibration you can reduce these to the point where you can almost completely eliminate these layers.

Elephants foot is not much of an issue if you use rafts and supports lifted from the plate so that they are printed using the normal layer times.

If you print objects directly on the plate then you may want to compensate for the oversized layers caused by burn-in so that your layers are a more uniform, and expected, size.

1. Go to the menu for `File` - `Preferences`
1. Ender the `Printers and resins` menu.
1. Select your printer and click the 'cog' icon beside the resin profile you want to set compensation on.
1. Ender the value you want to compensate for in the box for either burn in or normal layers.
1. Select if you want the compensation to apply to supports as well.

#### Figuring out your ideal compensation value

The amount of compensation needed varies between resins, exposure times and even environmental factors such as ambient temperature and if your printer is subject to vibrations (such as from unstable surfaces or being in a location that it might vibrate from what happens around it).

1. You need to print a part that shows the oversized layers.
1. With a set of calipers or other precision measuring tool measure the size of the initial layers.
1. Measure the normal layers just above the burn-in ones.
1. Calculate the difference between normal and burn-in layers by subtracting normal size from burn-in size.
1. Half the value you have.
1. Enter the value you have into the compensation field.

*** Note: Because this value will change due to various factors it is hard to get it perfect for all your prints and resins used ***


66633281UV405380C
