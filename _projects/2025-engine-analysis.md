---
layout: project
title: P&W FW-100-PW229 Engine Analysis
description: Thermodynamic Analysis
technologies: 
image: /assets/images/pw-eng-view.png

---

For a class, we were asked to perform a thermodynamic analysis on a real-world device. I chose the Pratt & Whitney FW-100-EQ medium bypass turbofan, a jet engine used in several aircaft including variants of the F-15 and F-16

The FW-100 is a medium-bypass turbofan engine. The operating principle of the FW-100 is as follows:

![Simplified render of turbofan]({{ "assets/images/diagram-turbofan.jpg" | relative_url }}){: .inline-image-r style="width: 400px"}

A fan at the engine's intake draws in air at the ambient pressure, with most of the air being drawn into a compressor, while some of it is drawn into bypass ducts. The compressor compresses the incoming air before feeding it into the combustion chamber, where it is mixed with jet fuel. The resulting mixture is ignited, and the expanding gas drives a turbine, which provides some power back into the fan and compressor. The outflow mixture is then sent out of a nozzle, producing thrust.

Each of the five segments (fan, compressor, burner, turbine, and nozzle) can be modeled as a control volume (CV) system, with the CV being the inside of the engine duct.

For all of the five segments below, let us assume that the aircraft is parked at sea level and NTP (v<sub>inlet</sub>=0; P<sub>inlet</sub>=P<sub>atm</sub>=101.3kPa; T<sub>inlet</sub>=293°K). Also assume air is an ideal gas.


The fan is a CV system that draws in air from the inlet, takes work from the engine's main shaft, and outputs air out to the bypass and core ducts. We will assume that the fan is isentropic and adiabatic. From the specs of the FW-100, the Fan Pressure Ratio(FPR) is 3.04, the inlet mass flow rate is 112.7kg/s. and the engine's bypass ratio BPR is 0.36. The inlet has a diameter of 0.88m, or a cross-section of 0.6082m^2.

The compressor is a CV system that takes the airflow from the core duct, takes work from the engine's main shaft, and outputs air out to the burner. We will assume that the compressor is isentropic and adiabatic. From the specs of the FW-100, the operating pressure ratio(OPR), or the ratio between inlet and compressor pressure, is 32.4.



Nulla et magna urna. Morbi a ipsum sollicitudin, rhoncus risus volutpat, ultricies nunc. Quisque mollis finibus ante id imperdiet. Quisque vehicula elit sit amet felis facilisis fermentum.

Aenean tincidunt aliquam arcu, in euismod dui dapibus eu. In placerat, mi et ultrices consequat, quam ligula cursus mauris, in semper neque nibh at est. Maecenas hendrerit dignissim porta. Phasellus nec fringilla dolor. Etiam efficitur nisi sit amet velit pharetra feugiat. Etiam ultrices turpis at leo semper, eleifend scelerisque neque malesuada. Aliquam molestie congue rhoncus. Donec blandit neque dolor, nec tristique mi pretium ac. Mauris tincidunt ullamcorper magna, nec pellentesque mi sagittis quis.

I was inspired by this old radio when I made this rendering:

![Photo of old radio]({{ "/assets/images/old-radio.jpg" | relative_url }}){: .inline-image-l}

Aenean tincidunt aliquam arcu, in euismod dui dapibus eu. In placerat, mi et ultrices consequat, quam ligula cursus mauris, in semper neque nibh at est. Maecenas hendrerit dignissim porta. Phasellus nec fringilla dolor. Etiam efficitur nisi sit amet velit pharetra feugiat. Etiam ultrices turpis at leo semper, eleifend scelerisque neque malesuada. Aliquam molestie congue rhoncus. Donec blandit neque dolor, nec tristique mi pretium ac. Mauris tincidunt ullamcorper magna, nec pellentesque mi sagittis quis.

Aenean tincidunt aliquam arcu, in euismod dui dapibus eu. In placerat, mi et ultrices consequat, quam ligula cursus mauris, in semper neque nibh at est. Maecenas hendrerit dignissim porta. Phasellus nec fringilla dolor. Etiam efficitur nisi sit amet velit pharetra feugiat. Etiam ultrices turpis at leo semper, eleifend scelerisque neque malesuada. Aliquam molestie congue rhoncus. Donec blandit neque dolor, nec tristique mi pretium ac. Mauris tincidunt ullamcorper magna, nec pellentesque mi sagittis quis.
