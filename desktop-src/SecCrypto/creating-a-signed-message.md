---
Description: 'Depicts the tasks that must be accomplished to create a signed message.'
ms.assetid: '61896022-28c2-4f70-977a-c990b4b23c55'
title: Creating a Signed Message
---

# Creating a Signed Message

The following illustration depicts the tasks that must be accomplished to create a signed message. The steps are listed following the illustration.

![signing a message](images/signdmsg.png)

**To create a signed message**

1.  Create the data (if necessary) and get a pointer to it.
2.  Open a [*certificate store*](security.c_gly#-security-certificate-store-gly) that contains the signer's certificate.
3.  Get the [*private key*](security.p_gly#-security-private-key-gly) for the certificate. A property must be set on the certificate before using it, to tie a certificate to a particular [*CSP*](security.c_gly#-security-csp-gly), and, within that CSP, to a particular private key. This needs to be set once.
4.  Choose a hashing algorithm for the digest operation. We recommend that the hashing algorithm be selected from a configurable location that can be subsequently updated without requiring changes to code.
5.  Send the data through the hashing function by using the hashing algorithm, thus creating a [*hash*](security.h_gly#-security-hash-gly) (digest) of the data.
6.  Using the [*private key*](security.p_gly#-security-private-key-gly) obtained through the property on the certificate, encrypt the digest, creating the signature.
7.  Include the following in the signed message:

    -   The signed data
    -   The hash algorithm
    -   The signature
    -   The signer identifier (certificate issuer and serial number)
    -   The signer's certificate (optional)

For a detailed procedure and example, see [Procedure for Signing Data](procedure-for-signing-data.md) and [Example C Program: Signing a Message and Verifying a Message Signature](example-c-program-signing-a-message-and-verifying-a-message-signature.md).

 

 


