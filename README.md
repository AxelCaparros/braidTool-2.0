# braidTool-2.0
This is a maya autodesk tool that facilitates creating braids for groom purposes that can later be used for tube grooming as well.
*IMPORTANT* Make sure to run the script twice as some of the window sliders for clumpTwist and clumpWidth only activate this way.
*Run through the STEPS top to bottom (order of buttons is top to bottom)*

(copy paste script directly to python shell in MAYA) 

1.Create a nurbCurve (this is up to you on how you do it)
2.Hit "Create Dynamic Curve" (this creates dynamic curve out of your curve)
3.Hit "Make Braid" (creates a braid using paintFX)
4.Hit "PaintFx Braid Curves" (it will turn them back into curves)
5.Run "curveExtruder" script in MEL Maya shell
6.Now with the "curveExtruder" script you have your 3 curves for turning into nurbTubes
7.Hit "NURBS to Poly Preset" (to get your polygon tubes going)

**The History should retain all the way even after using the curvesExtruder script (not mine) to play even more the final look.
**Also the hairsystem is active with the follicles created from your curve.


Have fun and play around with it. :)
