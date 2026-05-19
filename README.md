# ADPLL
A frequency detector (PFD) is used to compare the arrival times of the reference and divided clock edges. The resulting early/late information is filtered through a DLF at a divided frequency.
The output of the filter is divided into the most significant bits (MSB), which are directly sent to the DCO for coarse tuning and the least significant bits (LSB), which are sent to the sigma delta modulator for fine tuning.
The output of the DCO is used to generate a local clock that goes to all of the digital logic and to generate a clock gating signal that further reduces the clock frequency and is used by DLF and PFD.

The proposed ADPLL is designed in 22-nm and its layout occupies an area of (71×32 μm2).

### ADPLL Topology

![ADPLL](ADPLL_Design.png)


# DCO Array

![DCO Array](DCO_Array.png)


# PFD

![PFD](PFD.png)

# Digital loop Filter

![Loop_Filter](Loop_Filter.png)


# DCO_Control_Unit

![DCO_Control](DCO_Control_Unit.png)

# ADPLL Layout
![PLL](PLL.png)
