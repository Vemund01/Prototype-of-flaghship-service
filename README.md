# Public Funding Navigator: prototype

Prototype built for the BI course *AI for Business* (Autumn 2026). It helps Norwegian early-stage founders find relevant public funding schemes.

This version runs entirely in the browser with no AI service and no login:

1. **Fact extraction:** a built-in text engine reads the founder's description (English or Norwegian) with keyword and pattern rules and fills in the fact fields.
2. **Eligibility check:** explicit rules compare the facts with each scheme's conditions in the database.
3. **Ranking:** a scoring model ranks the eligible schemes (rule result, amount fit, stage, purpose match) and writes the reasons from templates.
4. **Advisor review:** a human approves the shortlist.

Results are deterministic: the same description always gives the same result. Always check the extracted facts in step 2.
