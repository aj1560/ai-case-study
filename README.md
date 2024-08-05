# Juniper Mist - An AI driven network solution

## Overview and Origin 
Mist Systems Inc. was founded and incorporated in 2014 by Sujai Hajela (CEO) and Bob Friday (CTO).  Sujai and Bob both came from Cisco and had deep knowledge of network technologies. They thought of using the information available in wireless systems as the inputs to ML models and developing AI driven networks. They raised $108M over 4 years with some of the investors being Lightstream Venture Partners, Dimension Data, Google and Cisco.

Juniper Networks Inc. (AKA Juniper) is one of the leaders in network industry for the last couple of decades. Juniper acquired "Mist Systems Inc." in 2019 for ~400M and integrated the AI platform into the Juniper portfolio of network gear. The competitors for Juniper Mist today are <a href="www.cisco.com">Cisco</a>, <a href="www.arista.com">Arista</a>, <a href="www.nile.com">Nile</a> to name a few, which are still playing catch-up while Juniper Mist is recognized as the leader.

When Mist was founded in 2014, Enterprise networks were facing the challenges of being the roadblocks to business evolution. All the solutions in the market addressed networks in a nearly identical fashion - copious amounts of network hardware, monitor, manage, truck rolls, upgrade, replace, rinse and repeat. All of these actions required manual intervention and as such the lifecycle for networks was 8-10 years at a minimum, making network transformation a dreaded term that involved a significant cost, time and risk to business. If an organization decided to go with transformation they would end up with still the same problems they had in the old network - static and largely dependent on human intervention.

The problem statement/idea for the company was : ***How can we get wireless networks to be automated, self correcting and require least human intervention for the installation and the ongoing operations.*** 

Below are couple of examples that will help illustrate the value of Juniper Mist platform:\
**Example 1:** **Wireless user is not able to connect to the internet**
|  Network Engineer troubleshooting steps without the Juniper Mist platform  |  Elapsed time (mins) | Troubleshooting steps with the Juniper Mist platform                                                                    |  Elapsed time (mins) |
|----------------------------------------------------------------------------|:----------------------------------:|-------------------------------------------------------------------------------------------------------------------------|:----------------------------------:|
| 1. Confirm wireless interface on laptop is ON.                             |                05:00               | 1. Access Juniper's AI engine known as "Marvis Virtual Network Assistant" or more commonly as "Marvin VNA" platform, provide user laptop details and request latest connection history                      | 02:00                              |
| 2. Check wireless SSID is the right one                                    |                06:00               | 2. Marvis responds with data about connectivity failure for the history and points to the likely problem as DHCP server | 02:30                              |
| 3. Check wireless access point reachability to the controller              |                11:00               | 3. DHCP server issue is fixed                                                                                           | 02:00                              |
| 4. Check controller for any issues                                         |                13:00               | 4. User successfully connects to the internet                                                                           | **07:00**                              |
| 5. Packet sniff user wireless access to identify issue                     |                20:00               |                                                                                                                         |                                    |
| 6. DHCP server issue identified                                            |                25:00               |                                                                                                                         |                                    |
| 7. DHCP server fixed                                                       |                30:00               |                                                                                                                         |                                    |
| 8. User successfully connects to the internet                              |                **31:00**               |                                                                                                                        
Note that the resolution time is quardrupled when Juniper Mist is not used.

**Example 2:** **Wireless slowdown for a section of the building**
|  Network Engineer troubleshooting steps  without the Juniper Mist platform                     |  Elapsed time (mins) |                                                          Troubleshooting steps  with the Juniper Mist platform                                                           |  Elapsed time (mins) |
|------------------------------------------------------------------------------------------------|:----------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------:|
| 1. Check Wireless Access Point and Switch                                                      |                05:00               | 1. Marvis VNA platform monitors the Wirless Radio signal congestion in real-time.    It switches channels whenever problem is noticed. No user intervention is required. | 00:00                              |
| 2. Check LAN connectivity to the building                                                      |                06:00               |                                                                                                                                                                          |                                    |
| 3. Check network congestion on the LAN                                                         |                08:00               |                                                                                                                                                                          |                                    |
| 4. Check Wireless Radio Congestion                                                             |                13:00               |                                                                                                                                                                          |                                    |
| 5. Identify alternate wireless radio channel and    switch the Access Point to the new channel |                17:00               |                                                                                                                                                                          |                                    |
| 6. Congestion resolved                                                                         |                18:00               |                                                                                                                                                                          |                                    |
Note that the resolution cycle is eliminated for this problem entirely.

## Under the hood
Mist was the first network product to create self-healing products driven by AI. This was a big leap for the network industry which was just getting used to the idea of software driven networks. The below video provides a brief summary into how the AI Engine was trained. <a href="https://www.youtube.com/watch?v=h-cgOoxvPOI&list=PLGvolzhkU_gRu2Sq3O3yKpo8u0h3-NNe6&index=5">The graphics content of this video has been sourced from the Juniper AI series on youtube</a>

![Mist_video_git](https://github.com/aj1560/ai-case-study/blob/main/Mist_video_git.gif)

## Conclusion
The early adoption of AI in networks was an extremely successful winning strategy for Mist. Mist is the leader in the space and having started with wireless networks as the focus, now other enterprise products such as LAN switches and routers, WAN routers are also part of the Mist platform. The network telemetry data collected through 30+ years of Juniper networks has been effectively used for training the ML model showcasing great results.

## References for additional reading 
<a href="https://www.juniper.net/us/en/research-topics/what-is-ai-native-networking.html">What is AI Native Networking?</a>

<a href="https://m.youtube.com/playlist?list=PLGvolzhkU_gRu2Sq3O3yKpo8u0h3-NNe6">Juniper Mist Whiteboard Technical Series</a>

<a href="https://www.juniper.net/documentation/us/en/software/mist/mist-aiops/mist-aiops.pdf">Juniper Mist AI Native Operations Guide</a>
## Sources
<a href="https://www.crunchbase.com/organization/mist-systems/company_financials">Company Information</a>

<a href="https://icis.corp.delaware.gov/Ecorp/EntitySearch/NameSearch.aspx">Company registration search</a>

<a href="https://newsroom.juniper.net/news/news-details/2019/Juniper-Networks-Announces-Intent-to-Acquire-Mist-Systems-to-Bring-AI-to-IT-Delivering-on-Promise-of-Software-Defined-Enterprise/default.aspx">Mist acquisition news</a>

<a href="https://medium.com/lightspeed-venture-partners/mist-systems-joins-juniper-networks-e13e774d54d5">Article on the acquisition</a>

<a href="https://m.youtube.com/playlist?list=PLGvolzhkU_gRu2Sq3O3yKpo8u0h3-NNe6">Juniper Mist Whiteboard Technical Series</a>


