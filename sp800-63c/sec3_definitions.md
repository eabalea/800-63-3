<a name="sec3"></a>

## 3. Definitions and Abbreviations

There are a variety of definitions used in the area of authentication. While many terms are consistent with earlier revisions version of SP 800-63, some have changed in this revision. Since there is no single, consistent definition of many of these terms, careful attention to how the terms are defined here is warranted.

The definitions in this section are primarily those that are referenced in this document. Refer to the other documents in the SP 800-63 document family for additional definitions and abbreviations specific to their content.

#### Federation
A process that allows for the conveyance of identity and authentication information across a set of networked systems. These systems are often run and controlled by disparate parties in different network and security domains.

#### Identity Provider (IdP)
The common term in federation protocols for the credential service provider (CSP) that manages the subscriber's primary authentication credentials and issues assertions derived from those credentials. 

#### Authenticated Protected Channel
A communication channel that uses approved encryption where the initiator of the connection (client) has authenticated the recipient (server). Authenticated protected channels provide confidentiality and man-in-the-middle protection and are frequently used in the user authentication process. TLS [[BCP 195]](#bcp195) is an example of an authenticated protected channel when the certificate presented by the recipient is verified by the initiator.

#### Attribute
A claim of a named quality or characteristic inherent in or ascribed to someone or something. (See term in [[ICAM]](#ICAM) for more information.)

#### Assertion
A statement from a verifier to a Relying Party (RP) that contains identity information about a subscriber. Assertions may also contain verified attributes.

#### Assertion Reference
A data object, created in conjunction with an assertion, which identifies the verifier and includes a pointer to the full assertion held by the verifier.

#### Authentication
The process of establishing confidence in the identity of users or information systems.

#### Authentication Protocol
A defined sequence of messages between a claimant and a verifier that demonstrates that the claimant has possession and control of a valid authenticator to establish his/her identity. Secure authentication protocols also demonstrate to the claimant that he or she is communicating with the intended verifier.

#### Pairwise Pseudonymous Identifier
An opaque unguessable subscriber identifier generated by a CSP for use at a specific individual RP. This identifier is only known to and only used by one CSP-RP pair.