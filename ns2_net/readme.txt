Implementation of a small network in ns2

Description/Comments:
--------------------
1. Created six nodes n0 and n1 correspond to src1 and src2; n2 and n3 correspond to R1 and R2; n4 and n5 correspond to rcv1 and rcv2.
2. Established appropriate links(duplex) wih DropTail queue mechanism.
3. Created TCP agents and attached it to n0 and n1
4. Added FTP traffic source over these TCP agents
5. Created two TCP sinks and attached them to n4 and n5
6. Recorded bandwidth data using set bw0 and set bw1 at the two sinks.
7. Used three global variables sum_1, sum_2 and count to calculate the average throughput of src1 and src2.
4. Printed these results using puts. 

