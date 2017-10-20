
![Alt text](https://g.gravizo.com/source/custom_mark10?https%3A%2F%2Fraw.githubusercontent.com%2FTLmaK0%2Fgravizo%2Fmaster%2FREADME.md)

<details> 
<summary></summary>
custom_mark10
[*] --> Payload;
[*] --> Action;
[*] --> Destination;
[*] --> Source;
Source : id;
Source :  private key;
Destination : id;
Destination: public key;
Payload : dict of values;
Action : type of action;
Payload --> SerializedPayload;
SerializedPayload : Schema-encoded and serialized;
Action --> SignatureHash;
Source --> SignatureHash;
Destination --> SignatureHash;
SerializedPayload --> SignatureHash;
Source --> Signature
SignatureHash --> Signature
Destination --> EncryptedPayload
SerializedPayload --> EncryptedPayload;
EncryptedPayload --> Message;
Action --> Message;
Source --> Message;
Destination --> Message;
Signature --> Message;
Message --> [*]
}
custom_mark10
</details>
