# Android-AES-Crypto
Library for android aes crypto

Android native AES encryption, when running on Android 7.0, directly reported an error. The reason is that Android's key generation method has changed, and the specific error is as follows:

New versions of the Android SDK no longer support the Crypto provider

So aes-crypto core perfectly solves Android Aes encryption