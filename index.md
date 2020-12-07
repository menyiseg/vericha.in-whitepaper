---
layout: default
---

## Connecting Blockchain Addresses with Trusted Entities

Attila Perez

[attila@vericha.in](mailto:attila@vericha.in)

December 2020

##### Abstract

Public accountability and trust in entities are necessary parts of a working decentralized financial (defi) ecosystem. Vericha.in aims to fill a gap in the defi space by providing a living and breathing, publicly verifiable source for blockchain address ownership. This is achieved using a combination of cryptographic digital identity verification techniques as well as an open backend that allows for vetting of the service’s practices by third parties. The service never stores persistent addresses, only hashes, creating a one-way lookup system. Scraping of an entity’s owned addresses becomes a fruitless endeavor. An end-user-facing API allows for integration into third party wallets and public projects.


>As society becomes more and more complex, cheating will in many ways become progressively easier and easier to do and harder to police or even understand.
There should be whitespace between paragraphs. 
>
>	-Vitalik Buterin, co-founder, Ethereum


## Requirements For Such a Service

1.  Completely public codebase, including each vector (frontend, backend, open-source API tools) ☑️
2.  Capable of defense from scraping an entity's addresses ☑️
3.  Third-parties are able to verify the legitimacy of entities ☑️


### The Solution

* * *

### Harnessing The Power of Preexisting Cryptographic Frameworks

![Ethereum Signing](https://vericha.in/assets/images/signatures1.png)

Cryptographic signatures are built into web3js, allowing ECDSA-method signed messaging completely off-blockchain. This means that there is no gas requirement, decreasing cost per function greatly. 




### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item


![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
