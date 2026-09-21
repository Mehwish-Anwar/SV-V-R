# SV-V-R
| Req. ID | Description                                                                                    | Priority |
| ------- | ---------------------------------------------------------------------------------------------- | -------- |
| **R1**  | The robot shall remain in **IDLE** when it is switched on and no delivery request is received. | High     |
| **R2**  | The robot shall start **NAVIGATING** when a delivery request is received.                      | High     |
| **R3**  | The robot shall navigate toward the requested destination while in the **NAVIGATING** state.   | High     |
| **R4**  | The robot shall enter **AVOIDING_OBSTACLE** when an obstacle is detected during navigation.    | High     |
| **R5**  | The robot shall return to **NAVIGATING** after successfully avoiding the obstacle.             | High     |
| **R6**  | The robot shall enter **DELIVERING** when it reaches the destination.                          | High     |
| **R7**  | The robot shall not enter **DELIVERING** directly from **IDLE** or **AVOIDING_OBSTACLE**.      | High     |
| **R8**  | The robot shall enter **RETURNING** after successfully delivering the package.                 | High     |
| **R9**  | The robot shall enter **RETURNING** when its battery becomes critically low during navigation. | High     |
| **R10** | The robot shall return to **IDLE** after reaching the warehouse.                               | High     |
