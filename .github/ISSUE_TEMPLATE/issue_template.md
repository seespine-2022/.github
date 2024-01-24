---
name: Issue template
about: Fill out this issue template to start coding
title: ''
labels: ''
assignees: ''

---
## 0. Are you changing the product that falls under the QMS?
- [ ] Yes (-> Continue to 1)
- [ ] No (-> Remove all, but 3, and continue to 3.)

## 1. What type of change is this? Choose one.
- [ ] Infrastructure / programming language (-> Schedule meeting with QA)
- [ ] Verification and validation (-> Schedule meeting with QA)
- [ ] Architecture (-> Schedule meeting with QA)
- [ ] Core algorithm (-> Schedule meeting with QA)
- [ ] Other (-> Continue to 2)

## 2. Impact of changes
- [ ] Does this ticket change our [Risk Matrix](https://drive.google.com/file/d/1FU75q1N5YYBL8HDRbQIrOO1lzGUQP8j9/view)? (-> Schedule meeting with QA)
- [ ] Does this ticket change our intended use? Our intended use is... (-> Schedule meeting with QA)
- [ ] Is device performance or functionality significantly altered? (-> Schedule meeting with QA)

-> Continue to 3

## 3. Change description
*A description of the changes. Describe before and after functionality.*

PLACE YOUR DESCRIPTION HERE.

-> Continue to 4

## 4. Reason for change
*Reasons can include product improvement, costs improvement or customer feedback.*

PLACE YOUR DESCRIPTION HERE.

-> Continue to 5

## 5. Risk assessment
*Assess how this might impact risk* LINK TO risk management file.

PLACE YOUR DESCRIPTION HERE.

-> Continue to 6

## 6. Change questionnaire
*Check if any of the statements are true. If true, check the statement and add an explaination.*

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

-> End.