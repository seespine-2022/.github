---
name: Issue template
about: Fill out this issue template to start coding
title: ''
labels: ''
assignees: 'xemberi, Joyal_mh, philippemiller-seespine'

---

# Change Request and Assessment Form
**Document No.**:  
**Revision**: 

## Section A: Change Request Details (completed by Requestor)

### Change description
*A description of the changes. Describe before and after functionality.*

PLACE YOUR DESCRIPTION HERE.

### Reason for change
*Reasons can include product improvement, costs improvement or customer feedback.*

PLACE YOUR DESCRIPTION HERE.

### Impacted parts or docs
| Impacted Part # | Number | Description | Status (New, Revised, Obsoleted) |
|-----------------|--------|-------------|----------------------------------|
|                 |        |             |                                  |

### Departments involved
- [ ] Supply Chain Management
- [ ] Sales and Marketing
- [x] Software R&D
- [ ] Other: 

## Section B: Change Evaluation (completed by Requestor and QA/RA)

### Risk assessment
*Assess how this might impact risk* [Risk Matrix](https://drive.google.com/file/d/1FU75q1N5YYBL8HDRbQIrOO1lzGUQP8j9/view).

PLACE YOUR DESCRIPTION HERE.

### Product in the field impacted by the change?
- [x] Yes
- [ ] No

### Design control project determination
#### Question 1: Are you changing the product that falls under the QMS?
- [ ] Yes (-> Continue to 2)
- [ ] No (-> No additional information required)

#### Question 2: What type of change is this? Choose one
- [ ] Infrastructure / programming language (-> Schedule meeting with QA)
- [ ] Verification and validation (-> Schedule meeting with QA)
- [ ] Architecture (-> Schedule meeting with QA)
- [ ] Core algorithm (-> Schedule meeting with QA)
- [ ] Other (-> Continue to 3)

#### Question 3: What is the impact of these changes?
- [ ] Does this ticket change our [Risk Matrix](https://drive.google.com/file/d/1FU75q1N5YYBL8HDRbQIrOO1lzGUQP8j9/view)? (-> Schedule meeting with QA)
- [ ] Does this ticket change our intended use? Our intended use is... (-> Schedule meeting with QA)
- [ ] Is device performance or functionality significantly altered? (-> Schedule meeting with QA)

### Change questionnaire
*Check if any of the statements are true. If true, check the statement and add an explaination.*

<details>
  <summary>Labeling change</summary>

  - [ ] A1.1 – Is it a change from a device labeled for “single use only” to a device labeled as “reusable”?
  - [ ] A1.2 – Is it a change from prescription (Rx) to an over-the-counter use (OTC)?
  - [ ] A1.3 – Is it a change to the device name, or to solely improve readability or clarity?
  - [ ] A1.4 – Does the change describe a new disease, condition, or patient population that the device is intended in diagnosing, treating, preventing, curing or mitigating?
  - [ ] A1.5 – Does a risk-based assessment identify any new risks or significantly modified existing risks?
  - [ ] A2 – Does the change add or delete a contraindication?
  - [ ] A3 – Is it a change to cautions, warnings or precautions?
  - [ ] A4 – Could the change affect the directions for use?
  - [ ] A5 – The legal manufacturer’s name and address on the device labeling stays the same but a new manufacturing facility is added, or production facilities are moved?
  - [ ] A6 – Change in manufacturer’s name/address, or EU representative or product name, variants or accessories
  - [ ] A7 – Is the labeling revised based on post-market surveillance?


</details>
<details>
  <summary>Design change (technology, engineering, performance changes)</summary>

  - [ ] B1 – Does the change affect indications, contraindication or warnings or precautions?
  - [ ] B2 – Is it any other change in design such as: performance specifications, wireless communications, components or accessories, patient/user interface/environmental specifications?
  - [ ] B2.1 – Does the change significantly affect the use of the device?
  - [ ] B2.2 – Does a risk assessment identify any new or significantly modified risks?
  - [ ] B2.3 – Is clinical data necessary?
  - [ ] B2.4 – Were any unexpected issues encountered with Verification and/or Validation activities that could affect safety & effectiveness of the device?

</details>
<details>
  <summary>Quality system, administrative or manufacturing change</summary>

  - [ ] D1 – Post Market Surveillance produces a need for a change. Consider product recalls, field actions, CAPAs, critical supplier issues, etc.
  - [ ] D2 – Change in product portfolio, adding a product line, changing a product to cover additional indications?r accessories, patient/user interface/environmental specifications?
  - [ ] D3 – Changing a critical supplier or their location?
  - [ ] D4 – Change in compliance to standards/directives?
  - [ ] D5 – Does risk assessment identify any new or significantly modified risks?
  - [ ] D6 – Change to process validation?
  - [ ] D7 - New quality certificates issued?
  - [ ] D8 - Changed/new quality management representative?
  - [ ] D9 - Is there a significant change in the QMS structure or organizational structure?

</details>
<details>
  <summary>Software change</summary>

  - [ ] E1 – Does the change in software modify an algorithm or does it impact the way the data is read and interpreted such that it impacts/alters the diagnosis or therapy delivered?
  - [ ] E2 – Is the change made solely to strengthen cybersecurity and does not have any other impact on the software or device?
  - [ ] E3 – Is the change made solely to return the system into specification of the most recently cleared device?
  - [ ] E4 – What are the impacts of any changes to risks associated with use of the device and the impacts of any changes to the risk controls for the device?
  - [ ] E4.1 – Does the change introduce a new risk or modify an existing risk that could result in significant harm and that is not effectively mitigated in the most recently cleared device?
  - [ ] E4.2 – Does the change create or necessitate a new risk control measure or a modification of an existing risk control measure for a hazardous situation that could result in significant harm?
  - [ ] E5 – Could the change significantly affect clinical functionality or performance specifications or control of the device that are directly associated with the diagnosis or intended use of the device?
  - [ ] E6 – Does the change in software introduce or remove an alarm function, and a response to the new alarm may change the treatment of the patient in comparison to the previous version of the software?
  - [ ] E7 – Does the change in software correct an error for which there is a safety risk to the patient if the error is not fixed?
  - [ ] E8 – Does the change only introduce non-therapeutic and nondiagnostic features (e.g. printing, faxing, reporting format) or disables a feature that does not interact with other features?
  - [ ] E9 – Does the change in software only modify the user interface in appearance with negligible risk of impacting diagnosis or therapy delivered?
  - [ ] E10 – Is it a change to the infrastructure of the software?
  - [ ] E11 – Is it a change to the architecture of the software, including change to a new OS, new hardware platform and new middleware?
  - [ ] E12 – Is it a change to a ‘Core algorithm’ such that it can directly impact or contribute to the device’s intended use?
  - [ ] E13 – Are there any ‘re-engineering’ or ‘refactoring’ changes?

</details>

## Section C: Regulatory Assessment (completed by Regulatory Affairs)

## Section D: Change Control Board Review

- ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) `#f03c15`


### Approval
- [ ] Signed off by QA
- [ ] Signed off by management