| **Transition ID** | **From State**    | **Event**                     | **To State**      | **Req. ID** |
| :---------------: | ----------------- | ----------------------------- | ----------------- | :---------: |
|       **T1**      | IDLE              | New delivery request received | NAVIGATING        |      R2     |
|       **T2**      | NAVIGATING        | Obstacle detected             | AVOIDING_OBSTACLE |      R4     |
|       **T3**      | AVOIDING_OBSTACLE | Obstacle avoided              | NAVIGATING        |      R5     |
|       **T4**      | NAVIGATING        | Destination reached           | DELIVERING        |      R6     |
|       **T5**      | DELIVERING        | Delivery successful           | RETURNING         |      R8     |
|       **T6**      | NAVIGATING        | Battery becomes very low      | RETURNING         |      R9     |
|       **T7**      | RETURNING         | Warehouse reached             | IDLE              |     R10     |
