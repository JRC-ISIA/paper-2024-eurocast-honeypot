# A Generative Model Based Honeypot for Industrial OPC UA Communication

The dataset is available in the subfolder dataset/.
It is a CSV-file, organized as follows:

| **Col.** | **Name**    | **Description**                      | **Type**  | **Symbol**        | **Unit** |
|----------|-------------|--------------------------------------|-----------|-------------------|----------|
| 0        | Time        | Elapsed time since measurement start | --        | $t$               | s        |
| 1        | Voltage0    | DC-motor 0 voltage                   | output    | $U_0$             | V        |
| 2        | Voltage1    | DC-motor 1 voltage                   | output    | $U_1$             | V        |
| 3        | Current0    | DC-motor 0 current                   | measured  | $I_0$             | A        |
| 4        | Current1    | DC-motor 1 current                   | measured  | $I_1$             | A        |
| 5        | MotorSpeed0 | Rotational speed of fan 0            | measured  | $s_0$             | rpm      |
| 6        | MotorSpeed1 | Rotational speed of fan 1            | measured  | $s_1$             | rpm      |
| 7        | Yaw         | Actual yaw angle                     | measured  | $\varPsi$         | rad      |
| 8        | Pitch       | Actual pitch angle                   | measured  | $\varTheta$       | rad      |
| 9        | TargetYaw   | Target yaw angle                     | input     | $\varPsi_T$       | rad      |
| 10       | TargetPitch | Target pitch angle                   | input     | $\varTheta_T$     | rad      |
| 11       | YawDot      | Yaw, angular velocity                | estimated | $\dot{\varPsi}$   | rad/s    |
| 12       | PitchDot    | Pitch, angular velocity              | estimated | $\dot{\varTheta}$ | rad/s    |
