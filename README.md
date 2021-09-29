# VSD-AdvancePhysicalDesign usingOpenLane/sky130

![Advanced-Physical-Design-using-OpenLANE_Sky130_1](https://user-images.githubusercontent.com/69396127/134968815-f1295221-93d3-402c-a573-fecc71c85342.png)

# * Table of contents*
* Overview of Physical Design FLow
     - Challenges and Surprises 
---
>Day 1- Theotrical concept -->Inception of open-source EDA, OPENLANE and Sky130 PDK        
* 1.)[How to talk to computers](https://github.com/Gourav0486/VSD-AdvancePDdesign-sky130/edit/main/README.md)
    * Basic Terminologies in Chip design Flow
    * Introduction to QNF-48 package ,chip pads
    * What is IPs and why they are so important?       
        
* 2.)SoC design and OpenLANE
    * Intro to RISC-V ISA 
    * SOC Design and OpenLANE
    * From Software application to hardware
              
* 3.)Get familiar to open-source EDA tool
    * OPENLANE ASIC FLOW in Details
    * External Link for further Description
      
> Day 1 - LAB : 
* Setting up _OpenLane_
* Design Preperation Step
* Run Synthesis and Review the synthesis results

---
> Day 2 : Theotrical Concept -->  Good vs bad Floorplan and Introduction to Library cells
* 1.) Chip Floor planning considerations
    * Utilization factor 
    * Aspect ratio
    * Floor planning 
    * Pre-Placed cells and decoupling capacitors
    * Power planning 
* 2.) Library Binding and Placement
    * Netlist binding and initial place design
    * Placement
    * Need for Libraries and charaterization 

* 3.) Cell Design and Characterization Flow
    * Cell Design Flow
    * Circuit Design Flow
    * Layout Design Step
    * Characterization Flow

* 4.) General timing characterization parameters
    * Threshold Voltage
    * Propogation delay
    * Transition time
    * Output current waveform
    
> Day 2: Lab 
* Review Floorplan files 
* Layout for floorplan in Magic tool
* Congestion Aware Placement with RePlAce
---
> Day 3: Theortical Concept --> Design and characterize one library cell using Magic Layout tool and Ngspice

* 1.) CMOS Inverter simulation using Ngspice 
    * SPICE deck creation for CMOS inverter
    * SPICE simulation lab for CMOS inverter
    * Switiching Threshold Vm
    * CMOS Inverter : Static behaviour evalution
* 2.) Inception of Layout – CMOS fabrication process
    * In-Depth about 16-mask CMOS process 

> Day 3: Lab 
* SKY130 Tech File Labs
    *  Review of Sky130_inv.spice
    *  Review of CMOS inverter layout in Magic
    * In-depth overview of Magic's DRC engine
    * Introduction to Google/Skywater DRC rules
    * Warm-up exercise :Fix  a simple rule error
    * Main exercise  : Fix or create a complex error
---
> Day 4: Theotrical Conept--> Pre-layout timing analysis and importance of good clock tree   
* 1.) Timing modelling using delay tables
    *  Power Aware CTS
* 2.) Clock Tree synthesis
    * H-Tree
    * Buffers

> Day 4: Lab
* Rules for Layout of Standard Cell
* Convert Magic layout to std cell LEF
* Inside LEF file
* Integrate Custom cell into design
* Configure synthesis to Fix slack
* Post -synth Timing analysis-OpenSTA
* Optimize Synthesis 
* Synthesis Clock distribution network - TritonCTS
---
>Day 5: Theotrical Concept--> Final steps for RTL2GDS
* Routing and design rule check (DRC) 
    * Overview of TritonROute 
    * DRC check Rules

>Day 5 : Lab
* Power Distribution Network generation
* Routing in OpenLane

---
WRAP Up the Course

---
# REFRENCES



