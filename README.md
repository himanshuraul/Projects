# Projects
Water tank & transfer pump surveillance

Problem Statement – This project was implemented for multiple commercial and domestic large scale buildings. The objective was to proactively initiate the process of pump or tank inspection and maintenance.
There could be several reasons for not getting the required amount of water in the rooftop tank such as pump operational failure, or piping or valve or water tank leakages etc. 
When the pump did not deliver the required volume of water, it was evident that the pump was consuming more wattage of electrical power but doing lesser work and also it was an inconvenience for the building occupants as the water got over faster. In case of some leakage problem in pipes, valves and tank, electricity and water both of the essential resources were wasted which cost a great monetary sum in long run. 

We created independent columns as following:
1.	Mismatch in water volume per day (The difference between required water volume and actual water delivered to the rooftop tank. This data can be obtained from the level sensors installed inside the tanks.)
2.	Days after last maintenance of pump (No. of days it is been after the last maintenance)
3.	Days after last maintenance of piping
4.	Days after last maintenance of tank

The target or dependent column was “Maintenance required” with values classified in binary format with the help of Logistic regression (0 indicates it did not require maintenance in the past and 1 indicates it required maintenance).
By virtue of this algorithm, if the system raises a warning for maintenance requirement then the operator would notify the maintenance department on an urgent basis to initiate the inspection process.  
Adapting this proactive maintenance process not only saved our client from unnecessary expenditure but it also helped in the extension of equipment life. 
