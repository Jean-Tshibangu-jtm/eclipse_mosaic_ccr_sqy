#  "Striving for Urban Traffic Optimization: Eclipse MOSAIC-Backed Predictive" paper submitted to CiCom 2023
# Abstract
In densely populated urban locales, the burgeoning volume of traffic has
  precipitated congestion, traffic bottlenecks, and heightened apprehensions
  regarding safety. In this context, this paper explores predictive
  simulation-based Internet of Vehicles (IoV) application design using the Eclipse
  MOSAIC co-simulation framework. Our goal is to develop predictive driving
  assistance applications, focusing on improving traffic flow in congested
  commercial areas, as relevant use cases. This work extends prior research
  involving realistic urban traffic design using SUMO, based on field observations
  at a regional shopping center in the Saint-Quentin-en-Yvelines (SQY)
  agglomeration, France.  It introduces a vehicular communication layer, enabling
  prototype Cooperative Awareness Messages (CAM) transmission and reception
  application. Our work is underpinned by data collection, including log files,
  which are instrumental in our initial analysis of network-layer traffic flows.



## Git repository 

SUMO version is **v1_16_0**

**Execution**:
- Download eclipse-mosaic-23.0.zip from: https://eclipse.dev/mosaic/docs/getting_started/
- Extract it into a directory
- Clone the project into the "mosaic/scenarios" directory
- While in the "mosaic" directory, execute the following command: ./mosaic.sh -s eclipse_mosaic_ccr_sqy -v (for Linux) and ./mosaic.bat -s eclipse_mosaic_ccr_sqy -v (for Windows)

**Contacts**:
- Jean Tshibangu Muabila: `jean.tshibangu-muabila_at_estaca.fr`
- Sebti Mouelhi: `sebti.mouelhi_at_estaca.fr`
