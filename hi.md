
| Event ID | User Name | Activity | Process ID | Backend Communication | Detailed Process | AD Handshake |
--|--|--|--|--|--|--
| 4624     | John Doe | Successful Login | 1001 | Successful Verification of Credentials | 1. User submits login request. 2. Login form presented to user. 3. User inputs credentials. 4. System performs input validation. 5. System verifies credentials against database. 6. Successful verification of credentials. 7. Session established for user. | 1. System sends authentication request to AD. 2. AD verifies credentials. 3. AD sends response to system indicating successful verification of credentials. |
| 4625     | Jane Doe | Failed Login | 1002 | Failed Verification of Credentials | 1. User submits login request. 2. Login form presented to user. 3. User inputs credentials. 4. System performs input validation. 5. System verifies credentials against database. 6. Failed verification of credentials. | 1. System sends authentication request to AD. 2. AD verifies credentials. 3. AD sends response to system indicating failed verification of credentials. |

