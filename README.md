# Awesome Identifiers
Pick the best ID for your database

## Table of Content
- [SERIES (aka INT)](#series-aka-int)
- [BIGSERIES (aka BIGINT)](#bigseries-aka-bigint)

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky"></th>
    <th class="tg-c3ow">SERIES (aka INT)</th>
    <th class="tg-c3ow">BIGSERIES (aka BIGINT)</th>
    <th class="tg-c3ow">Snowflake ID</th>
    <th class="tg-c3ow">Sonyflake</th>
    <th class="tg-c3ow">CUID</th>
    <th class="tg-c3ow">nanoId</th>
    <th class="tg-c3ow">xid</th>
    <th class="tg-c3ow">ULID</th>
    <th class="tg-c3ow">UUIDv4</th>
    <th class="tg-c3ow">UUIDv1</th>
    <th class="tg-c3ow">LexicalUUID </th>
    <th class="tg-c3ow">Flake</th>
    <th class="tg-c3ow">ObjectId (Mongo)</th>
    <th class="tg-c3ow">Ksuid</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">General Specification</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Example</td>
    <td class="tg-c3ow">13</td>
    <td class="tg-c3ow">120310392</td>
    <td class="tg-c3ow">1584093427933380608</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">cjld2cjxh0000qzrmn831i7rn</td>
    <td class="tg-c3ow">V1StGXR8_Z5jdHi6B-myT</td>
    <td class="tg-c3ow">9m4e2mr0ui3e8a215n4g</td>
    <td class="tg-c3ow">0123456789ABCDEFGHJKMNPQRSTVWXYZ</td>
    <td class="tg-c3ow">fa23bd22-a5ac-46c2-8a67-bda88ca3e6e4</td>
    <td class="tg-c3ow">e6a21b7c-5c2f-11ed-9b6a-0242ac120002</td>
    <td class="tg-c3ow">00048df6-faef-2bb5-2772-4e30d6b86086</td>
    <td class="tg-c3ow">8HFaR8qWtRlGDHnO57</td>
    <td class="tg-0pky">507f1f77bcf86cd799439011</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Number Range</td>
    <td class="tg-c3ow">0 - 4,294,967,295</td>
    <td class="tg-c3ow">0 - 18,446,744,073,709,551,615</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">-</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Numbers of bit</td>
    <td class="tg-c3ow">32</td>
    <td class="tg-c3ow">64</td>
    <td class="tg-c3ow">64</td>
    <td class="tg-c3ow">64</td>
    <td class="tg-c3ow">200</td>
    <td class="tg-c3ow">variable</td>
    <td class="tg-c3ow">96</td>
    <td class="tg-c3ow">128</td>
    <td class="tg-c3ow">128</td>
    <td class="tg-c3ow">128</td>
    <td class="tg-c3ow">128</td>
    <td class="tg-c3ow">128</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Numbers of characters</td>
    <td class="tg-c3ow">0 - 10</td>
    <td class="tg-c3ow">0 - 20</td>
    <td class="tg-c3ow">19</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">25</td>
    <td class="tg-c3ow">variable</td>
    <td class="tg-c3ow">20</td>
    <td class="tg-c3ow">32</td>
    <td class="tg-c3ow">36</td>
    <td class="tg-c3ow">36</td>
    <td class="tg-c3ow">36</td>
    <td class="tg-c3ow"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">DB Specification</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Suggested DB Type</td>
    <td class="tg-c3ow">INT</td>
    <td class="tg-c3ow">BIGINT</td>
    <td class="tg-c3ow">BIGINT</td>
    <td class="tg-c3ow">BIGINT</td>
    <td class="tg-c3ow">VARCHAR(25)</td>
    <td class="tg-c3ow">VARCHAR(X)</td>
    <td class="tg-c3ow">VARCHAR(20)</td>
    <td class="tg-c3ow">VARCHAR(32)</td>
    <td class="tg-c3ow">UUID</td>
    <td class="tg-c3ow">UUID</td>
    <td class="tg-c3ow">UUID</td>
    <td class="tg-c3ow"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Performance impact on Database (eg. Storage, JOIN operations, etc...)</td>
    <td class="tg-c3ow">very low</td>
    <td class="tg-c3ow">low</td>
    <td class="tg-c3ow">low</td>
    <td class="tg-c3ow">low</td>
    <td class="tg-c3ow">high</td>
    <td class="tg-c3ow">variable</td>
    <td class="tg-c3ow">medium</td>
    <td class="tg-c3ow">high</td>
    <td class="tg-c3ow">high</td>
    <td class="tg-c3ow">high</td>
    <td class="tg-c3ow">high</td>
    <td class="tg-c3ow">high</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Is timestamp based</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Sortable by creation date</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Can be easly used in a distributed ecosystem</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Support cursor-based pagination without adding a dedicated createdAt field</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Needs to be configured (eg. machine ID, shard id)</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes (machine ID)</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">BIT Distribution</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Time</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">41 bit (msec res.)</td>
    <td class="tg-c3ow">39 bit (10msec res)</td>
    <td class="tg-c3ow">8 chars <br>(64 bit UTF8 ecoded, 41 bit real entropy, 1msec resolution) </td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">32 bit</td>
    <td class="tg-c3ow">48 bit</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">60 bit</td>
    <td class="tg-c3ow"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Sequence/Counter</td>
    <td class="tg-c3ow">32 bit</td>
    <td class="tg-c3ow">64 bit</td>
    <td class="tg-c3ow">12 bit</td>
    <td class="tg-c3ow">8 bit</td>
    <td class="tg-c3ow">4 digits <br>(32 bit UTF8 encoded, 10-11bit of entropy)</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">24 bit <br>(starting random)</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">16 bit<br>(clok seq.)</td>
    <td class="tg-c3ow"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Machine Id + Process Id</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">10 bit</td>
    <td class="tg-c3ow">16 bit</td>
    <td class="tg-c3ow">4 chars <br>(32 bit UTF8 encoded, </td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">40 bit <br>(24 machine + 16 process)</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">48 bit <br>(MAC Address)</td>
    <td class="tg-c3ow"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Randomnes</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">8 chars<br>(64 bit UTF8 encoded)</td>
    <td class="tg-c3ow">variable</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">80 bit</td>
    <td class="tg-c3ow">122 bit</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Security</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Is completly Random?</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Predictability of the ID</td>
    <td class="tg-c3ow">High</td>
    <td class="tg-c3ow">High</td>
    <td class="tg-c3ow">Medium</td>
    <td class="tg-c3ow">Medium</td>
    <td class="tg-c3ow">Medium</td>
    <td class="tg-c3ow">Low</td>
    <td class="tg-c3ow">Medium-High</td>
    <td class="tg-c3ow">Low</td>
    <td class="tg-c3ow">Low</td>
    <td class="tg-c3ow">Medium-High</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Leaks the count of items</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Partially</td>
    <td class="tg-c3ow">Partially</td>
    <td class="tg-c3ow">Partially</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes?</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Leaks information about the machine/process</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Leaks the date of creation</td>
    <td class="tg-c3ow">Partially<br>(thorugh interpolation of <br>known dates it could be guessed)</td>
    <td class="tg-c3ow">Partially<br>(thorugh interpolation of <br>known dates it could be guessed)</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">No</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Suggested Hashing with HashIds</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-c3ow">Yes</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
</tbody>
</table>
