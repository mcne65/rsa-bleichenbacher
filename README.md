# rsa-bleichenbacher

This is a python implementation of the Bleichenbacher Million Message Attack (CCA2) on RSA v1.5. The library chosen is Pycryptodome, but a similar strategy can work for all libraries with RSA v1.5. This attack can be prevented by using the most up-to-date RSA padding scheme, RSA-OAEP (Optimal Asymmetric Encryption Padding). The file attack.py contains the attack, rsa.py contains the RSA functions used, and main.py runs the attack. This attack prints out information at steps for demonstration purposes. The pdf contains a detailed description and analysis of the attack. We use a python library Intervals to do interval calculations in the attack (unions, min, max, etc of intervals). 