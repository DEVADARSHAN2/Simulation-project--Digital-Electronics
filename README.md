# To Design and simulate the logic diagram using Verilog
# AIM
To Design and simulate the logic diagram using Verilog.
# HARDWARE REQUIRED:
– PC, Cyclone II , USB flasher
# SOFTWARE REQUIRED:
Quartus prime
# LOGIC DIAGRAM:
![WhatsApp Image 2023-11-17 at 14 32 30_3525d839](https://github.com/AJAYASWIN-M/Simulation-project--Digital-Electronics/assets/118679692/6f4d4104-a6b8-430b-b029-d003905d7a43)

# Procedure:

Step1:

create module encoder and decoder.

Step-2:

Get inputs and outputs for encoders and decoders.

Step-3:

perform or operation for encoder and and logic for decoders.

Step-4:

perform RTL LOGIC and get waveform.

Step-5:

End the module.

# PROGRAM
```
Program to To Design and simulate the logic diagram using Verilog.
Developed by: DEVADARSHAN A S
RegisterNumber: 212222110007

module e13 (x, y1, y2, z1, z2);
input x,y1, y2;
output z1, z2;
assign z1=(x&y1) | ((~x) &y2);
assign z2-((~x) &y2) | (x& (~y1));
endmodule
```
# RTL LOGIC:
![WhatsApp Image 2023-11-17 at 14 30 47_fa65cc5a](https://github.com/AJAYASWIN-M/Simulation-project--Digital-Electronics/assets/118679692/32447461-5985-4b4a-bf17-3f6fd05022fb)

# TIMING DIAGRAM

![283723412-4634b2d0-de6b-4b06-8512-4376da55f016](https://github.com/AJAYASWIN-M/Simulation-project--Digital-Electronics/assets/118679692/5df064ef-dc07-42dd-af0d-e0f618a8e896)

# Truth Table:
![283723487-4912e55a-5d72-4f62-a13e-983aa39ac570](https://github.com/AJAYASWIN-M/Simulation-project--Digital-Electronics/assets/118679692/6976e155-4456-4875-8702-205346a78f48)
# RESULT:

Thus the program to design and simulate the logic diagram using Verilog.

