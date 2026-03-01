# FCMFID-A-Full-Coverage-Multi-bit-Fault-Tolerant-Instruction-Decoder-for-RISC-V-based-softcore
 a new Full-Coverage Multi-Bit Fault-Tolerant Instruction Decoder (FCMFID) design that enhances the reliability of a pipeline RV32I processor core by providing protection to the full Instruction decoder, including IF/ID and ID/EX pipeline registers. 
The instruction decoder is one of the most critical components of a CPU, particularly in space applications. Its primary role is to generate control signals for processor components and to provide addresses for register file read/write operations. Among the pipeline registers, the IF/ID and ID/EX registers are especially important, as they are directly integrated with the decoding stage. As shown in Fig. 1, heavy-ion strikes on the instruction decoder and its associated pipeline registers (IF/ID and ID/EX) induce single-event multiple upsets (SEMUs), leading to functional failure in the decode stage. Such errors propagate to subsequent pipeline stages, ultimately resulting in a complete system breakdown. Thus, for environments vulnerable to radiation, protecting the instruction decoder and its pipeline registers (IF/ID and ID/EX) through fault masking becomes indispensable. To address this critical issue, an improved fault-tolerant scheme and architecture are proposed to completely protect the decoder stage, which has been integrated in a pipeline RV32I soft-core (in-house developed). The proposed scheme and micro-architectures are described in the subsequent subsections.
<img width="1220" height="489" alt="image" src="https://github.com/user-attachments/assets/4a5c5705-4b4c-4502-aa5d-2f885d3b7557" />
<img width="1342" height="760" alt="image" src="https://github.com/user-attachments/assets/c8aa7359-bbb7-4b8f-a239-88c750661c28" />
<img width="1328" height="758" alt="image" src="https://github.com/user-attachments/assets/566e4b31-79ac-4076-a34b-f143b0f0c64e" />
<img width="989" height="613" alt="image" src="https://github.com/user-attachments/assets/3d9098ae-8b93-4944-9e90-fe75ea182b14" />
<img width="1101" height="629" alt="image" src="https://github.com/user-attachments/assets/4ca15d71-43f6-48f0-b4ee-b84144effe70" />
<img width="1188" height="557" alt="image" src="https://github.com/user-attachments/assets/1c5c7770-d404-4dfb-a778-cf406e9425d4" />

<img width="925" height="645" alt="image" src="https://github.com/user-attachments/assets/0f1ab9db-df9d-4185-a787-9c973a5e6038" />
<img width="1305" height="743" alt="image" src="https://github.com/user-attachments/assets/3998792d-477e-4fcd-9e09-8f68fb81a8a9" />

publication link: https://www.sciencedirect.com/science/article/pii/S0167926026000349
