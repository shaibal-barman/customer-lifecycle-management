# 4. Voice of Customer to Action

Feedback is valuable only when another person can understand the situation, verify the evidence, and make a decision from it.

“The customer does not like this” is not actionable. It does not show who is affected, what they were trying to do, how often the issue occurs, or what the business consequence is.

## The feedback record

Capture:

- the customer's original wording;
- the role and workflow involved;
- when the issue appears;
- frequency or pattern;
- business or operational consequence;
- current workaround;
- available evidence;
- affected customer segment, if known;
- recommended internal owner; and
- what “resolved” would mean to the customer.

Use the [Customer Feedback Record](../templates/customer-feedback-record.md) to keep these fields consistent.

## Classify before assigning

| Classification | Evidence to look for | Likely response |
| --- | --- | --- |
| Product behavior | Reproducible gap, limitation, or unexpected result | Product and Engineering investigation |
| Service execution | Missed handoff, timing, ownership, or quality gap | Operational correction and follow-up |
| Enablement | Workflow exists but the user cannot apply it reliably | Role-based training or guidance |
| Configuration | The product can support the need but current setup does not | Configuration review and validation |
| Process design | Internal or customer workflow creates the failure | Joint workflow redesign |

Classification can change as evidence improves. The purpose is to find the next responsible action, not to defend the first assumption.

## The closed loop

1. **Clarify:** Restate the issue and consequence in plain language.
2. **Verify:** Reproduce the problem or validate the pattern from available evidence.
3. **Classify:** Decide whether the main gap is product, service, enablement, configuration, or process.
4. **Assign:** Name one owner for the next decision.
5. **Respond:** Tell the customer what is known, what is being checked, and when the next update will occur.
6. **Validate:** Confirm that the change improved the customer workflow.
7. **Share the learning:** Update training, documentation, process, or product context so the same issue is handled better next time.

## Example: one complaint, four possible causes

A customer reports that important alerts are unreliable. That statement may point to different problems:

- the signal itself is inaccurate;
- the alert arrives too late for the customer's workflow;
- the configuration does not match the use case; or
- the team does not know how to handle the exception.

Sending the statement directly to Engineering would be premature. The useful work is separating these possibilities, collecting evidence, and assigning the correct next decision.

## Definition of done

Feedback is closed only when:

- the customer has received a clear response;
- the assigned action is complete;
- the result has been checked against the original workflow; and
- reusable learning has been documented.
