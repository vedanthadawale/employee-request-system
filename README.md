# Employee Request Management System (Proof of Concept)

A working prototype of a single intake point for employee requests (HR, IT,
Payroll, Operations), with automatic categorisation, unique ticket IDs and
tracked states.

**Live demo:** https://vedanthadawale.github.io/employee-request-system/

## What it shows

- **Submit request:** a standard form for requests from any channel
- **Auto-categorisation:** keyword scoring picks the department and priority;
  unmatched requests go to a triage desk
- **Unique ticket IDs:** for example `REQ-20261005-0001`, with a history log
- **Service desk:** move tickets through Open, Active and Finalized, with SLA
  warnings and escalation
- **Workflow:** end-to-end lifecycle diagram and escalation rules
- **Routing rules:** the keywords and SLA hours the prototype uses

## How to try it

1. Open the live demo
2. Click **Fill sample** and submit a request
3. Go to **Service desk** to move it through its states
4. Click **Simulate 5h passing** to see SLA warnings and escalation

## Limitations

- No login or backend; tickets are saved only in the viewer's own browser
- No real email, SMS or WhatsApp connection (a production version would add these)
- Keyword rules are for demonstration, not production accuracy

## Tech

Single HTML file (HTML, CSS, JavaScript). [Mermaid](https://mermaid.js.org/) draws the workflow diagram.
