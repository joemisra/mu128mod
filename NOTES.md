## OPENING MU-128

#### TOP
![mu128unscrewtop](https://user-images.githubusercontent.com/326734/200065645-c43b2884-0f19-4ec1-b2d1-2ce3a0f89e24.png)

#### REAR
![mu128unscrewrear](https://user-images.githubusercontent.com/326734/200065658-97478007-1ddf-48a3-8446-5a890fa71c98.png)

#### BOTTOM
![mu128unscrewbottom](https://user-images.githubusercontent.com/326734/200065674-00b2cc38-1ef9-498b-8398-129e169be093.png)

#### SLIDE OPEN

![mu128slideopen](https://user-images.githubusercontent.com/326734/200065994-04ca8ac9-d1b1-4703-942d-4af05d85d691.png)

### BUILDING MU-100-DIT

Depending on if you got this as a kit, or perhaps had them made yourself, this may vary - my kit was smt assembled and only required soldering a header and the optical port.

### INSTALL MU-100-DIT

Your wires may be a different color, I mapped them out with what I had, so just try to match things up.

![MU-100-DIT-rear](https://user-images.githubusercontent.com/326734/199870247-9b8a227f-bedb-4162-ac54-a4b41283a15b.png)

You're looking for the DAC which is IC36, it's to one side next to a big inductor coil. Gather your patience, and carefully solder the wires from the header directly to the pins. It's a very tight spot and a bit tricky with the inductor next to it. I kept some liquid flux handy to help deal with bridges.

![ic36wiring](https://user-images.githubusercontent.com/326734/199870308-f5db9d89-d079-4233-86da-673defeb4fea.png)

![ic36withwires](https://user-images.githubusercontent.com/326734/199870341-220e319b-c2f4-43fd-ab37-331a3d2cc63f.png)

The last wire is MCLK and the pin is on one of the ASICs, I chose to put the wire on a resistor array that pin connects to.

![ra57](https://user-images.githubusercontent.com/326734/199870368-fd08280d-c4b4-4ae4-b28a-46825af40517.png)

![zoomedview](https://user-images.githubusercontent.com/326734/199870376-7a52b0af-d44f-4b70-975a-f2a853cd958f.png)

### TEST

Once the board is wired up, I suggest testing it out before mounting it to the case. A quick way to do this is by hooking up an optical cable to your audio interface or DAC and running the MU-128 demo, which you can access by pressing UTIL and selecting DEMO. If you hear a grand demonstration of XG synthesis fading in, congratulations!

If you hear static as I did, make sure you've bridged DIF0 on the MU-100-DIT board.

### MOUNTING

I chose this spot in the rear, which ended up being a bit too low for the orientation I originally planned, so I ended up flipping the board and added another screw hole...

![opticalclose](https://user-images.githubusercontent.com/326734/200067517-4db47a07-76a4-4320-9bcc-7a2b423b53b8.png)

View

![opticalside](https://user-images.githubusercontent.com/326734/200066850-e4c684b3-4bd6-4f4d-9bf1-f63ebd51b7d6.png)
