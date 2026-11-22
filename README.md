## EXPERIMENT NO. 3 – STAIRCASE WIRING

| **Name:** |Menakaapriya M| **Reg. No.:** |26018669|
|---|---|---|---|
| **Date:** |23/11/2026| **Batch / Section:** |26ODJ153|

---

## AIM

To control the status of the given lamp by using two-way switches.

## APPARATUS REQUIRED

| S. No. | Name of the apparatus | Range / Type | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Incandescent lamp | 60 W | 1 No. |
| 2 | Lamp holder | Pendant type | 1 No. |
| 3 | SPDT switch | 230 V, 5 A | 2 Nos. |
| 4 | Wires | 1/18" | As required |
| 5 | PVC pipe | 1/4" | As required |
| 6 | Wooden board | — | 1 No. |
| 7 | Round block | — | 1 No. |
| 8 | Simulation software | Proteus Design Suite | 1 |

## THEORY

- A two-way switch is installed near the first step of the stairs. The other two-way switch is installed at the upper part where the stairs end.
- The light point is provided between the first and last stair at an adequate location and height. If the light is switched on by the lower switch, it can be switched off by the switch at the top, or vice versa.
- The circuit can also be used in places like a bedroom, where the person need not walk back to the place from where the light was switched on in order to switch it off.
- Two numbers of two-way switches are used for this purpose. The supply is given to the switch at the short-circuited (common) terminal.
- The connection to the light point is taken from the similar short-circuited (common) terminal of the second switch. The other two independent terminals of each switch are connected through cables.

## PROCEDURE

1. Place the accessories on the wiring board as per the circuit diagram.
2. Place the PVC pipe and insert two wires into the PVC pipe.
3. Take one wire; connect one end to the phase side and the other end to the middle (common) point of SPDT switch 1.
4. The upper point of SPDT switch 1 is connected to the lower point of SPDT switch 2.
5. The lower point of SPDT switch 1 is connected to the upper point of SPDT switch 2.
6. Another wire is taken through the PVC pipe, and the middle (common) point of SPDT switch 2 is connected to one end of the lamp holder.
7. The other end of the lamp holder is connected to the neutral line.
8. Screw the accessories on the board and switch on the supply.
9. Test the circuit for all possible combinations of switch positions.

## A. DIRECT CONNECTION

### Circuit diagram

<img width="609" height="400" alt="Screenshot 2026-11-20 212533" src="https://github.com/user-attachments/assets/a77cc89e-79ed-4a02-8697-339b441f1948" />


**Figure 1:** Staircase wiring – direct connection

### Tabulation 1: Truth table – direct connection

| S. No. | Switch S1 position | Switch S2 position | Lamp status (ON / OFF) |
|:---:|:---:|:---:|:---:|
| 1 |ON|ON|ON|
| 2 |ON|OFF|OFF|
| 3 |OFF|ON|OFF|
| 4 |OFF|OFF|ON|

## B. CROSS CONNECTION

### Circuit diagram

<img width="655" height="522" alt="Screenshot 2026-11-20 153821" src="https://github.com/user-attachments/assets/719be089-9c28-4b80-a6a1-7a058c297411" />


**Figure 2:** Staircase wiring – cross connection

### Tabulation 2: Truth table – cross connection

| S. No. | Switch S1 position | Switch S2 position | Lamp status (ON / OFF) |
|:---:|:---:|:---:|:---:|
| 1 |ON|ON|OFF|
| 2 |ON|OFF|ON|
| 3 |OFF|ON|ON|
| 4 |OFF|OFF|OFF|

## SIMULATION USING PROTEUS

Build both the direct and cross connection circuits in Proteus using an AC source, two SPDT switches and a lamp. Run the simulation for each switch combination and paste screenshots showing the lamp ON and OFF states.

### A. Direct connection – simulation

<img width="609" height="400" alt="Screenshot 2026-11-20 212533" src="https://github.com/user-attachments/assets/2b0d3cbc-07e1-460e-a30a-29cd9fe6cbde" />
<img width="642" height="452" alt="Screenshot 2026-11-20 154259" src="https://github.com/user-attachments/assets/561182c1-93a6-435c-a5ad-08db83081a15" />

**Figure 3:** Proteus simulation – direct connection

### B. Cross connection – simulation

<img width="655" height="522" alt="Screenshot 2026-11-20 153821" src="https://github.com/user-attachments/assets/0447a428-95a0-4405-92ca-dc22e5a90a6b" />
<img width="625" height="466" alt="Screenshot 2026-11-20 220920" src="https://github.com/user-attachments/assets/80681bc0-a2d6-4624-a7c1-05f9db0d1d91" />


**Figure 4:** Proteus simulation – cross connection

## RESULT

Thus, the staircase wiring was connected and tested for both direct and cross connections, and the lamp was controlled from two different places using two-way switches.
