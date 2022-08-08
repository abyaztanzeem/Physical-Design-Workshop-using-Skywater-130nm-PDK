# Physical-Design-Workshop-using-Skywater-130nm-PDK


## Day 1 - SK3, L5 (Flop Ratio)

<p align="center">
  <img width="600" height="250" src="https://i.imgur.com/HdOrvc0.jpg"
</p>
  <p align="center">
    Figure: Flop Ratio
</p>
\


Flop Ratio = Number of FF's in the design/ Total Number of Cells
Flop Ratio = 1613/14876 = 0.1084

### - Intellectual Property

IP's, also known as Macros, are pre-made logic units that can be used repeatedly and are supplied by different vendors. The IP's are manufactured in such a way that they have the most optimum and highest specifications that meet the market requirements. Hence, IP's can help reduce the time to market for chip manufacturers like Samsung or Intel.

### - On-Chip Clock Multiplier (PLL)

#### What is it?

An on-chip Clock Multiplier is an IP, that is used to increase (multiply) the frequency of a clock signal coming from a low frequency source (quartz crystal oscillator). 

<p align="center">
  <img width="600" height="250" src="https://i.imgur.com/j4kFVrW.jpg"
</p>
  <p align="center">
    Figure: Clock Multiplier Circuit Diagram
</p>
\


librecores.org
opencores.org
github.com
github.com/google/skywater-pdk
