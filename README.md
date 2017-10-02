# TTK8: IPv6/Cloud connected multi-humidity sensor
## Description
Make a capacitive humidity sensor from scratch or convert a capcative touch sensor to become a humidity sensor if possible. Using the nRF52480 chip or development kit to connect it to the cloud/IPv6. Then also attach industrial/hobby humidity sensors to the kit and compare it to the capacitive humidity sensor which I made.
## Work break down structure
1. Humidity sensor
    1. Layout design
    2. Manifacture PCB
    3. Test capacitive sensitivity
    4. Add other sensors
    5. Driver code
    6. Network code
    7. Cloud code
    8. UI code

## Progress/work plan
1. 1. sep - 15. Oct: Learn layout design and source components
    * If all fails switch to using breadboards and make capcacitive sensor from PCB
2. 16. Oct - 18. Oct: Send design to manifacturer(Est. 2-3 Week ship+production time), Document PCB creation
3. 18. Oct - 26. Oct: Wire up other sensors to DK board and write driver code, write about experience and document layout
4. 31. Oct - 05. Nov: Write network code for connecting to IPv6 over BLELoWPAN, document code and step by step guide for IPv6 over LoWPAN
5. 05. Nov - 11. Nov: Write reception code for cloud service provider, document code cloud and service provider creationg and API
6. 11. Nov - 16. Nov: Write UI code for a neat user interface for the device, document UI code and creation of UI interface
7. 11. Nov - 23. Nov: Polish/refactor code + Make presentation
    
