# Filtering-with-AND-OR-and-NOT-Operators

<h2>Objective</h2>

Use `AND`, `OR`, and `NOT` operators to filter log in attempts in the Maria Database.

<h2>Tasks</h2>

- Retrieve all failed login attempts after business hours.
- Retrieve all log in attempts that occurred on dates: `2022-05-08` and `2022-05-09`.
- Retrieve logins that didn't originate in `MEXICO`.
- Retrieve information about certain employees in the `Marketing` department.
- Retrieve information about employees in the `Sales` and `Finance` departments.
- Obtain information about employees who are not in the `Information Technology` department.

<h2>Steps Taken</h2>

- Investigated the **login_time** and **success** columns of the **log_in_attempts** table for failed login attempts made after business hours. `success = 0` indicates the login attempt was unsuccessful in this scenario.

![1](https://github.com/DigitalWatchmen/Filtering-with-AND-OR-and-NOT-Operators/assets/164795269/5638e02d-d5f8-403e-b4e4-1826cb77c861)

- Investigated the **login_date** column of the **log_in_attempts** table for all log in attempts made on `2022-05-08` and `2022-05-09`.

![2 1](https://github.com/DigitalWatchmen/Filtering-with-AND-OR-and-NOT-Operators/assets/164795269/4dbc144c-b5a3-4b0d-b30f-c94d396cb3fa)

![2 2](https://github.com/DigitalWatchmen/Filtering-with-AND-OR-and-NOT-Operators/assets/164795269/fd27ad16-26cb-41c7-ba8a-d2cdc7248e8f)

- Investigated the **country** column of the **log_in_attempts** table for all log in attempts outside of `MEXICO`.

![3 1](https://github.com/DigitalWatchmen/Filtering-with-AND-OR-and-NOT-Operators/assets/164795269/88f5bed8-36d8-4c33-bbf6-c0229436fb34)

![3 2](https://github.com/DigitalWatchmen/Filtering-with-AND-OR-and-NOT-Operators/assets/164795269/d594471c-1e40-4ae1-8571-7f0b99d42bf0)

![3 3](https://github.com/DigitalWatchmen/Filtering-with-AND-OR-and-NOT-Operators/assets/164795269/cc4d2678-aec6-4364-9c8c-2ee98e33f125)

![3 4](https://github.com/DigitalWatchmen/Filtering-with-AND-OR-and-NOT-Operators/assets/164795269/11b7d22b-0a84-4ec8-927d-2e54e374dbf7)

- Investigated the **department** and **office** columns of the **employees** table for all employees in the `Marketing` department inside of the `East` offices. 

![4](https://github.com/DigitalWatchmen/Filtering-with-AND-OR-and-NOT-Operators/assets/164795269/d3f8a0ff-6322-458e-a251-4ddf887abf4f)

- Investigated the **department** column of the **employees** table for all employees within the `Sales` and `Finance` departments.

![5 1](https://github.com/DigitalWatchmen/Filtering-with-AND-OR-and-NOT-Operators/assets/164795269/6156c052-1497-4ea4-949f-8dbe18ee9846)

![5 2](https://github.com/DigitalWatchmen/Filtering-with-AND-OR-and-NOT-Operators/assets/164795269/57ebabb8-4a0b-4d5b-bb35-8efa842f5b88)

- Investigated the **department** column of the **employees** tables for all employees not within the `Information Technology` department. 

![6 1](https://github.com/DigitalWatchmen/Filtering-with-AND-OR-and-NOT-Operators/assets/164795269/2a551da7-c4f5-4b73-8b11-12458cf1ca8c)

![6 2](https://github.com/DigitalWatchmen/Filtering-with-AND-OR-and-NOT-Operators/assets/164795269/de331f3b-ce5f-4487-a621-310b87d74066)

![6 3](https://github.com/DigitalWatchmen/Filtering-with-AND-OR-and-NOT-Operators/assets/164795269/834e8ca1-e643-4009-bde7-39dcec7ba5a3)

![6 4](https://github.com/DigitalWatchmen/Filtering-with-AND-OR-and-NOT-Operators/assets/164795269/588f8859-460e-4bfc-b4fe-7abcf27e4c91)
