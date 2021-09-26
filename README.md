# `_cuckoorooza_`
![keycorn](https://user-images.githubusercontent.com/70670631/134788868-e594097d-cbcf-4ef9-879a-c6c3d259c47f.png)

Cuckoorooza ("kukuruza") is how you say the word corn in Russian.  It's one of my favorite sounds and the portmanteau effect of prefixing it with the English euphemism for crazy/nutty/kooky is simply delightful.  So there's that.

****************

## How it started

Our perspectives are a function of our unique life experiences, and mine is heavily influenced by my background in document/records and information management. Unsurprisingly, I find myself focused on distributed storage and the amazing breakthroughs systems like IPFS and Filecoin have made in the space. But I also feel like there is currently an imbalance in the distributed storage ecosystem, characterized by a heavily slanted focus on storage scalability and persistence; and a corresponding void around data hygiene (e.g., lifecycle, retention and disposition).

All things naturally conform to a lifecycle. It's just the way our world works. Trees shed; catterpillars metamorphose; eventually all plants and animals die and new ones are born to take their place. Even the Universe itself is in a constant state of flux, somewhere on its own axis of existence - its own lifecycle. There is a natural balance, or hygiene if you will, to the very concept of *lifecycle* that simply resonates with the operational underpinnings of our world. 

Data and information is no different. It too comes into existence and follows a course charted by its unique utility/relevance pattern. There are times when a document, or its metadata (or both), will be more relevant and more valuable than at other times in its life. Eventually it will cease to be relevant or have any value altogether. Nobody needs the scanned image of my driver's license from 20 years ago.

Even if the hubris-heavy idea of anything we create being truly *permanent* is a laughable fallacy in the grand scheme of things, content and data that is bound by a contract of persistence and immutability but unchecked by a lifecycle-driven counterbalance runs the risk of eventually imploding under its own weight.

****************

## How it's going

This project attempts to introduce the idea of time and access limits to distributed storage artifacts. Users will be able to grant access to their files (potentially an NFT use case?) and will be able to assign metadata to the file. Part of the metadata componentry will be the ability to select a retention period (days/months/years). After the retention period elapses, any access keys will be crypt-shredded.  

The following artifacts will be supported in this initial use case:

* Files (definitely) 
* File metadata (maybe - if there's time)

### Workflow

1. User will connect to cuckooroza 
2. They will select file(s) from their computer for upload to an IPFS (or Filecoin) node
3. They will be presented with an interface allowing them to select up to 5 *(<-- arbitrary number here)* metadata fields, as well as an optional retention setting
4. The content will upload
5. The user will be presented with a shareable key for access
6. When the retention period has elapsed, the access will no longer work

****************

## Pie *(corn muffin?)* in the Sky

Imagining some super well-developed future state ... 

### Taxonomy Governance

What if the user is not a single individual but a group, storing shared documents on a distributed file system. What if there is disagreement on naming conventions or metadata sets? Would a taxonomy DAO be able to solve that problem? DAO members would be able to vote for how best to represent the content that matters to them, for easier search/retrieval and realistic retention policies. Part of the DAO voting process might be contractual obligations (in a legal or regulatory compliance context) for storing this type of content.

### Commoditizing personal information

It would be great if users of this dApp would be able to hook into the various functions that generate metadata on their behalf (thinking about the social media context here), so that they could control how it is stored, and could conceivably charge for access.  Imagine a future where, rather than Facebook and Google controlling your data and deciding who they get to sell it to and how, *you* are the sole custodian of *your* information, and *you* get to decide who has access to what, and at what price.

