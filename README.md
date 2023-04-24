# CS-305
SNHU Project Submissions

Artemis Financial is a consulting company offering financial plans to their customers including savings, retirment, investment, and insurance plans. The requirements were to implement a hash function for secure communications as well as addressing security vulnerabilites currently present and implementing industry best practices for software security.

I think the SHA 256 hash algorithm was well implemented only requiring the standardcharset and required messagedigest packages. The code implemented did not add to the current security vulnerabilities present, which demonstrates successful secure coding practices. Secure coding is intrinsically valuable to a company. Without secure coding during each stage of the software development lifecycle costs accumulate as a vulnerability is more costly the longer it goes unaddressed due to the system becoming more complex or worse has real world impact on company trust, liabilities or customers.

The most challenging part of the vulnerability assessment was identifying potential false positives. Had we not used the maven depency check, identyfing false positives would have required more familiarity with the innitial code base. The most helpful feature of the tool was being able to research the dependencies and known vulnerabilities.

Adding error handling and cryptography were the most impactful increases to security. Assessing vulnerabilities requires understanding what is being implemented to meet software requirements and how to address potential security flaws inherited. For instance, if input from a user is needed then input validation design patterns must be used to prevent injections, etc. Standard industry mitigation techniques should be used to prevent additional security risks. As an example, the use of SHA 1 is depricated for it's known issues.

The maven depency check was used before and after the code was refactored to assess if new vulnerabilites were introduced. Functional testing was also used to ensure the code behaved as expected and met requirements. 

The maven depency checklist was crucial during the course and I will use it again or similar tools depending on the project. For coding practices, using proper design patterns is crucial.I will also be using various forms of testing to ensure remote code execution or other malicious acts can not be performed with a system.

The hash function implementation is something I would consider using in future projects and willing to show employers along with other secure coding practices learned during this course that were not implemented as part of this assignment. Discovering the WhiteLabel Error Page existed is something of note as well, although outside the scope of assignment to address.
