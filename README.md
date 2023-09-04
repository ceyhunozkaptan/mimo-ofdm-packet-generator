## MIMO OFDM Packet Generator

This application is developed within the Qt Creator 4 framework to generate customized transmission packets for [MIMO OFDM Joint Radar-Communication (JRC) Transceiver](https://github.com/ceyhunozkaptan/gr-mimo-ofdm-jrc):

+ **Customized Packet Generation:** Generates Data Packet (DATA) and Null Data Packet (NDP) customized for the JRC transceiver.
+ **GnuRadio Flowgraph Integration:** Interfaces with the GnuRadio flowgraphs by sending the packets through a UDP socket. 
+ **Upper Layer Functionality:** Provides a simple framework for implementing essential Application and MAC Layer functionalities for the JRC transceiver: (i) data formatting/encapsulation, (ii) initializing PHY transmissions, and (iii) control of the transmission rate. 
