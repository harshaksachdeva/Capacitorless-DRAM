layout: post
title: "Capacitorless DRAM"
date: 2023-05-14
description: 'An introduction to capacitorless DRAM'

tags:
-IEEE NITK
- Capacitorless DRAM

categories:
-Diode

github_username_1: "harshaksachdeva"
_ _ _

# Introduction to Capacitorless DRAM
##Introduction
Capacitorless DRAM (Dynamic Random Access Memory) is a type of memory technology that does not rely on the use of capacitors to store data. Instead, it uses a different approach that allows for higher density and lower power consumption. In traditional DRAM, each memory cell contains a capacitor and a transistor. The capacitor stores the charge that represents the memory state, while the transistor is used to access and manipulate the stored data.

##Drawabacks:
As the size of capacitors has decreased with advances in technology, they have become more susceptible to leakage and other reliability issues. Moreover, as the channel length of the transistor is reduced, its electrical performance is degraded by the short-channel effect.
 Due to these reasons, it suffers from several disadvantages such as a small sensing margin and short retention time because the neutral region for charge storage is insufficient as the transistor is scaling down, the stored holes could recombine with electrons. These disadvantages lead to the degeneration in the memory characteristic of the DRAM.
 
Thus, to overcome these effects, the DRAM is designed based on  a polycrystalline silicon nanotube structure with a grain boundary thus improving electrical performances because the outer gate (OG) and the inner gate (IG) effectively control the charges in the channel and body regions.

# Device structure
<!-- Adding images : -->
![Capacitorless DRAM](/blog/assets/img/Images/cross-sectional-view.jpg)
Figure shows the cross section of the proposed DRAM based on a single poly-Si NT with a body thickness of 10 nm. The proposed nanotube-based structure offers superior channel controllability because the outer-gate (OG) and the inner-gate (IG) electrodes surround the entire channel region. In addition, different voltages can be applied to the OG and the IG compared to conventional nanowire device, resulting in advantage to use as a memory device. The OG is used for the conventional MOSFET operation and the IG performs a hold operation to store the excess holes.
The high work function 5.2 eV of the IG increases the energy band close to the OG and creates a potential well for the hole storage region. The OG length is designed a long channel of 50 nm. A long channel length is related to the storage ability of 1T-DRAM. 

As longer the gate length, the energy band of the body region is wide and more holes could be stored. Furthermore, the proposed 1T-DRAM cell contains underlap of 10 nm. The underlap structure used in the IG is designed to improve the memory characteristics of the proposed 1T-DRAM. By using the underlap, the effect of the gate electric field could be reduced.
The body thickness of the proposed device was varied to optimize the sensing margin and retention time.
# Transfer characteristics:
<!-- Adding images : -->
![Capacitorless DRAM](/blog/assets/img/Images/transfer-characteristics.jpg)

Figure shows the drain current (IDS) versus the gate voltage (VGS) transfer characteristics of the proposed poly-Si NT 1T-DRAM cell with a poly-Si thickness (Tbody) of 10 nm. The threshold voltage (Vth) of the proposed device is 0.52 V and 0.73 V at temperature of 358 K and 300 K. 

The 1T-DRAM realizes higher on-current (Ion) because it is controlled by the two gates in the channel region. An inversion layer is formed at the OG side. And the IG side induces charge accumulation and increases the mobile carrier concentration, enhancing the floating body effect. Therefore, the inner gate exhibits role of a dual gate resulting in increased on current compared
with the conventional gate-all-around transistor with the same Tbody.

<!-- Adding images : -->
![Capacitorless DRAM](/blog/assets/img/Images/transient-characteristics.jpg)

This figure shows the transient characteristic of the proposed 1T-DRAM. As shown in the figure, the proposed 1T-DRAM achieves a high sensing margin of 422 µA/µm. 

<!-- Adding images : -->
![Capacitorless DRAM](/blog/assets/img/Images/energy-band-diagram.jpg)

This figure shows that applying a positive voltage of 2.0 V to OG and a negative voltage of −2.0 V to IG causes reduction in the potential barrier of the electron tunnels across the conduction band. Thus, a tunneling path is created by the electric fields in the same direction, and the excess holes generated by the BTBT(Band to Band tunneling) accumulate below the valence band
at the IG side. Furthermore, the storage holes are retained by the high work function and negative hold voltage of IG.

# Advantages of Capacitorless DRAM: 
The advantage of capacitorless DRAM is that it allows for higher density memory without sacrificing performance or reliability. Because there is no capacitor, the memory cells can be packed more closely together, resulting in higher memory density. Additionally, since there is no capacitor to charge and discharge, the power consumption of capacitorless DRAM is significantly lower than that of traditional DRAM. Overall, capacitorless DRAM is an exciting development in memory technology that has the potential to significantly improve memory density and power consumption.

# Resources:
-https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8789468
-S. Okhonin, M. Nagoga, J. M. Sallese, and P. Fazan, ‘‘A capacitor-less
1T-DRAM cell,’’ IEEE Electron Device Lett., vol. 23, no. 2, pp. 85–87,
Feb. 2002, doi: 10.1109/55.981314.
- https://www.mdpi.com/2079-9292/11/20/3365
- https://www.ijsr.net/archive/v9i6/SR20529100732.pdf


