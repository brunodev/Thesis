# LSASS internals
 
## Memory key
All passwords in LSASS memory is encrypted with the memory key (i have no idea if this is what it's actually called).
 
Find the first instance of KSSM. Go forward 20 bytes and the key starts here



## Resources
* Reverse engineering of lsass (pre encryption) https://web.archive.org/web/20110625150122/http://research.truesec.com/?p=22
* Mimikatz sekurlsa_nt5 - How to get memory key (Windows NT 5) https://github.com/gentilkiwi/mimikatz/blob/bb371c2acba397b4006a6cddc0f9ce2b5958017b/mimikatz/modules/sekurlsa/crypto/kuhl_m_sekurlsa_nt5.c
* System.Security.Cryptography.BCryptNative - Native bcrypt functions in c# https://referencesource.microsoft.com/#system.core/System/Security/Cryptography/BCryptNative.cs