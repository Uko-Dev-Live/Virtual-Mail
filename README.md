# Virtual-Mail
Setting up and Running Virtual Mail Server.

Virtual Mail System Components

A. Postfix (Mail/SMTP Server, MTA)
   (i). STARTTLS -- for encryption
   (ii). SMTP AUTH (SASL) -- for authentication

B. Dovecot (IMAP/POP3 Server, MDA)
   (i). (SSL/TLS) -- for encryption

C. MySql
   (i). Domains and virtual users storage

D. Spam Filter (Rspamd/SpamAssassin)

E. Pflogsumm -- for Postfix log monitoring
