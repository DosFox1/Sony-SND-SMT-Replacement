# Sony-SND-SMT-Replacement
BETA -
A replacement for the Sony SND IC (part number 343-0045-A) as used on the Macintosh Plus, SE and others, using SMD parts.

![Sony SND SMD Front](https://github.com/user-attachments/assets/a9366a45-02f2-4450-8ef1-25b19c2cc6e2)


![Sony SND SMD Back](https://github.com/user-attachments/assets/6860037d-bd89-46c1-ab46-15233396dfbb)

# So what is it?
This is a variant of my existing Sony SND replacement, however, it uses purely SMD parts. 
My original repo for the through hole variant can be found here:
https://github.com/DosFox1/Sony-SND-THT-Replacement

The design is effectively the same, except that this variant should only require the +5v and +12v rails - there is no requirement to tap -12v from the board. 
This might work, it might not. I need to build and test it first!

**NOTE - This is Completely Untested**
# Bill Of Materials:
```blocks
Part     Value          Device                       Package  Library                Sheet

C1       100n 16V       100N_CAP_0603                C0603    Capacitors SMD         1
C2       100n 16V       100N_CAP_0603                C0603    Capacitors SMD         1
C3       100n 16V       100N_CAP_0603                C0603    Capacitors SMD         1
C4       100n 16V       100N_CAP_0603                C0603    Capacitors SMD         1
C5       1u 16V         1U_CAP_0603                  C0603    Capacitors SMD         1
C6       100n 16V       100N_CAP_0603                C0603    Capacitors SMD         1
C7       470p           470P_CAP_0603                C0603    Capacitors SMD         1
C8       1n 50V         1N_CAP_0603                  C0603    Capacitors SMD         1
C9       100n 16V       100N_CAP_0603                C0603    Capacitors SMD         1
C10      100n 16V       100N_CAP_0603                C0603    Capacitors SMD         1
C11      220p           220P_CAP_0603                C0603    Capacitors SMD         1
C13      100n 16V       100N_CAP_0603                C0603    Capacitors SMD         1
D1       5.1V           DIODE-ZENER-MMSZ5231B        SOD-323  SparkFun-DiscreteSemi  1
IC1      LM358          OPAMP-DUALU                  SO08     SparkFun-IC-Amplifiers 1
IC2      4016D          4016D                        SO14     40xx                   1
IC3      NE555DRG4      555_SOIC8                    SOIC8    ICs                    1
IC4      74LVC1G06DBV   74LVC1G06DBV                 SOT23-5  74xx-little-us         1
IC5      Turned pins    SND THT turned pins          DIP16    Pins                   1
Q1       MMBT3906       TRANS_PNP-PMBT3906|MMBT3906L SOT23-3  SparkFun-DiscreteSemi  1
Q2       MMBT3904       TRANS_NPN-MMBT2222AL         SOT23-3  SparkFun-DiscreteSemi  1
R1       1M             GENERIC_RESISTOR_0603        R0603    Resistors SMD          1
R2       1M             GENERIC_RESISTOR_0603        R0603    Resistors SMD          1
R3       6K8            GENERIC_RESISTOR_0603        R0603    Resistors SMD          1
R4       47K            47K_RESISTOR                 R0603    Resistors SMD          1
R5       1k             1K_RESISTOR_0603             R0603    Resistors SMD          1
R6       47K            47K_RESISTOR                 R0603    Resistors SMD          1
R7       68K            GENERIC_RESISTOR_0603        R0603    Resistors SMD          1
R8       150K           GENERIC_RESISTOR_0603        R0603    Resistors SMD          1
R9       470K           GENERIC_RESISTOR_0603        R0603    Resistors SMD          1
R10      470K           GENERIC_RESISTOR_0603        R0603    Resistors SMD          1
R11      200K           GENERIC_RESISTOR_0603        R0603    Resistors SMD          1
R12      150R           150R_RESISTOR_0603           R0603    Resistors SMD          1
```
