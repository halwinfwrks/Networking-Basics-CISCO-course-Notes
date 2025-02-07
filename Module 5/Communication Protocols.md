# **Communication Protocols**

---

## **1. Communication Protocols**

Communication in our daily lives takes many forms and occurs in many environments. We have different expectations depending on whether we are chatting via the internet or participating in a job interview. Each situation has its corresponding expected behaviors and styles.

Before beginning to communicate with each other, we establish rules or agreements to govern the conversation. These agreements include the following:

What method of communication should we use?
What language should we use?
Do we need to confirm that our messages are received?

These rules, or protocols, must be followed in order for the message to be successfully delivered and understood. Among the protocols that govern successful human communication are these:

- An identified sender and receiver
- Agreed upon method of communicating (face-to-face, telephone, letter, photograph)
- Common language and grammar
- Speed and timing of delivery
- Confirmation or acknowledgment requirements
  The techniques that are used in network communications share these fundamentals with human conversations.

---

## **2. Why Protocols Matter**

Just like humans, computers use rules, or protocols, in order to communicate. Protocols are required for computer to properly communicate with each other across the network. In both a wired and wireless environment, a local network is defined as an area where all hosts must "speak the same language", which, in computer terms means they must "share same protocol".

If everyone in the same room spoke a differrent language, they would not be able to communicate. Likewise, if devices in a local network did not use the same protocols, they would not be able to communicate.

Networking protocols define many aspects of communication over the local network.

| Protocol Chacteristic | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Message format**    | When a message is sent, it must use a specific format or structure. Message formats depend on the type of message and the channel that is used to deliver the message.                                                                                                                                                                                                                                                                                              |
| **Message size**      | THe rules that govern the size of the pieces communicatef across the network are very strict. They can also be different, depending on the channel used. When long message is sent from one host to another over a network, it may be necessary to break the message into smaller pieces in order to ensure that the message can be delivered reliably.                                                                                                             |
| **Timing**            | Many network communication functions are denpendent on timing. Timing determines the speed at which the bits are transmitted across the network. It also affects when an individual host can sent data and the total amount of data that can be sent in any one transmission.                                                                                                                                                                                       |
| **Encoding**          | Messages sent across the network are first converted into bits by the sending host. Each bit is encoded into a pattern of sounds, light waves, or electical impulses depending on the network media over which the bits are transmitted. The destination host receives and decodes the signals in order to interpret the message.                                                                                                                                   |
| **Encapsulation**     | Each message transmitted on a network must include a header that contains addressing information that identifies the source and destination hosts, otherwise it cannot be delivered. Encapsulation is the process of adding this information to the pieces of data that make up the message. In addition to addressing, there may be other information in the header that ensures that the message is delivered to the correct application on the destination host. |
| **Message pattern**   | Some messages requires an acknoledgment before the next message can be sent. This type of request/response pattern is a common aspect of many networking protocols. However, there are other types of messages that may be simply streamed across the network, without concern as to whether they reach their destination.                                                                                                                                          |

---
