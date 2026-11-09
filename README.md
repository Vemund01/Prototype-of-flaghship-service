# Public Funding Navigator: prototype

Prototype built for the BI course *AI for Business* (Autumn 2026). It helps Norwegian early-stage founders find relevant public funding schemes.

**Live page:** https://vemund01.github.io/Prototype-of-flaghship-service/

## How it works

The page runs entirely in the browser, with no AI service and no login:

1. **Describe:** the founder describes the start-up in plain language (English or Norwegian), or loads one of seven test profiles.
2. **Confirm facts:** a built-in text engine extracts the facts (company form and age, stage, amount sought, sector, women leadership and more), and the founder can correct them.
3. **Rule check:** explicit rules check eligibility against a built-in database of 27 Norwegian and European public funding schemes. Each scheme is marked as:
   - **Passes rule check** (green)
   - **Needs checking** (amber): a fact is missing or a condition needs human judgement
   - **Qualifies, but not enough money** (yellow): the start-up meets the conditions, but the scheme's maximum is less than the amount sought
   - **Not indicated** or **Does not qualify** (grey/red), with the reason
4. **Draft shortlist:** a scoring model ranks the eligible schemes, with a reason, amount, deadline and link to the official page. Schemes that cover only part of the amount are listed separately.
5. **Advisor review:** a human advisor keeps, edits or removes each item before the shortlist is sent to the founder.

## Notes

- The same description always gives the same result. Unusual wording can be missed, so check the facts in step 2.
- Amounts in EUR are converted at an approximate fixed rate (1 EUR = NOK 11.5). Deadlines are compared with today's date.
- The scheme data was collected in October and November 2026 and must be checked on each funder's official page before use.
- Not financial or legal advice.
