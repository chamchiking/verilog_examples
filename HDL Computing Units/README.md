# HDL Computing Units

---

## Lab1

### creating a DSP using Xilinx IP generator

- click "IP Catalog" on vivado
- search "DSP"
- choose "DSP48 Marco" and double click on it

#### ports of the DSP

- Input
  - CLK
  - A[17:0], B[17:0]
  - C[47:0]
- Output
  - P[47:0]

#### DSP formula

P = A*B + C

---

## Lab2

- Build a MAC
  - Use multiple multipliers
  - Adder tree
- Make a testbench
  - Test the MAC

### DNN accelerator

#### Processing element (PE) Array

- An array of multiplication and accumulation (MAC).
- Perform convolution operations.
- Computing unit pr "ALU" of a DNN accelerator

#### MAC

- MAC is a module that performs many mltiplications and accumulations in parallel

---

## Lab3

