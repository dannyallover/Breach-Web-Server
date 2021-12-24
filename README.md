# Breach Web Server

Capture the flag exercise for breaching a web server. See the [design](design.pdf) doc which maps out each exploit.

Overalls the attacks involve:
<br>
(1) **SQL injection** (which can be defended by **prepared statements**),
<br>
(2) **stored XSS attack** (which can be defended by **input sanitization**), and 
<br>
(3) **reflected XSS attack** (which can be defended by **content security policy**).

note: this is the 3rd project of [CS 161](https://fa20.cs161.org/) at UC Berkeley.
