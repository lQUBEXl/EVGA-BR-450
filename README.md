# EVGA-BR-450

## Interior 
Now the fun begins...We open the unit up to find it is Double Switch Forward topology with  DC-DC converters (regulation) apart from their daughter boards compared to more commonly and higher priced units. 
![](https://i.imgur.com/a7HN1UV.png)
* Here is the main layout of the unit. From the top right, we can see the soldered onto a PCB part of the AC repactacle and beginnings of an EMI filter. Moving downward off the side of the chassis, we find a fuze, CM choke, and X + Y capacitor (very basic).

* Moving along towards the bottom right, we find the bridge rectifier (no heatsink -- increased temperatures) and the APFC stage. |

![](https://i.imgur.com/mPlbEt0.png)
* The bulk capacitor is a 85C degree rated one from Elite rated for 400V threshold. We can also see the two switching MOSFETs that make up the actual switch-mode of the unit taking the voltage down from a boosted one from the APFC. 

![](https://i.imgur.com/TCPf8UR.png)
* Top right near the entry plug

![](https://i.imgur.com/WS4hxhe.png)
* The supervisor IC is a Sitronix ST9S429-PG14 that boasts OCP, OVP, and UVP on every rail (nice to see!). It's not typical for supervisor ICs (especially cheaper ones in cheaper units) to include OTP as it could be implemented elsewhere perhaps on an op-amp connected to a lock-out pin or on the fan controller itself. Testing will need to be included if any of these protections are set or used.

![](https://i.imgur.com/buSF1V4.png)
* The unit hosts lower quality series from Teapo's lineup (but still are 105C degree rated).

![](https://i.imgur.com/a3AuFcV.png)
* The fan used is a Yate Loon (D12SH-12) with a sleeve bearing fan (generic).

## Notes

This is not an unique platform. If take a look, it is similar to the BeQuiet L8 lineup with a few modifications like changing out the secondary side group coils for two DC-DC modules, updated transformer, among taking out the 5V recitification circuit.
