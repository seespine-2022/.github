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
*Give a brief overview of the proposed change.*

## 1.2. Source
*Describe the source of this proposal. Was it an idea? Based on a complaint? Did we find a bug? Did someone give us feedback?*

## 1.3. Management approval
*If Philippe (CEO) or Frank (CTO) has given approval to move forward with this proposal, confirm that here. Approval should be in the issue comment. Also confirm who is the lead developer on the change.*

# 2. Change Request Plan

## 2.1. Scope
*Provide a more detailed and technical overview of the scope of the proposal. What will and what will not be part of this task? What does it look like in case of UX/UI change?*

## 2.2. Task breakdown and timeline
*Break up the change in tasks and provide an estimated timeline for completion of the tasks, include testing.*

- [ ] Task 1
- [ ] Task 2
- [ ] Testing

## 2.3. QMS governance
*Does this change impact our product and/or users?*
- [ ] Yes

## 2.4. Design impact
*Does this change impact the [Design Traceability Matrix](https://github.com/seespine-2022/qms-docs/tree/main/design/design-matrix) or [Risk Controls](https://github.com/seespine-2022/qms-docs/tree/main/risk)?
- [ ] Yes

## 2.5. Design traceability
*Do we currently have a traceability thread? Describe how the user needs, software requirements, design inputs will change.*

*Please list the following:*
- Affected User Needs:
- Affected Software Requirements:
- Affected Design Inputs:

## 2.6. Acceptance criteria & test
*When defining acceptance criteria, you should clearly articulate specific, measurable conditions that the software must meet to satisfy the user need. To create acceptance tests, developers should then translate these criteria into executable test cases that verify each condition, ensuring the tests cover both the expected functionality and potential edge cases.

For example:

**User Need:** "I want to quickly find and purchase items."
**Acceptance Criterion:** "Users can complete a purchase in 3 clicks or less from the product page."
**Direct Purchase Test:**
1. Start on a product page
2. Click "Add to Cart"
3. Click "Proceed to Checkout"
4. Click "Confirm Purchase"
**Expected Result:** Purchase should be completed in exactly 3 clicks

## 2.7. QA approval
*If Rama (QA) has given approval to move forward with this change, confirm that here. Approval should be visible in the comment section.*