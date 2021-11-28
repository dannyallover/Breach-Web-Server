# Breach Web Server

See the [design](design.pdf) doc which maps out each exploit.

Overalls the attacks involve:
(1) **SQL injections** (which can be defended by **prepared statements**),
(2) **stored XSS attack** (which can be defended by **input sanitization**), and 
(3) **reflected XSS attack** (which can be defended by **content security policy**).
