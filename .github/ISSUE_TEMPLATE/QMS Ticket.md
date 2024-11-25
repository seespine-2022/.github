---
name: QMS Ticket
about: For changes that affect the API/mobile app and the user.
title: ''
labels: ''
assignees: 'xemberi, rama-momentum'

---

# QMS Ticket 
Fill out > management approval > schedule QA/RA meeting (QMS change request).

## Change classification 
- [ ] Minor change (negligible functionality or enhancement of usability or performance.)
- [ ] Major change (significant impact on safety, effectiveness, or regulatory status.)


## QMS Scope 
*Provide a more detailed and technical overview of the scope of the proposal. What will and what will not be part of this task? What does it look like in case of UX/UI change?* 


## QMS Source
*If there are QMS sources or related documents, link the documents below:*

- Source: 
- Other related documents:


## Mobile app/API impact assessment  
 - *Impacts of change on constituent parts (relating to components, dependencies, or different parts of the system). In simpler terms, it's about understanding if changing one thing might break or alter something else.*
		        
        
 - *Impacts of change on product in process or already delivered (relating to the affect on versions of the product that are currently being developed or are already in use by customers). It's important to think about whether the change will require updates to existing versions.*
       
        
 - *Impacts of change on inputs or outputs of risk management (relating to introduction of new risks or alteration of existing risk assessments). It's about ensuring that any potential problems are identified and addressed.*
       
        
 - *Impacts of change on overall design and development process (relating to infrastructure, programming language, verification/validation, architecture, performance/functionality, or core algorithm). It involves thinking about whether the change requires modifications to the underlying structure, coding practices, testing methods, or core functionalities of the product.*
		 
       
 
## Design Traceability Matrix (DTM) Impact 
Check [Design Traceability Matrix](https://github.com/seespine-2022/qms-docs/tree/main/design/design-matrix):
Is there a clear thread of traceability for all of the following?
    • Associated with existing design input
    • Design input is complete, unambiguous, verifiable, and not conflicting
    • Associated with relevant design output
    • Design output has product acceptance criteria
    • Design verification activities confirm outputs meet inputs
    • Design validation activities confirm product meets user needs/intended uses

- [ ] Yes, no updates to DTM required → Continue to "Risk impact"
- [ ] No, DTM requires update [provide details on how it should be updated] → 
- [ ] N/A, explain → 

## Risk impact 
Check [Risk Controls](https://github.com/seespine-2022/qms-docs/tree/main/risk):
- Is the answer to all of the following a clear yes? 
    • Existing FMEAs adequately address potential risks
    • Change does not introduce new risks
    • Risk control measures are sufficient
    • No unaddressed risks are present

- [ ] Yes, no updates to FMEA required → Continue to QA Approval
- [ ] No, FMEAs require updates [provide details on how it should be updated] → 
- [ ] N/A, explain → 

## Approvals 
 - [ ] **Lead Developer:** [Name], [Date Change Request Proposal Initiated]
 - [ ] **Management Approval:** [Name], [Date Change Request Proposal Approved]
 - [ ] **RA/QA Approval**: [Name], [Date Issue Approved]
