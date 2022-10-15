# Static_Timing_Analysis

###VALID TIMING PATHS

<img width="599" alt="image" src="https://user-images.githubusercontent.com/110079800/195977761-f429bc8b-ba54-4cd2-ba55-eacc16bf8263.png">

####ARRIVAL TIME: Time required for a signal to begin at the start point and reach at the end point is known as arrival time

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

