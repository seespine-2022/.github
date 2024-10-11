---
name: Issue template
about: Fill out this issue template to start coding
title: ''
labels: ''
assignees: 'xemberi, rama-momentum, philippemiller-seespine'

---

*Name*: REPLACE THIS VALUE

# 1. Change Request Proposal

## 1.1. Proposal
Give a brief overview of the proposed change.

## 1.2. Source
Describe the source of this proposal. Was it an idea? Based on a complaint? Did we find a bug? Did someone give us feedback?

## 1.3. Management approval
If management has given approval to move forward with this proposal, confirm that here. Approval should be in the issue comment. Also confirm who is the lead developer on the change.
- [ ] Lead Developer: [Name], [Date Change Request Proposal Initiated]
- [ ] Management Approval: [Name], [Date Change Request Proposal Approved]

Does this change impact the API/mobile app or will it in the future? If you are not sure if it will in the future, it is a no.

<details>
<summary>2. Change Request Plan</summary>

# 2. Change Request Plan

## 2.1. Scope
- Provide a more detailed and technical overview of the scope of the proposal. What will and what will not be part of this task? What does it look like in case of UX/UI change?
- Clarify how the change will impact the mobile app and/or API, adress the following points:
    -	Impacts of change on constituent parts (relating to components, or dependencies). This refers to how the proposed change might affect different parts of the system or its dependencies. In simpler terms, it's about understanding if changing one thing might break or alter something else.

    -	Impacts of change on product in process or already delivered (relating to mobile app releases in process, or mobile app release already on the app stores). This is about considering how the change might affect versions of the product that are currently being developed or are already in use by customers. It's important to think about whether the change will require updates to existing versions.

    -	Impacts of change on inputs or outputs of risk management (relating to any FMEA's). This point is asking to consider how the change might introduce new risks or alter existing risk assessments. It's about ensuring that any potential problems are identified and addressed.

    -	Impacts of change on product realization/design plan (relating to infrastructure, programming language, verification/validation, architecture, performance/functionality, or core algorithm). This is about evaluating how the change might affect the overall design and development process. It involves thinking about whether the change requires modifications to the underlying structure, coding practices, testing methods, or core functionalities of the product.

## 2.2. Source QMS
Is the source (in 1.2) recorded in the QMS? If so, link the documents:
- Source:
- Other related documents:

## 2.3. Task breakdown and timeline
Break up the change in tasks and provide an estimated timeline for completion of the tasks, include testing.
 - [ ] Task 1, estimated time needed for completion:
 - [ ] Task 2, estimated time needed for completion:
 - [ ] Testing, estimated time needed for completion:

## 2.4. Design Traceability Matrix (DTM) Impact
Check [Design Traceability Matrix](https://github.com/seespine-2022/qms-docs/tree/main/design/design-matrix):
- Is there a clear thread of traceability for all of the following?
    • Associated with existing design input
    • Design input is complete, unambiguous, verifiable, and not conflicting
    • Associated with relevant design output
    • Design output has product acceptance criteria
    • Design verification activities confirm outputs meet inputs
    • Design validation activities confirm product meets user needs/intended uses

- [ ] Yes → Continue to 2.5
- [ ] No → DTM requires update [provide details on how it should be updated]

## 2.5. Risk impact
Check [Risk Controls](https://github.com/seespine-2022/qms-docs/tree/main/risk):
- Is the answer to all of the following a clear yes? 
    • Existing FMEAs adequately address potential risks
    • Change does not introduce new risks
    • Risk control measures are sufficient
    • No unaddressed risks are present

- [ ] Yes → Continue to 2.6
- [ ] No → FMEAs require updates [provide details on how it should be updated]

## 2.6. Acceptance criteria & test
When defining acceptance criteria, you should clearly articulate specific, measurable conditions that the software must meet to satisfy the user need. To create acceptance tests, developers should then translate these criteria into executable test cases that verify each condition, ensuring the tests cover both the expected functionality and potential edge cases.

For example: 
*User Need:* "I want to quickly find and purchase items." 
*Acceptance Criterion:* "Users can complete a purchase in 3 clicks or less from the product page." 
*Direct Purchase Test:* 1. Start on a product page 2. Click "Add to Cart" 3. Click "Proceed to Checkout" 4. Click "Confirm Purchase" 
*Expected Result:* Purchase should be completed in exactly 3 clicks

## 2.7. QA approval
If RA/QA has given approval to move forward with this change, confirm that here. Approval should be visible in the comment section.
 - [ ] RA/QA Approval: [Name], [Date Change Request Plan Approved]

</details>
