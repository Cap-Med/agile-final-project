# agile-final-project
This project is an example of Agile application in the context of agile intorduction training


---------------------------------------------------------------
   LECTURE DES CODES DEFAUTS
---------------------------------------------------------------

Calculateur : VCU (0x82)
Nombre de défauts enregistrés : 8
P1AF209 (28h - Momentary) High Voltage battery pack: Excessive contactor close requests - Component Failures
U118A87 (2Fh - Permanent++) IS/HS1 CAN network : LVNSD control unit frame is confirmed absent - Missing message
U115E87 (2Fh - Permanent++) E_CAN network : FMCU frame is confirmed absent - Missing message
U147581 (2Fh - Permanent++) CAN network : invalid data received from BCM control unit - Invalid serial data received
P105804 (28h - Momentary) Switch 1 failure - System Internal Failures
P17C309 (2Fh - Permanent++) Park lock actuator - Component Failures
U1F0000 (2Eh - Permanent+) Not historized defect event  - No Subtype information
U225D87 (2Ch - Permanent) BSI_LIN 1 network: DEFOG_SENSOR_WINDSHIELD frame is confirmed absent - Missing message

Calculateur : ESP/ABS (0x8D)
Pas de défaut enregistré

Calculateur : DAE (0x95)
Nombre de défauts enregistrés : 7
C110BA2 (28h - Momentary) System voltage - System Voltage Low
U012987 (28h - Momentary) Lost Communication With Brake System Control Module "A" - Missing message
U041581 (28h - Momentary) Invalid Data Received From Anti-Lock Brake System (ABS) Control Module - Invalid serial data received
U029487 (28h - Momentary) Lost Communication With Powertrain Control Monitor Module - Missing message
U014187 (28h - Momentary) Lost Communication With Body Control Module "A" - Missing message
U042281 (2Fh - Permanent++) Invalid Data Received From Body Control Module - Invalid serial data received
U133082 (28h - Momentary) CAN network : erroneous data or too short frame received from MVC unit - Alive/sequence counter incorrect/not updated

Calculateur : RBG (0x04)
Nombre de défauts enregistrés : 6
B00D567 (2Eh - Permanent+) Restraint System Passenger Disable Indicator - Signal incorrect after event
B140016 (28h - Momentary) Supply voltage fault - Circuit voltage below threshold
U012187 (2Eh - Permanent+) Lost Communication With Anti-Lock Brake System (ABS) Control Module "A" - Missing message
U041581 (28h - Momentary) Invalid Data Received From Anti-Lock Brake System (ABS) Control Module - Invalid serial data received
U193587 (2Ch - Permanent) Vehicule_CAN network : eVCU control unit frame is confirmed absent - Missing message
U194687 (2Eh - Permanent+) Vehicule_CAN network : Body Control Unit gateway frame is confirmed absent - Missing message



Panneau Diag :
---------------------------------------------------------------
4204.7829  CAN_HS1  82   -->   10 03
4204.7966  CAN_HS1  82   <--   50 03 00 C8 00 14
4205.0549  CAN_HS1  82   -->   19 02 2F
4205.1560  CAN_HS1  82   <--   59 02 7F 1A F2 09 28 D1 8A 87 2F D1 5E 87 2F D4 75 81 2F 10 58 04 28 17 C3 09 2F DF 00 00 2E E2 5D 87 2C
4205.2173  CAN_HS1  82   -->   10 01
4205.2412  CAN_HS1  82   <--   50 01 00 C8 00 14
4205.2524  CAN_HS1  88   -->   10 03
4205.5133  CAN_HS1  88   -->   81
4205.7902  CAN_HS1  89   -->   81
4206.0545  CAN_HS1  89   -->   10 03
4206.3217  CAN_HS1  8A   -->   10 03
4206.5998  CAN_HS1  8A   -->   81
4206.8667  CAN_HS1  8D   -->   81
4206.8826  CAN_HS1  8D   <--   7F 81 11
4207.1371  CAN_HS1  8D   -->   10 03
4207.1531  CAN_HS1  8D   <--   50 03 00 32 01 F4
4207.4134  CAN_HS1  8D   -->   19 02 2F
4207.4280  CAN_HS1  8D   <--   59 02 FF
4207.4327  CAN_HS1  8D   -->   10 01
4207.4490  CAN_HS1  8D   <--   50 01 00 32 01 F4
4207.4589  CAN_HS1  90   -->   10 03
4207.7228  CAN_HS1  90   -->   81
4207.9906  CAN_HS1  95   -->   81
4208.0074  CAN_HS1  95   <--   7F 81 11
4208.2631  CAN_HS1  95   -->   10 03
4208.2810  CAN_HS1  95   <--   50 03 00 C8 01 F4
4208.5447  CAN_HS1  95   -->   19 02 2F
4208.5942  CAN_HS1  95   <--   59 02 FF 51 0B A2 28 C1 29 87 28 C4 15 81 28 C2 94 87 28 C1 41 87 28 C4 22 81 2F D3 30 82 28
4208.6450  CAN_HS1  95   -->   10 01
4208.6640  CAN_HS1  95   <--   50 01 00 C8 01 F4
4208.6842  CAN_HS1  A7   -->   10 03
4208.9496  CAN_HS1  A7   -->   81
4209.2204  CAN_HS1  04   -->   81
4209.2403  CAN_HS1  04   <--   7F 81 11
4209.5016  CAN_HS1  04   -->   10 03
4209.5338  CAN_HS1  04   <--   50 03 00 C8 00 14
4209.8030  CAN_HS1  04   -->   19 02 2F
4210.1360  CAN_HS1  04   <--   59 02 FF 80 D5 67 2E 94 00 16 28 C1 21 87 2E C4 15 81 28 D9 35 87 2C D9 46 87 2E
4210.1804  CAN_HS1  04   -->   10 01
4210.1986  CAN_HS1  04   <--   50 01 00 C8 00 14

