Overview
========

Keystore for the demonstration purpose of the Secure Container for Android project.

The keystore contains two different private key/certificate entries:
- container_key
- untrusted_key

The container_key is used to sign applications which should run within the secure
container. For untrusted applications which should run in the default untrusted
application domain the untrusted_key should be used (any other key can be used for this as
well but to keep things easy the keystore already contains one).

The keystore itself and the private keys are secured with the same password which is: test123
