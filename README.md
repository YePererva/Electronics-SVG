# Electronics-SVG
Vector images of electronic components / boards created in InkScape.

## Image structure
All images are multi-layered based on usage:
1. Background - used for original raster image of device (photo, etc.)
2. Outline - outer contour of board
3. Pads - pads and holed for pins
4. Silk screen - all images on silkscreen
5. Silkscreen text - text (!only) on the silkscreen
6. Components - all components on the board. If there are several boards, which shares the topology - all common (mutual) components. Components, which differs from version to version are separated with appropriate name as individual layer (like for Nucleo32 boards)
7. Jumpers - all jumpers. If they define function mode, the switched position is separate layer (like operation / flashing mode for STM32 BluePill)
8. Pins - pins for positioning in breadboard
9. Headers - stacking headers

There could be also separate layer for individual components (like JTAG socket, etc.)

## Acknowledgements
Some components used for making this boards were taken from opensource locations or other repositories, which allowed such usage. Thanks them! some of them are listed below:
- [Adafruit](https://github.com/adafruit)
- [SparkFun](https://github.com/sparkfun)
