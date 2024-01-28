1. Which of the following MUST be addressed by software security requirements? Choose the BEST answer.

A. Technology used in building the application.

B. Goals and objectives of the organization.

C. Software quality requirements.

D. External auditor requirements.



2. Which of the following types of information is exempt from confidentiality requirements?

A. Directory information.

B. Personally identifiable information (PII).

C. User’s card holder data.

D. Software architecture and network diagram.



3. Requirements that are identified to protect against the destruction of information or the software itself are commonly referred to as

A. confidentiality requirements.

B. integrity requirements.

C. availability requirements.

D. authentication requirements.

Destruction is the threat against availability as disclosure is the threat against confidentiality and alteration being the threat against integrity.



4. The amount of time by which business operations need to be restored to service levels as expected by the business when there is a security breach or disaster is known as

A. Maximum Tolerable Downtime (MTD).

B. Mean Time Before Failure (MTBF).

C. Minimum Security Baseline (MSB).

D. Recovery Time Objective (RTO).

Maximum Tolerable Downtime (MTD) is the maximum length of time a business process can be interrupted or unavailable without causing the business itself to fail. Recovery Time Objective (RTO) is the time period in which the organization should have the interrupted process running again, at or near the same capacity and conditions as before the disaster/downtime. MTD and RTO are part of availability requirements. It is advisable to set the RTO to be lesser than the MTD.



5. The use of an individual’s physical characteristics such as retinal blood patterns and fingerprints for validating and verifying the user’s identity if referred to as

A. biometric authentication.

B. forms authentication.

C. digest authentication.

D. integrated authentication.



6. Which of the following policies is MOST likely to include the following requirement? “All software processing financial transactions need to use more than one factor to verify the identity of the entity requesting access””

A. Authorization. 

B. Authentication. 

C. Auditing.

D. Availability.



7. A means of restricting access to objects based on the identity of subjects and/or groups to which they belong, as mandated by the requested resource owner is the definition of

A. Non-discretionary Access Control (NDAC).

B. Discretionary Access Control (DAC).

C. Mandatory Access Control (MAC).

D. Role based Access Control.



8. Requirements which when implemented can help to build a history of events that occurred in the software are known as

A. authentication requirements.

B. archiving requirements.

C. accountability requirements.

D. authorization requirements.



9. Which of the following is the PRIMARY reason for an application to be susceptible to a Man-in-the-Middle (MITM) attack?

A. Improper session management

B. Lack of auditing

C. Improper archiving

D. Lack of encryption

Easily guessable and non-random session identifiers can be hijacked and replayed if not managed appropriately and this can lead to MITM attacks.



10. The process of eliciting concrete software security requirements from high level regulatory and organizational directives and mandates in the requirements phase of the SDLC is also known as

A. threat modeling.

B. policy decomposition.

C. subject-object modeling.

D. misuse case generation.



11. The FIRST step in the Protection Needs Elicitation (PNE) process is to

A. engage the customer

B. model information management

C. identify least privilege applications

D. conduct threat modeling and analysis



12. A Requirements Traceability Matrix (RTM) that includes security requirements can be used for all of the following except

A. ensuring scope creep does not occur

B. validating and communicating user requirements

C. determining resource allocations

D. identifying privileged code sections



13. Parity bit checking mechanisms can be used for all of the following except

A. Error detection.

B. Message corruption.

C. Integrity assurance.

D. Input validation.



14. Which of the following is an activity that can be performed to clarify requirements with the business users using diagrams that model the expected behavior of the software?

A. Threat modeling

B. Use case modeling

C. Misuse case modeling

D. Data modeling



15. Which of the following is LEAST LIKELY to be identified by misuse case modeling?

A. Race conditions

B. Mis-actors

C. Attacker’s perspective

D. Negative requirements

Misuse cases, also known as abuse cases help identify security requirements by modeling negative scenarios. A negative scenario is an unintended behavior of the system, one that the system owner does not want to occur within the context of the use case. Misuse cases provide insight into the threats that can occur against the system or software. It provides the hostile users point of view and is an inverse of the use case. Misuse case modeling is similar to the use case modeling, except that in misuse case modeling, mis-actors and unintended scenarios or behavior are modeled. Misuse cases may be intentional or accidental. One of the most distinctive traits of misuse cases is that they can be used to elicit security requirements unlike other requirements determination methods that focus on end-user functional requirements.



16. Data classification is a core activity that is conducted as part of which of the following?

A. Key Management Lifecycle

B. Information Lifecycle Management

C. Configuration Management

D. Problem Management



17. Web farm data corruption issues and card holder data encryption requirements need to be captured as part of which of the following requirements?

A. Integrity.

B. Environment. 

C. International. 

D. Procurement.

When determining requirements it is important to elicit requirements that are tied to the environment in which the data will be marshaled or processed. Viewstate corruption issues in web farm settings where all the servers were not configured identically or lack of card holder data encryption in public networks have been observed when the environmental requirements were not identified or taken into account.



18. When software is purchased from a third party instead of being built in-house, it is imperative to have contractual protection in place and have the software requirements explicitly specified in which of the following?

A. Service Level Agreements (SLA).

B. Non-Disclosure Agreements (NDA).

C. Non-compete Agreements

D. Project plan.

SLAs should contain the levels of service expected for the software to provide and this becomes crucial when the software is not developed in-house.



19. When software is able to withstand attacks from a threat agent and not violate the security policy it is said to be exhibiting which of the following attributes of software assurance?

A. Reliability.

B. Resiliency.

C. Recoverability. 

D. Redundancy.



20. Infinite loops and improper memory calls are often known to cause threats to which of the following?

A. Availability.

B. Authentication. 

C. Authorization. 

D. Accountability.



21. Which of the following is used to communicate and enforce availability requirements of the business or client?

A. Non-Disclosure Agreement (NDA).

B. Corporate Contract.

C. Service Level Agreements (SLA).

D. Threat model.



22. Software security requirements that are identified to protect against disclosure of data to unauthorized users is otherwise known as

A. integrity requirements.

B. authorization requirements.

C. confidentiality requirements.

D. non-repudiation requirements.



23. The requirements that assure reliability and prevent alterations are to be identified in which section of the software requirements specifications (SRS) documentation?

A. Confidentiality. 

B. Integrity.

C. Availability.

D. Accountability.



24. Which of the following is a covert mechanism that assures confidentiality?

A. Encryption.

B. Steganography. 

C. Hashing.

D. Masking.



25. As a means to assure confidentiality of copyright information, the security analyst identifies the requirement to embed information insider another digital audio, video or image signal. This is commonly referred to as

A. Encryption.

B. Hashing.

C. Licensing.

D. Watermarking.

Digital watermarking is the process of embedding information into a digital signal. These signals can be audio, video, or pictures.



26. Checksum validation can be used to satisfy which of the following requirements?

A. Confidentiality. 

B. Integrity.

C. Availability.

D. Authentication.



27. A Requirements Traceability Matrix (RTM) that includes security requirements can be used for all of the following EXCEPT

A. Ensure scope creep does not occur

B. Validate and communicate user requirements

C. Determine resource allocations

D. Identifying privileged code sections
