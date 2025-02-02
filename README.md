# disclosures

## CVEs

- ["Get Super Serial" CVE-2015-2231 & CVE-2015-2232](https://github.com/rednaga/disclosures/blob/master/GetSuperSerial.md)
  
  Chain from an application with internet permissions to a system uid, then from a system uid to root. This is mainly due
  to an extremely weak firmware upgrade system calls "ADUPS" which has failed to have any type of response. While the two
  specific CVEs directly correlate to a few Blu phones, it appears to be used by many other lower-end phones.


- ["HTC Peap" CVE-2015-5525, CVE-2015-5526 & CVE-2015-5527](https://github.com/rednaga/disclosures/blob/master/HTCPeap.md)
  
  Multiple ways to access a backdoor which allows an unprivledged application the ability to run root commands. Discussed
  at the DEFCON23 Red Naga workshop on Offensive and Defensive Android Reverse Engineering.

- ["Qualcomm System Agent", No CVEs assigned](https://github.com/rednaga/disclosures/blob/master/QCOMSysAgent.md)

  Multiple vulnerabilities in an application that was never meant to be shipped on production devices. Discussed
  at the DEFCON23 Red Naga workshop on Offensive and Defensive Android Reverse Engineering.
  
- ["RESERVED", CVE-2015-6841](N/A)
  
  Vulnerability spot just reserved, currently only "triaged" by vendor. Fix not yet rolled out.
