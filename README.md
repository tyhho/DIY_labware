# 3D Printable DIY Labwares

This is a repository for some DIY labwares which I have created to faciliate my experiments.

## Aspirator Stand

<img src="https://github.com/tyhho/DIY_labware/aspirator_stand/blob/master/images/AS_FrontView.jpg" alt="Aspirator Stand Front View" width="300"> <img src="https://github.com/tyhho/aspirator_stand/blob/master/images/AS_BackView.jpg" alt="Aspirator Stand Back View" width="300">

This aspirator stand is designed to aid researchers who have the need to pipette a layer of liquid that was fractionated by centrifugation - a process which often the demands the pipetting to be done slowly and stably so as to avoid perturbing the fractionated layers.

Please open the folder "aspirator_stand" for more information

## Colony Picking Assistant

<img src="https://github.com/tyhho/DIY_labware/blob/master/diy_labware_images/ColonyPickingAssistant.jpg" alt="Aspirator Stand Front View" width="300"> <img src="https://github.com/tyhho/aspirator_stand/blob/master/images/AS_BackView.jpg" alt="Colony Picking Assistant Cover" width="500">

A rack for tip rack insert to ease the process of manual colony picking.

Files:
* Colony Picking Assistant_200 uL tips & flat-bottom plates.rsdoc
* Colony Picking Assistant_200 uL tips & flat-bottom plates.stl

Recommended print setting: 20% infill, Cubic, Brim



This aspirator stand is designed to aid researchers who have the need to pipette a layer of liquid that was fractionated by centrifugation - a process which often the demands the pipetting to be done slowly and stably so as to avoid perturbing the fractionated layers.

Usually, a researcher will use a plastic Pasteur pipette / pipetteman with a tip attached. He/she will hold it steady above the tube while keeping the pressure on the piston / bulb, gradually low it so that the tip is submerged at the layer of interest, and then slowly releasing the piston / bulb while trying not to introduce motion that would disrupt the layers and cause remixing of the fractionated layers. This is an exacting procedure that requires quite an amount of skill and training. It is especially painstaking if the researcher has multiple samples that need to be processed in the same manner. 

This aspirator stand attempts to overcome this issue by "decoupling" the vertical motion of the pipette and the suction of the layer into two physically and temporally independent steps. When the aspirator is used, the researcher first places the centrifuged tube onto the designated slot on the **base** and removes that cap. The researcher then attaches an exchangeable glass pipette to an rubber insert, which hangs on the **lift** of the stand. The **lift** is held in place by magnets but can be slided up and down along a **magnetic rail (a magnetic steel sheet)**. The top of the glass pipette is connected air-tight to the rubber insert, then through a plastic tubing, to a syringe. Once the researcher set the Z-position of the glass pipette in place, he/she can then release hands from the **lift**, and then pull the syringe to suck up the liquid layer of interest without perturbing the Z-motion. Finally, the researcher pushes the **lift** upward, removes the source tube and replaces it with a collection tube, pushes the **lift** down again, and then pushes the syringe such that the pipetted liquid layer empties into the collection tube.

<img src="https://github.com/tyhho/aspirator_stand/blob/master/images/AS_Action1.jpg" alt="Aspirator Stand in action 1" width="300"> <img src="https://github.com/tyhho/aspirator_stand/blob/master/images/AS_Action2.jpg" alt="Aspirator Stand in action 2" width="300">

The stand was primarily designed for a 15 mL Falcon centrifuge tube but should also work with a 50 mL Falcon centrifuge tube. To avoid cross contamination between samples and the tubings, a 22 µm filter is fitted between the adaptor and the tubing. This is identical to that most electronic pipette aids.

This invention was a response to a need mentioned in white blood cells extraction from whole blood, and has been successfully tested for that purpose.

## Materials
1. PLA Plastics for 3D Printing
2. M5 x 25 mm machine Screws and Nuts x 8
3. 150 * 50 * 2 mm 430 steel plate x 1
4. 50 * 50 * 2 mm 430 steel plate x 1
(note: the design could be modified to accommodate a single 300 * 50 * 2 mm steel plate, and any magnetic plates will do)
5. 20 mm diameter * 4 mm (5 mm hole) Neodymium disc round magnet x 4
6. 0.22 μm / 0.45 μm filter x 1
7. 3 mL syringe with Luer lock x 1
8. ~ 30 - 50 cm plastic tubing x 1
9. Connectors that join the filter and the Luer lock syringe to the plastic tubing
* Female Luer Union x 1
* Straight Male Luer Lock to Hose Barb Adapter x 2
10. Insert rubber that connects the glass Pasteur pipette / serological pipette to the filter and fits on the lift x 1. (Drummond Pipet-Aid Rubber Insert for EZ Grip Nosepiece is the one used here)

For the items #6 - #10, any combinations of products from different bands are acceptable as long as the joins are air-tight.

## Printing and Assembly
<img src="https://github.com/tyhho/aspirator_stand/blob/master/images/AS_PartsAnnotation.png" alt="Aspirator Stand parts annotated" width="300">

* Recommended print setting: 40% infill, Cubic, Brim
* The **Base** and **Body_Part1** are assembled together via 8 screws and nuts. The direction of the nuts should not matter. If the holes for the screws were too tight, it might be necessary to drill them open a little.
* **Body_Part1** and **Body_Part2** must be joined prior to insertion of the magnetic steel into the socket. The 3D printed parts should snap to each other directly, like below:
<img src="https://github.com/tyhho/aspirator_stand/blob/master/images/AS_BackViewBodyPart2.jpg" alt="Aspirator Stand Back View" width="200">

* The design of the **lift** was specifically designed for the rubber insert from a broken pipette aid. Using a different substitute will necessitate a redesign of the **lift**.

## Known issues
1. If a 3D printer with print height > 30 cm is available, **Body_Part1** and **Body_Part2** could be merged as a single print object.
2. The initial workable design shown above considered the issue that the magnetic rail might be too high. This might happen if the liquid layer to pipette is located close to the bottom of the tube. A quick solution would be to remove the **spacing plastic** that stacks underneath the rail. This would shift the operable range of pipetting lower. However, a permanent solution would be to purchase a longer piece of magnetic steel sheets such that the entire range of height is covered. This might necessitate a corresponding adjustment in the 3D prints.

## Acknowledgement
Greg Sutton (iBioE, University of Edinburgh) described the need in repetitive white blood cells extractions from multiple samples.

Rose Rae (iBioE, University of Edinburgh) came up with the idea of salvaging the rubber insert from a broken pipette aid. Credits to her to make this stand feasible in the first place.

Dr. Logan Mackey (School of Chemistry, University of Edinburgh) provided access to a reliable 3D printing as well as materials, and set up print settings to yield the 3D parts shown here.

Dr. Abdelrahman Zaky kindly spared the plastic tubings and connectors for prototyping this aspirator stand.

## Questions/Issues/Suggestions
Please contact me through email since I do not actively or passively monitor my Github. Thank you.
