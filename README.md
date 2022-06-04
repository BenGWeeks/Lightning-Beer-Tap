# BTCPayServer-LightningBeerTap

## Introduction

This is a Proof-of-Concept for a beer dispenser that dispenses beer on a Bitcoin Lightning payment being received.

## Parts list

To build your own BTCPayServer Lightning Beer Tap, you will need the following items:

| Name                                                                                                                                  | Cost        |
| ------------------------------------------------------------------------------------------------------------------------------------- | ----------- |
| [Lindr Pygmy 20/K Draught Dispenser - Green Line](https://www.draughtbeeronline.com/product/pygmy-25-k-single-tap-dispenser/)     | £454.80     |
| Beverage flow controller                                                                                                          | £12.00      |
| Convertor for Lindr or PortaPint × 1 | £30.00 |
| Sankey Keg Coupler - S Type × 1 | £42.00 |
| Pipeline Professional Purple Beer Line Cleaner 250ml × 1 | £5.99 |
| Sankey 5 litre pressurised cleaning bottle × 1 | £70.80 |
| Mixed Gas Regulator Valve × 1 | £82.80 |

NB This assumes you have a separate existing BTCPayServer, although if needed this could be setup on the same Raspberry Pi as the beer tap using something like Umbrel.

## Threads

A little on threads:

- The beer tap is actually a European style tap, which uses an ANSI Unified Screw Thread (1 1/8-18 or 1.125 UNEF) which is approximately 27mm in diameter.
- The solenoid uses a British style BSP G 1/2"-14 and I found that no offset was required on the threads of the two adapters for that.
- Different printers have varying accuracies of printing. I have set the offset of -0.2mm for the nut that holds the nozzle on. I find this works well on a Prusa MK3S+ that has been calibrated.

For a very good video on threads, please see:

[3D Printed Threads - Model Them in Fusion 360 | Practical Prints #2!](https://www.youtube.com/watch?v=aGWrFeu8Hv0)
