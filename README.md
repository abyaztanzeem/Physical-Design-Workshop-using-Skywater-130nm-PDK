# Physical-Design-Workshop-using-Skywater-130nm-PDK

The main purpose of this workshop is to design an On-Chip Clock Multiplier (PLL) and implement the layout using open-source EDA tools such as ngspice and Magic on OSU180nm PDK.

## Section 1 - Introduction and Basics of PLL

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
