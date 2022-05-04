# Validation-for-Packet-Operations-in-NEST
# Course-Code :CS751
# Assignment : #10
# Aim: Adding test cases to validate various packet operations in NeST.

# Overview:
NeST is a python3 package that handles testbed setup, testbed configuration, collecting and visualizing data by providing a user friendly API,       addressing common issues involved in conducting networking experiments [1].

NeST supports various packet operations like packet dupication, packet loss, reordering of packets , packet corruption. NeST currently has APIs supporing all these operations. These APIs are useful for verifying all packet operations.

For example, if some packets are duplicated within the network then we can know the number of duplicate packets in the output we get using ping command.
Hence, it verifies that duplicate packets are present [2].

To make sure these operations are happening as expected, there is no current mechanism in NeST to validate these operations.
So, this project aims to write validation test cases for packet operations in NeST.

# References:
[1] https://dl.acm.org/doi/abs/10.1145/3404868.3406670

[2] https://gitlab.com/nitk-nest/nest/-/issues/215

[3] https://nest.nitk.ac.in/

