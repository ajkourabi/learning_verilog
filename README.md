# Goal 

My goal was to design a chip from scratch. To achieve that, I had to learn about the process from the start, beginning with learning Verilog. After some sample projects, I designed an **RGB Mixer** in Verilog. Using OpenLane, I turned that into a chip. 

I also completed several other smaller projects to get to creating this larger more involved project. 

## Final Product 

The final product is an **RGB LED Mixer ASIC**. I described the base functionality in Verilog, and using OpenLane's RTL to ASIC workflow, took the design through the chip desing process. The mixer is made of three parts: 

1. PWM Driver, built from scratch 
2. Digital Rotary Encoder, built from scratch 
3. LED-Driver that combines these modules to power 3 LEDs. 

> The flow of taking the Verilog code into a chip is completely outlined and annotated in a Jupyer Notebook I made. You can find it [here](chip design flow.ipynb). chip design flow.ipynb

## Past Projects 








I am learning verilog. My goal is to explore the entire chip desing process from writing the verilog code to doing the layout. I started with writing verilog programs, like an ALU and a Systolic Array. My next goal is to take a program, like an RGB mixer, all the way through the chip design process. 

Here are my projects so far:

# **RGB Mixer**

This was composed of three parts 

1. PWM Driver, built from scratch 
2. Digital Rotary Encoder, built from scratch 
3. LED-Driver that combines these modules to power 3 LEDs. 

My goal is to take this and make it into an ASIC, thus learning about the entire chip design process. 

I already verified it using VHDL test benches, but plan to do a more complete job with something like coco_tb. 

# **Systolic Array for Matrix Multiplication**. 

A systolic array is a form of architecture in which nodes are tightly couples and networked in a way that allows for streamlined parallel computing. It is used in AI Chips like Google's TPU for matrix multiplication. 

Because these cells are tightly coordinated and pipelines flow rhytmically, the array is called systolic (referring to the way the heart beats)

I wanted to better understand parallel architectures, and decided to implement a systolic array -- from scratch, in verilog. It was a robust learning expereince in which I was able to better understand parallel computing. It also enabled me to better understand the details between how TPUs and GPUs are different. 

There is one file, `block.v`, which describes the basic behaviour of a single processing element, and the other code describes putting together the array. 

# Other projetcs

## Traffic State Machine 
Simple program to learn state machines in Verilog! 

## ALU and a Counter 
Other basic projects to understand Verilog and computer architecture better 