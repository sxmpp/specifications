---
### sxmpp - XMPP more secure
### SXEP stands for sxmpp extension protocol.
---
#
#
**SXEP-0001** We inherit the following standards from original XMPP specification. In case of contradiction with this standards SXEP has higher priority.
- RFC 6120: XMPP CORE
- RFC 6121: XMPP IM
- RFC 7395: XMPP Subprotocol for WebSocket
- XEP-0004: Data Forms 2.9
- XEP-0012: Last Activity 2.0
- XEP-0030: Service Discovery 2.5rc3
- XEP-0049: Private XML Storage 1.2
- XEP-0054: vcard-temp 1.2
- XEP-0077: In-Band Registration 2.4
- XEP-0092: Software Version 1.1
- XEP-0138: Stream Compression 2.0
- XEP-0160: Best Practices for Handling Offline Messages 1.0.1
- XEP-0163: Personal Eventing Protocol 1.2.1
- XEP-0191: Blocking Command 1.3
- XEP-0199: XMPP Ping 2.0
- XEP-0220: Server Dialback 1.1.1
- XEP-0237: Roster Versioning 1.3

**SXEP-0002** No registration should be present nor any passwords.

**SXEP-0003** Client parties should be able to transmit text messages in an encrypted way only. Plain text messages should not be present, but all base protocol messages (XML data) should be in plain text. No need to encypt this.

**SXEP-0004** Usernames are public keys or some data which can be used to get public key without any decryption.
