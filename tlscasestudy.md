1. History of SSL/TLS
    A. Non-technical overview of SSL’s uses and structure
    B. Distinction between SSL and X.509
    C. History of X.509
        i. OSI standardization initiative at ISO (1977)
            a. Goals
            b. Long-term effects
        ii. X.500 suite
            a. Role of X.509
            b. LDAP
        iii. Evolution of X.509
            a. Advent of TCP/IP
            b. Role of certificate authorities
            c. Updated standards
    D. History of SSL
        i. Secure Network Programming (SNP) API
        ii. Netscape
            a. SSL v1.0 (never released)
            b. SSL v2.0 (1995)
                1. Major flaws
            c. SSL v3.0 (1996)
        iii. TLS
            a. TLS 1.0 (1999)
                1. Differences from SSL
            b. TLS 1.1 (2006)
                1. Protection against CBC attacks.
                2. Explicit IV.
                3. IANA support.
            c. TLS 1.2 (2008)
                1. Replace MD5-SHA1 with SHA256 by default.
                2. Extend ciphers available.
                3. Enhance ability of clients and servers to specify acceptable ciphers.
    E. History of adoption
        i. First websites to use:
            a. Banking
            b Online commerce (solely for checkout pages)
            c. Government services?
                1. TO RESEARCH: What was the first gov’t service to TLS?
    F. SSL today
        i. Major implementations
            a. NSS
            b. OpenSSL
            c. Proprietary
            d. Embedded
            e. Others
        ii. Major security issues
            a. CA breaches
            b. Heartbleed
            c. …
        iii. Newer developments
            a. PFS
            b. OCSP stapling
            c. HSTS
            d. Letsencrypt (disruptive changes to X.509 CA business model)
            e. TLS v1.3 status
