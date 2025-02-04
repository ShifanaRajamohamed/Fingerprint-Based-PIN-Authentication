# Fingerprint-Based-PIN-Authentication
The PIN authentication system with fingerprint for each digit combines PIN authentication with a biometric finger recognition system. This system is designed in such a way that adds to security by ensuring that each digit of the PIN is verified with a unique fingerprint.

The system consists of a number pad with each digit embedded with 10 fingerprint sensors. Users can enter their PIN by placing fingers corresponding to each digit in the PIN of their choice.

An input module is included to handle the credentials entered by the users. It then directs them to subsequent processes. An Arduino microcontroller connected to a multiplexer is deployed, which allows for handling multiple fingerprint sensors.

The collected data is then forwarded for the encryption process in order to secure user credentials during storage and verification. AES-256 encryption algorithm can be used for encrypting each fingerprint template along with its associated digit.The encrypted data is then stored in a NoSQL database. 

A verification module is included, which retrieves the encrypted fingerprint templates and PIN from the database, decrypts them, and compares them with the user's input. It ensures accurate matching between the stored and entered credentials. An authentication module then interprets the comparison results and authenticates the user.

A digital display is incorporated to prompt the user throughout the authentication process and display the authentication results.

The hardware components of the system include the fingerprint sensors, a microcontroller with multiplexer, a number pad, a digital display , all placed in a plastic case. The entire system is designed to offer a unique, yet secure authentication solution, hence making it suitable for banking applications.
