# dang-sat-recon-mode
As per protocol... we do risk assessment..... oh boy



The purpose of this repo to avoid the loss of data and the damage to the electronic devices in the area of the radio telescope that would occur in case its main beam was pointing towards a radio waves noise emitter, such as an aircraft or a satellite. The first step to achieve this is to collect and access real time data representing the ariplanes around the telescope. After analysing and plotting the data to find useful features, a first version of the controller can be implemented: the controller will switch off the telescope if an airplane passes throug the main beam. The next step consists in implementing a controller using Model Predictive Control that will find the optimal path to be followed by the telescope to avoid airplanes. In the optimization, a cost will be associated to the distance of the aircraft, its signal strenght, the control effort needed to avoid it, and the number of observarions already taken in that area.


