# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![WhatsApp Image 2025-10-10 at 13 31 53_382130fd](https://github.com/user-attachments/assets/c44b9fa6-43a4-433e-94d2-749a74343ea0)


Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

/* write all the steps invloved */

**PROGRAM**
![WhatsApp Image 2025-10-16 at 17 27 07_e6ae6ea1](https://github.com/user-attachments/assets/8ef0474c-3d12-4f40-b7c1-034d1fffba2b)

/* Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by:A.SAMYUKTH RegisterNumber:25018852

*/

**RTL LOGIC FOR SISO Shift Register**
![WhatsApp Image 2025-10-10 at 13 31 55_24f2abc3](https://github.com/user-attachments/assets/a84f7b86-7c53-46ff-a684-601fb05beb4e)

**TIMING DIGRAMS FOR SISO Shift Register**

**RESULTS**
THUS THE GIVEN LOGIC IS STUDIED AND VERIFIED SUCCESSFULLY
