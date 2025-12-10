# :nut_and_bolt: SlimeBolt-Tracker

DIY SlimeVR Trackers based on [Smol Slimes](https://docs.slimevr.dev/smol-slimes/index.html). This case design seeks to support DIY stacked slimes with a swappable decorative lid and easy assembly.

<img src=".\images\RENDER_ISO.PNG" height="200"><img src=".\images\RENDER_ISO_NoTop.png" height="200">

<img src=".\images\IRL_ISO.jpg" height="200"><img src=".\images\IRL_ISO_Filled.jpg" height="200"><img src=".\images\IRL_TOP_Parts.jpg" height="200">

I've never been a big fan of snap fits in 3d prints. Maybe its because I take my things apart to often... With this design, you are free to disassemble and peek at your tracker's guts every now and then. You could swap the faceplates with new designs or labels. Whatever your heart desires!

For one tracker, you must print one [Bolt-Base](3d-files\Bolt-Base.step) and one of any lid design: [Blank](3d-files\Bolt-Lid-Blank.step), [Large Logo](3d-files\Bolt-Lid-Large-Logo.step) or, [Small Logo](3d-files\Bolt-Lid-Small-Logo).

<img src=".\images\Slicer-Orientation.png" height="500">

Print with the flat sides of the lid and base on the build plate. Turn on automatic tree supports. This is ensure the recessed sections for the nut and socket head screw print cleanly. These can be easily removed after printing by pressing a hex key through the tops of the holes.

<img src=".\images\Slicer-Multicolor-Lid.png" height="500">

The logo lids are comprised of two components. In your slicer, you may assign materials to these components to make this logo stand out. This works in most slic3r based slicers (Prusa, bambu, orca, etc). You may also remove the logo component and leave the void embossed into the print.

The small logo lid variant has a small space at the bottom for you to emboss text, should you decide to do that!

## :gear: Components

### Trackers

Whatever components you buy, purchase 20% more nRF and IMUs than you plan on using. These components sometimes arrive DOA or broken during the build process. Nothing's worse than getting all your parts only to sit for another 2-3 weeks for Aliexpress to ship more.

| Component | Details | Link |
| --------- | ------- | ---- |
| ProMicro nRF52840 | The main controller | [Aliexpress](https://www.aliexpress.us/item/3256807552571798.html) |
| SlimeVR Compatible IMU | Check the [SlimeVR Docs](https://docs.slimevr.dev/diy/imu-comparison.html#-recommended-imus) for a recommendation list | [ICM45686+QMC6309](https://shop.slimevr.dev/products/slimevr-mumo-breakout-module-v1-icm-45686-qmc6309) |
| 3x4x2 Push Button Switch | Used as a multipurpose interface to reset, calibrate, pair, etc. Make sure you order the proper size! | [Aliexpress](https://www.aliexpress.us/item/3256806817879697.html) or [Amazon](https://www.amazon.com/dp/B07TB62N4T) |
| SPDT 3mm Toggle Switch | Used to disconnect the battery for long term storage. | [Aliexpress](https://www.aliexpress.us/item/3256803752541650.html) or [Amazon](https://www.amazon.com/dp/B09R43HCY3) |
| 601230 3.7v 180mAh LiPo Battery | Provides around 30 hours of runtime. Purchase in a 10 pack if possible | [Aliexpress](https://www.aliexpress.us/item/3256807528195808.html) |
| Kapton/Electrical Tape | A small layer of tape is used under the IMU to prevent shorting between the IMU and ProMicro. 20mm width recommended. |  |
| 26 AWG Wire | Used for wiring battery disconnect and antenna |  |
| 4 x M2x0.4x12 Socket Cap Screw | DIN 912 / ISO 4762 Standard | [McMaster](https://www.mcmaster.com/91292A834/) |
| 4 x M2x0.4 Hex Nut | DIN 934 | [McMaster](https://www.mcmaster.com/90591A265/) |

### Straps

| Component | Details | Link |
| --------- | ------- | ---- |
| 30 mm (1.2 in) Elastic Band | I recommend you get elastic band with rubber webbing behind it. This keeps the tracker secure without tightening it down. | [Amazon](https://www.amazon.com/dp/B092SM7Z2V) |
| 30 mm buckles | You could print these like I do. I use [This Dovetail Latch](https://www.thingiverse.com/thing:6929026) design from [MoDErahN](https://www.thingiverse.com/MoDErahN) on Thingiverse | |
| Needle & Thread / Hot glue | Used to secure one end of the strap. With the dovetail latch I often don't have to secure an end. | |

## :wrench: Assembly Instructions

🚧 Coming soon! 🚧
