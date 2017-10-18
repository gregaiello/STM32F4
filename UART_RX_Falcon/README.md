# STM32F4
Reverse engineering of the Falcon robot by Novint, code to read the UART from the gripper with the buttons, the state of the 4 buttons is encoded with values from 0 (no button pressed) to F (4 button pressed). <br />
The UART Packet is composed by 4 bytes: Start, A, 0, BUTTON_STATUS, End
