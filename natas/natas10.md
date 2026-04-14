Natas 10
===============

solution
---------------
UJdqkK1pTu6VLt9UHWAgRZz6sVUZ3lEk

exploit
---------------
They now sanitize the input for these symbols ; | &
But you can still grep the password file. So if you input `a /etc/natas_webpass/natas11`, you search the password file AND the dictionary
