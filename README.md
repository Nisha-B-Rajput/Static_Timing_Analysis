# Static_Timing_Analysis

### VALID TIMING PATHS

<img width="599" alt="image" src="https://user-images.githubusercontent.com/110079800/195977761-f429bc8b-ba54-4cd2-ba55-eacc16bf8263.png">

#### ARRIVAL TIME: Time required for a signal to begin at the start point and reach at the end point is known as arrival time

<img width="583" alt="image" src="https://user-images.githubusercontent.com/110079800/195977860-8d5f958c-847c-4d0e-8535-6cf25b4803d9.png">

### REQUIRED TIME: Time taken for the signal to reach the endpoint is known as requiredd time.

<img width="584" alt="image" src="https://user-images.githubusercontent.com/110079800/195978299-eee49b46-61b5-4479-b61f-e2bcf0b92f8f.png">

### SLACK

<img width="578" alt="image" src="https://user-images.githubusercontent.com/110079800/195978333-dd8d4741-89d4-4868-bad3-7838560a3f12.png">

<img width="610" alt="image" src="https://user-images.githubusercontent.com/110079800/195978434-a8e022a7-0cb9-4dd6-b1cc-218fdfd5bac9.png">

## TYPES OF SETUP AND HOLD ANALYSIS
(1) REG TO REG

<img width="580" alt="image" src="https://user-images.githubusercontent.com/110079800/195979574-ed81b1bb-8a50-457a-8071-d0f177991075.png">

(2) IN TO REG

<img width="514" alt="image" src="https://user-images.githubusercontent.com/110079800/195979660-403bee68-788e-4213-b3ab-4d9bae2b3666.png">

(3) REG TO OUT

<img width="496" alt="image" src="https://user-images.githubusercontent.com/110079800/195979698-45829d5a-9476-48cf-94a3-a4e3eb4ffaa3.png">

(4) IN TO OUT

<img width="497" alt="image" src="https://user-images.githubusercontent.com/110079800/195979757-45bb210e-a7b8-40c3-a6e8-afe91dd9e22d.png">

(5) CLOCK GATING: A path exists from the clock to the agte output

<img width="496" alt="image" src="https://user-images.githubusercontent.com/110079800/195979896-4c200ab6-95fb-481f-9027-ab2ca350ec61.png">

(6) RECOVERY/REMOVAL: The reset signal should come after certain edge of the clock.

<img width="478" alt="image" src="https://user-images.githubusercontent.com/110079800/195979994-4e915925-0da7-4a3b-adb2-5578fb9dca82.png">

(7) DATA TO DATA: A check between two data signals is known as data to data check

<img width="469" alt="image" src="https://user-images.githubusercontent.com/110079800/195980402-71b5067e-a327-4cc8-87e5-228cd23df015.png">

(8) LATCH (TIME BORROW/TIME GIVEN)

<img width="501" alt="image" src="https://user-images.githubusercontent.com/110079800/195980549-f7e5d8dc-3ce9-46dc-8dc0-090e58636c3a.png">

## INTRODUCTION TO SLEW/LOAD AND CLOCK CHECKS

CLOCK ANALYSIS
(1) SKEW

<img width="473" alt="image" src="https://user-images.githubusercontent.com/110079800/195981521-d000077b-deee-4ae0-8f19-cb2b570cd97a.png">

(2) PULSE WIDTH

<img width="509" alt="image" src="https://user-images.githubusercontent.com/110079800/195981722-5a40aa67-8d68-4bba-9eac-776badcdcd96.png">

<img width="218" alt="image" src="https://user-images.githubusercontent.com/110079800/195981796-6c38cf22-8923-4d2d-9abc-2b4aa40d50fe.png">

### INTRODUCTION TO SLACK AND GBA PBA ANALYSIS

<img width="524" alt="image" src="https://user-images.githubusercontent.com/110079800/195986498-5f3c4530-529a-4477-8414-92dae4d386ac.png">

<img width="523" alt="image" src="https://user-images.githubusercontent.com/110079800/195986520-9ba8d6b8-2ab2-4d1b-9b11-d736f896be67.png">

### CONVERT PINS TO  NODES AND COMPUTE RAT,AAT AND SLACK

<img width="578" alt="image" src="https://user-images.githubusercontent.com/110079800/195987519-c6be5bd8-e06e-4df2-a7f8-4232df05f002.png">

<img width="607" alt="image" src="https://user-images.githubusercontent.com/110079800/195987879-35952d66-6726-4836-a74e-17c9aee795e4.png">

<img width="602" alt="image" src="https://user-images.githubusercontent.com/110079800/195987985-1c16924d-ab49-49d3-b61f-409ff4420d23.png">

<img width="623" alt="image" src="https://user-images.githubusercontent.com/110079800/195988153-2da677a1-2b94-41c3-823f-4feb5bb765ea.png">

<img width="646" alt="image" src="https://user-images.githubusercontent.com/110079800/195988185-a86ba19c-b1e8-4fb5-b92e-485418e4d325.png">

<img width="623" alt="image" src="https://user-images.githubusercontent.com/110079800/195988205-a82dd85c-38f6-44de-902d-1cef7cfa5f80.png">

<img width="539" alt="image" src="https://user-images.githubusercontent.com/110079800/195988309-be4d7267-e6ee-4021-99e1-9f9ad777d16f.png">

<img width="632" alt="image" src="https://user-images.githubusercontent.com/110079800/195988367-9abe252b-2b2c-436f-91f6-b92dc37fc262.png">

<img width="635" alt="image" src="https://user-images.githubusercontent.com/110079800/195989187-e06726f0-28ea-4328-a610-2550bc21859b.png">

<img width="643" alt="image" src="https://user-images.githubusercontent.com/110079800/195989209-479c043a-f85d-4a3c-b88f-2fa5fb3708da.png">

<img width="636" alt="image" src="https://user-images.githubusercontent.com/110079800/195989250-f5eafcfc-fcbb-4c25-9614-5c70e24385bd.png">

<img width="639" alt="image" src="https://user-images.githubusercontent.com/110079800/195989281-bdf64d5f-b934-4a44-b0f7-2af34e6241ae.png">

<img width="635" alt="image" src="https://user-images.githubusercontent.com/110079800/195989302-4250b4fe-bb1c-43d4-8ab5-4c28ef932b97.png">

<img width="641" alt="image" src="https://user-images.githubusercontent.com/110079800/195989325-ce821830-2f79-44e8-a88e-876f55ff54d6.png">

### LIBRARY SETUP TIME CALCULATON

#### POSITIVE EDGE TRIGGERED FLIP FLOP USING MASTER-SLAVE CONFIGURATION

<img width="643" alt="image" src="https://user-images.githubusercontent.com/110079800/195989758-8c42364c-29f5-4d01-9b7a-f73013cc900d.png">

<img width="644" alt="image" src="https://user-images.githubusercontent.com/110079800/195989800-a3c5baa4-0275-4fc5-9478-08441bf2d0e8.png">

<img width="632" alt="image" src="https://user-images.githubusercontent.com/110079800/195989855-6da6d80b-6fd5-46e5-ba15-397517870507.png">

<img width="635" alt="image" src="https://user-images.githubusercontent.com/110079800/195989882-ed661c9d-814b-49fe-b8ba-41a46dc470fe.png">

<img width="320" alt="image" src="https://user-images.githubusercontent.com/110079800/195989975-777f3982-e706-477e-9e7a-d7e5c685f702.png">




