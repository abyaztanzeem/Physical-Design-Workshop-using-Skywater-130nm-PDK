# Physical-Design-Workshop-using-Skywater-130nm-PDK


## Day 1 - SK3, L5 (Flop Ratio)

<p align="center">
  <img width="400" height="500" src="https://i.imgur.com/HdOrvc0.jpg"
</p>
  <p align="center">
    Figure: Flop Ratio
</p>



Flop Ratio = Number of FF's in the design/ Total Number of Cells
Flop Ratio = 1613/14876 = 0.1084


## Day 2 - SK1, L7 (Die Area)

<p align="center">
  <img width="500" height="300" src="https://i.imgur.com/YzGBf5Q.jpg"
</p>
  <p align="center">
    Figure: Die Area
</p>



Die Area = ( Height * Width ) / 1000^2
Flop Ratio = (660685 * 671405) / 1000^2 = 443,590 um^2

## Day 2 - SK1, L8 (Floorplan)

run_floorplan \
magic -T ~/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.floorplan.def
\
<p align="center">
  <img width="500" height="300" src="https://i.imgur.com/CJlsobJ.jpg"
</p>
  <p align="center">
    Figure: Floorplan
</p>


## Day 2 - SK2, L5 (Congestion Aware Placement)

run_placement \
magic -T ~/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.placement.def
\
<p align="center">
  <img width="500" height="300" src="https://i.imgur.com/FQ2X0NH.jpg"
</p>
  <p align="center">
    Figure: Placement
</p>



## Day 3 - SK1, L5 (vsdstdcelldesign inverter layout)

magic -T sky130A.tech sky130_inv.mag
\
<p align="center">
  <img width="300" height="500" src="https://i.imgur.com/6kqgr9Z.png"
</p>
  <p align="center">
    Figure: Inverter Layout
</p>






















librecores.org
opencores.org
github.com
github.com/google/skywater-pdk
