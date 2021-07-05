# Android-Keystore-Example
Supports android 4.3 and above.

The Android Keystore system lets you store cryptographic keys in a container to make it more difficult to extract from the device. Once keys are in the keystore, they can be used for cryptographic operations with the key material remaining non-exportable. Moreover, it offers facilities to restrict when and how keys can be used, such as requiring user authentication for key use or restricting keys to be used only in certain cryptographic modes.

Example shows simple steps:
1. Generate new key using keygenerator.
2. Encrypt data using key and iv using AES Encryption
3. Decrypt data using Same key and Iv using Android keyStore.


Note: This example demostrate for For API level >=23, where KeyStore API generates random AES keys Using KeyGenParameter specs. For API level <23 use KeyPairGeneratorSpec API for generating public and private key. It uses RSA encryption.
