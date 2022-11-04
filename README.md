# awesome-identifiers
Pick the best ID for your database


## SERIES (aka INT)
### Specification
* Example: 13
* Number Range: 0 - 4,294,967,295
* Numbers of bit: 32
* Numbers of characters: 0 - 10

### DB Specification
* Suggested DB Type: INT
* Performance impact on Database (eg. Storage, JOIN operations, etc...): very low
* Is timestamp based: No
* Sortable by creation date: Yes
* Can be easly used in a distributed ecosystem: No
* Support cursor-based pagination without adding a dedicated createdAt field: Yes
* Needs to be configured (eg. machine ID, shard id): No

### BIT Distribution
* Time: 0
* Sequence/Counter: 32 bit
* Machine Id + Process Id: 0
* Randomnes: 0

### Security
* Is completly Random?: No
* Predictability of the ID: High
* Leaks the count of items: Yes
* Leaks information about the machine/process: No
* Leaks the date of creation: Partially (thorugh interpolation of known dates it could be guessed)
* Suggested Hashing with HashIds: Yes
