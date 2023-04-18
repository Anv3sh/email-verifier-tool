# A simple Email verifier tool
A simple email verifier tool in golang checks domain, hasMX, hasSPF, sprRecord, hasDMARC and dmarcRecord.
## What is mail exchange record?
- [What is an MX Record, and How Do They Work? (practical365.com)](https://practical365.com/mx-record/)
- MX stands for mail exchange
- An MX record is a type of DNS record, so any understanding of MX records has to begin with an understanding of the fundamentals of the Domain Name System (DNS).

## What is SPF(Sender Policy Framework)?
- Sender Policy Framework (SPF) is an email-authentication standard used to prevent spammers from sending messages that appear to come from a spoofed domain. It also helps to ensure that emails are delivered correctly – without being delivered to a recipient's spam box.
- [What is SPF? | A Guide to Sender Policy Framework (proprivacy.com)](https://proprivacy.com/email/guides/what-is-spf)

## What is DMARC?
-  DMARC stands for **Domain-based Message Authentication Reporting & Conformance**.
- it is a email security protocol.
- DMARC verifies email senders by building on the [Domain Name System (DNS)](https://www.fortinet.com/resources/cyberglossary/what-is-dns), DomainKeys Identified Mail (DKIM), and Sender Policy Framework (SPF) protocols.
- [What Is DMARC? How Does DMARC Work? | Fortinet](https://www.fortinet.com/resources/cyberglossary/dmarc)

## What are TXT records?
- TXT records are **multi-purpose records**.
- TXT records are commonly used to store contact details and general information about a domain.