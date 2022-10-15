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

### CLOCK TO Q DELAY

<img width="637" alt="image" src="https://user-images.githubusercontent.com/110079800/195994484-2b2b0081-c966-44bf-8b56-97075c296ced.png">

<img width="304" alt="image" src="https://user-images.githubusercontent.com/110079800/195994611-6edd7c20-1e16-4833-94f4-9944cbde8e6b.png">

<img width="287" alt="image" src="https://user-images.githubusercontent.com/110079800/195994641-b66d9035-683e-4d31-93d3-cd171c00e286.png">

<img width="307" alt="image" src="https://user-images.githubusercontent.com/110079800/195994869-1a6a8ef9-e680-4866-956e-b3a9629556d1.png">

<img width="589" alt="image" src="https://user-images.githubusercontent.com/110079800/195995471-1a3b2f53-8f39-4d1a-80a0-0cc3fde63089.png">

### STEPS TO CREATE EYE DIAGRAM FOR JITTER ANALYSIS

<img width="562" alt="image" src="https://user-images.githubusercontent.com/110079800/195995659-26254ac6-f573-429a-8252-fffd739033d5.png">

<img width="566" alt="image" src="https://user-images.githubusercontent.com/110079800/195995752-58d83e5a-50fe-4070-834b-c082780c56e8.png">

<img width="524" alt="image" src="https://user-images.githubusercontent.com/110079800/195996173-6fd8d10e-c4e3-4dc6-bcf5-536a34ccd102.png">

<img width="454" alt="image" src="https://user-images.githubusercontent.com/110079800/195996288-580d4541-06ef-4cbd-aec5-e8b641155a3c.png">

<img width="458" alt="image" src="https://user-images.githubusercontent.com/110079800/195996307-34a42462-ad7b-4d7d-ba8d-e77a9f78bce3.png">

<img width="535" alt="image" src="https://user-images.githubusercontent.com/110079800/195996415-afc88f7b-299d-47c9-9f0f-415a40c01d7b.png">

<img width="611" alt="image" src="https://user-images.githubusercontent.com/110079800/195996444-7ac3a049-47d5-4b1c-bfa0-7cbbc6ce7ed0.png">

### JITTER EXTRACTION AND ACCOUNTING IN STATIC TIMING ANALYSIS

<img width="617" alt="image" src="https://user-images.githubusercontent.com/110079800/195996627-ca685f98-1fb7-4b53-958d-397ba9c39ffe.png">

<img width="616" alt="image" src="https://user-images.githubusercontent.com/110079800/195997048-d03b717a-9a7e-496b-ba64-665d83f0722f.png">

### SETUP TIME - GRAPHICAL TO TEXTUAL CONVERSION

<img width="325" alt="image" src="https://user-images.githubusercontent.com/110079800/195999048-04031bd6-41d9-4cf6-a6b6-644db98c9a1c.png">

<img width="453" alt="image" src="https://user-images.githubusercontent.com/110079800/195999063-70753eb0-e3b5-43ab-bca4-6b34c5fcb09a.png">

<img width="638" alt="image" src="https://user-images.githubusercontent.com/110079800/195999230-93127e74-6227-43d9-b604-6a8e00b12db2.png">

### HOLD ANALYSIS WITH REAL CLOCKS

<img width="600" alt="image" src="https://user-images.githubusercontent.com/110079800/195999777-e2a7a927-8732-40cc-8e88-b3b9935eafb7.png">

<img width="638" alt="image" src="https://user-images.githubusercontent.com/110079800/196001499-b48b1760-61ec-40da-9dcf-601d92c37107.png">

### HOLD TIME- GRAPHICAL TO TEXTUAL CONVERSION

<img width="352" alt="image" src="https://user-images.githubusercontent.com/110079800/196001590-78956c05-69be-44ba-96e7-d10758ade9b2.png">

<img width="486" alt="image" src="https://user-images.githubusercontent.com/110079800/196001607-4fc09948-5fcd-4b2b-a2cb-aba18988a334.png">

<img width="623" alt="image" src="https://user-images.githubusercontent.com/110079800/196001833-bc20367d-eeea-4de8-9b1a-b9bc5b6bb0c6.png">

## SOURCES OF VARIATION - ETCHING PROCESS VARIATION

<img width="565" alt="image" src="https://user-images.githubusercontent.com/110079800/196002602-b39dfa49-970c-4522-9d30-d76c2fc7d865.png">

<img width="617" alt="image" src="https://user-images.githubusercontent.com/110079800/196002651-91c526c9-1eb4-437c-b862-3f55c7d7a4df.png">

<img width="515" alt="image" src="https://user-images.githubusercontent.com/110079800/196002916-2d9ead20-600d-40d9-8f9f-562b8fd70ba6.png">

<img width="621" alt="image" src="https://user-images.githubusercontent.com/110079800/196002935-c5be1757-186e-4a11-a43a-21bec6987b4a.png">

<img width="553" alt="image" src="https://user-images.githubusercontent.com/110079800/196002955-e7498fbc-3129-421c-b59d-5760443a0b69.png">

## SOURCE OF VARIATION - OXIDE THICKNESS

<img width="601" alt="image" src="https://user-images.githubusercontent.com/110079800/196003994-8fd675d0-ca2e-4ee5-b1e0-fbcd10be194d.png">

<img width="510" alt="image" src="https://user-images.githubusercontent.com/110079800/196004045-db35c0e5-9640-40e9-ace7-8467aedcd522.png">

### PROPAGATION DELAY OF INVERTER CELL

<img width="562" alt="image" src="https://user-images.githubusercontent.com/110079800/196004107-72497b3e-a03b-4759-82ca-e5458a76d3db.png">

<img width="545" alt="image" src="https://user-images.githubusercontent.com/110079800/196004169-b75e955b-691a-4879-b5e3-aa2566ad9bf7.png">

## RELATIONSHIP BETWEEN RESISTANCE,DRAIN CURRENT AND DELAY

<img width="540" alt="image" src="https://user-images.githubusercontent.com/110079800/196004464-aba6dfbb-9918-485f-a9ee-116d94bde686.png">

### 'R' OF INVERTER CELL

<img width="552" alt="image" src="https://user-images.githubusercontent.com/110079800/196004590-48ceebf4-f828-4508-a5d8-5fa64a87c5fd.png">

<img width="626" alt="image" src="https://user-images.githubusercontent.com/110079800/196004720-c514b3d1-e4fd-4f87-acd2-4d2619cd868d.png">

<img width="520" alt="image" src="https://user-images.githubusercontent.com/110079800/196004793-d3cb626e-e149-4c28-8e81-59205d4386f1.png">

## OCV BASED SETUP TIMING ANALYSIS














