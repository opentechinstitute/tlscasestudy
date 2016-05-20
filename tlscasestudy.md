1. History of SSL/TLS
    1. Non-technical overview of SSL’s uses and structure
    1. Distinction between SSL and X.509
    1. History of X.509
        1. OSI standardization initiative at ISO (1977)
            1. Goals
            1. Long-term effects
        1. X.500 suite
            1. Role of X.509
            1. LDAP
        1. Evolution of X.509
            1. Advent of TCP/IP
            1. Role of certificate authorities
            1. Updated standards
    1. History of SSL
        1. Secure Network Programming (SNP) API
        1. Netscape
            1. SSL v1.0 (never released)
            1. SSL v2.0 (1995)
                1. Major flaws
            1. SSL v3.0 (1996)
        1. TLS
            1. TLS 1.0 (1999)
                1. Differences from SSL
            1. TLS 1.1 (2006)
                1. Protection against CBC attacks.
                2. Explicit IV.
                3. IANA support.
            1. TLS 1.2 (2008)
                1. Replace MD5-SHA1 with SHA256 by default.
                2. Extend ciphers available.
                3. Enhance ability of clients and servers to specify acceptable ciphers.
    1. History of adoption
        1. First websites to use:
            1. Banking
            1. Online commerce (solely for checkout pages)
            1. Government services?
                1. TO RESEARCH: What was the first gov’t service to TLS?
    1. SSL today
        1. Major implementations
            1. NSS
            1. OpenSSL
            1. Proprietary
            1. Embedded
            1. Others
        1. Major security issues
            1. CA breaches
            1. Heartbleed
            1. …
        1. Newer developments
            1. PFS
            1. OCSP stapling
            1. HSTS
            1. Letsencrypt (disruptive changes to X.509 CA business model)
            1. TLS v1.3 status
