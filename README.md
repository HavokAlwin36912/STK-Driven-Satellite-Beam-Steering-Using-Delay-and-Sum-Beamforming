# STK-Driven-Satellite-Beam-Steering-Using-Delay-and-Sum-Beamforming
This project demonstrates satellite beam steering using STK-driven orbital geometry and Delay-and-Sum beamforming in MATLAB. Azimuth and elevation data from STK are used to compute URA steering vectors and DAS weights. The beamformer output Y = WᴴX and radiation pattern are evaluated to visualize real-time satellite tracking.

Master File :

This file calls STK application (ver 11) from MATLAB then creates Satellite and Ground Station using .NewChildren function, 
then gets the azimuth and elevation angle using the function aer() ( which is a inbuilt function of Ansys STK )
then it computes the steering vector -> weight -> DAS Beamformer 
then plots the graph for one particular angular position of the sateillite from that bunch ( azimuth(i) , elevation(i) ).
