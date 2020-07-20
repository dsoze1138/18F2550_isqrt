# PIC18F2550 calculate integer square root
==========================================

This is a MPLABX v5.40 sample project to show a pic-as(v2.20) 
project and debug method.

Step 1: Open the 18F2550_isqrt_v540 project

Step 2: Set at breakpoint in the test.S file at line 330: "call    isqrt"

Step 3: Select menu: Debug->Debug Project

Step 4: Add symbolic names to Variables (or Watch) windows

Step 4a: In the test.S file at line 180 click on symbol: "isqrt_in"

Step 4b: On keboard hold down ctrl+shift and press F9 to add "New Watch", click OK

Step 4c: In the Variables (or Watch) window right click on the "isqrt_in" symbol the select User Defined Size->32-bits

Steps 4d to 4f: Do the same for symbol "isqrt_out"

Step 5: Right click on the "Name Type Address Value" bar in the Variables (or Watch) window then select the Decimal:Decinal formatted value to dsiplay decimal value column.

You are now ready to use the "Step Over (F8)" of the debugger to observe the input and output values as the test loop executes.