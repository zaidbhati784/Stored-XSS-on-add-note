# Stored-XSS-on-add-note

Stored XSS on add note					
Summary:-					
Stored XSS can be submitted on reports, and anyone who will check the report the XSS will trigger.					
					
Description					
Stored XSS, also known as persistent XSS, is the more damaging than non-persistent XSS. It occurs when a malicious script is injected directly into a vulnerable web application.					
					
Steps to Reproduce					
1.  Go to https://web.sociorac.com/content/allNotes					
2.  Click on ADD button to add a note					
3.  On Note title,enter payload   ssssdddd"><img src=x onerror=alert(1);>					
4. Click Save then XSS will trigger					
					
Demonstration of Vulnerability					
POC:  https://clipchamp.com/watch/b9WEVQTNdOg					
					
Impact:					
The attacker can steal data from whoever checks the notes.					
