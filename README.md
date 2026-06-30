# Assignment_8_CS305

**Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**

Artemis Financial is a financial consultant looking to update their processes and apply best industry standards to protect their customers. Specifically, they are looking for a data verification step to their file transfer process.

**What did you do well when you found your client’s software security vulnerabilities? **

I was able to apply HTTPS to their process and deliver a better method for file transfer using standard practices.

**Why is it important to code securely? What value does software security add to a company’s overall well-being?**

Secure coding ensures that customers' data is safe. Neglectful coding can result in loss of financial information and trust.

**Which part of the vulnerability assessment was challenging or helpful to you?**

The vulnerability assessment was tricky at times, and I found that I had copy/pasted the wrong version of OWASP into my file.  After figuring this out, it became more straightforward.

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

First step in the increase was encryption through HTTPS implementation and certificate generation. Then we did a file transfer security in the form of SHA-256.  We wrapped it up with a dependency check to ensure vulnerabilities were not introduced.

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

The code was executed and the browser was checked to ensure that we were utilizing HTTPS. We then did a dependency check to ensure that no new vulnerabilities were found.

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**

The videos provided were fantastic and assisted in not only understanding what assignments were attempting to do, but also how it applied to the real world.

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**

I would show employers how we were able to employ a hash function.  This is because my current employer is currently working on adding this feature to ensure data integrity for future updates.
