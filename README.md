# dyesub-notes-clean

## Understand your printer and software

<img align="right" src="img.jpg"> In order to print dye sublimation illustrations correctly, you need to have a basic hang on **color management and print quality** at a software and hardware level. You need software that is able to manage color profiles. Even though most pictures are encoded with red, green and blue channels, printing is a different story. It's not just about conversion to cyan magenta yellow and black, all printers and dyes are different.

To use a basic example, let's say you're an artist, and you are mixing blue and yellow paint to make green. Take two blues from two paint manufacturers that look the same, and in practice you will get two different blues. Same goes for yellow. If you were to mix the same quantity of yellow and blue, what kind of green will it produce? Does it produce the same colors when applied to each differnt types of canvas paper?

These differences show up with printer ink and printers themselves, and even monitors. It is not possible to apply a simple mathematical formula to convert RGB to all CMYK, the physical medium is important.

This is even more important with dye sublimation ink. Traditional office printer inks are made for printing on office paper, and the paper will be read by a human. Dye sublimation ink is made to look good not when it is printed, but when it is sublimated onto a real object. Your pictures will look like crap on dye sublimation paper because it is not meant to be sitting on dye sublimation paper. **You will have no way to know if your picture looks good unless you sublimate it**.

Color profiles lets us transform a picture into instructions on how to properly balance the specific inks so that when it is printed by a specific printer on a specific type of paper, it will look good. When experimenting with traditional ink, you will end up with things like this:
- washed out colors
- too bright colors
- two shades of the same color that look very different on screen will look identical when printed

So it is important knowing how to print good pictures on traditional paper with traditional ink, before switching to dye sublimation ink. Experiment with your printer and software. Tweak printer settings, like paper type, which will affect print speed.

## Ink and paper

If your **dye sublimation ink** come in bottles, don't load them into your cartridges or continuous ink supply system unless you have tested each bottle individually by putting a droplet onto the correct side of a dye sublimation paper, and then attempting to sublimate it on a testing medium, like polyester fabric.

On a personal experience, I have received 4 bottles of each color, all labelled as heat transfer ink, but it turned out the black ink is not sublimation ink. It is unpleaseant to siphon all the black ink out of the CISS kit.

**Dye sublimation paper** has a specific side to print on which is coated with chemicals. It is the side that feels smoother to the touch, and looks less grainy when illuminated by a light source sideways. When loading it in the printer tray, double check which side the printer will print on.

Also, remember to print your pictures mirrored, and if you are going to cut the paper, don't cut it tight fit as the ink may steam out and leave scortch marks on areas that were not covered by the paper; leave 5mm of paper at least around the edges.

## Heat



# dyesub-notes

Personal notes on dye sublimation processes

Things to get:

- A compatible object to dyesub on
- Dye sublimation paper
- A dye sublimation compatible printer
- A dye sublimation compatible cartridge, usually a CISS kit
- Dye sublimation ink
- Proper software to print with advanced color profiles support and custom ICC profiles

## Dye sublimation paper

Dyesub paper has a specific side coated with chemicals, which is the face that needs to be printed on.

- Print on the whiter side of the dye sublimation paper (the side that feels smoother to the touch, and looks less grainy when illuminated by a light source sideways)
- When loading in the printer tray, double check which side the printer will print on
- Do not cut tight-fit the paper to the printed area, leave at least 5mm around the edges. The ink will steam out of the paper, which will leave dye marks on areas that were not covered by the paper

## Dye sublimation ink

Test the ink before putting it in the cartridges. Don't trust the labels of the bottles, check on your own if you have received proper ink that sublimates when heated.

- If the ink come in bottles, put a droplet from each bottle onto the correct side of dyesub paper, and try to sublimate it onto polyester fabric
  - It might turn out that one of colors will not sublimate properly, especially the black ink
  
## Testing the printer

Before installing any ink, train yourself in using the printer with normal ink in order to get a hang on how color management in Photoshop works (ICC profiles), and how the printer driver works.

Once the dyesub ink is installed, the colors will look completely different on paper and it becomes very difficult to figure out the print quality.

- Always set the paper settings to photo quality in the printer settings
- No matter what ICC setting is set to, and no matter what the paper is, when printing with dyesub ink, colors will appear washed out when printed
  - On dyesub paper, colors become brighter and more vivid after heating (dye turning into gas)
- Remember to mirror the image

## Fabrics

- Dyesub will not work as well on 100% cotton
- Use at least 50% polyester (not sure about the percentage though)

## Plastics

- Find out the plastic type before trying anything
  - ABS has a very low melting point, lower than the heat necessary for dyesub, never try dyesub on ABS ever
  - PBT might melt around 220 degrees Celsius, check the temperature of the heat press or heating element beforehand

## Applying the heat

- As much as possible maximize physical pressure and minimize thickness separation between the heating element and the dyesub paper. If the subject being dyed is not flat, then find a way to both apply pressure and transfer heat to the subject being dyed. Not applying enough pressure or using different thicknesses will lead to differences in dye absorption
- Experiment with different cooking durations. Overcooking can make black color turn brown
- Moisture will cause unwanted spreading of the ink
- After applying the heat, remove the paper firmly and quickly to avoid leaving a ghost image

## Maintenance

- Ink from a dyesub printer is subject to these aging effects
  - Drying if the printer is not used often enough
  - Evaporation
  - Waste ink saturation
