### Summary

Please write a summary here of the changes made, and which business objective it supports.

### Context

Closes #
Version bump: #major/#minor/#patch (append this to the commit message)
Emergency change: Yes/No (review the Emergency Change Process)

### Additional validation

Steps to be taken apart from a code review.

### Checklist Submitter

Please review the following checklist before submitting your pull request to ensure compliance. All items have to be checked.

- [ ] My changes adhere to the coding standards and best practices established in the **Code Review Guidelines**.
- [ ] I have performed a self-review of my own code.
- [ ] I have commented my code, particularly in hard-to-understand areas.
- [ ] I have made corresponding changes to the documentation, if applicable.
- [ ] My changes generate no new warnings or errors.
- [ ] I have added tests that prove my changes are effective and increase code coverage.
- [ ] New and existing unit tests pass locally with my change, coverage is above 75%.
- [ ] If applicable, I have added new credentials or environment variables to KeyVault or other systems.
- [ ] I have notified relevant stakeholders of any potential service disruptions or changes in availability when this PR is merged.
- [ ] I understand that my changes may require updates to business continuity plans, if applicable.
- [ ] I have conducted a security impact assessment of my changes.
  > To conduct a security impact assessment, consider the following:
  > - Identify the data and systems affected by the changes.
  > - Evaluate the sensitivity and value of the data and systems.
  > - Identify potential threats and vulnerabilities introduced by the changes.
  > - Assess the likelihood and potential impact of these threats.
  > - Identify measures to mitigate the identified risks.
  > Add the review below:
  >
- [ ] I have considered the potential impact on performance of my changes.
  > To assess the potential impact on performance, consider the following:
  > - Identify the parts of the system that will be affected by your changes.
  > - Evaluate the current performance of these parts.
  > - Predict how your changes will affect the performance (e.g., will it increase the load, require more memory, etc.).
  > - If possible, perform a load test or similar to measure the impact.
  > - Consider the trade-offs between the benefits of your changes and the potential performance impact.
  > - If the impact is significant, consider ways to optimize your changes.
  > Add the review below:
  >
- [ ] I have reviewed the changes for compliance issues related to relevant frameworks (SOC2, HIPPA, PIPEDA, GDPR). If there's any doubt, I have consulted with QA about the change.
- [ ] I have informed appropriate parties in case of changed functionality which may require additional training or instructions.

### Testing

- [x] Unit tests have passed.
- [ ] Integration tests have passed.
- [ ] End to end test has passed.
- [ ] Vulnerability scanning has passed.

### Checklist Reviewer

Please review the following checklist before approving the pull request to ensure compliance. All items have to be checked.

- [ ] I have reviewed the code, and either no further changes were needed, or my feedback was discussed and/or implemented.
- [ ] All of the points in the submitters checklist are properly handled.