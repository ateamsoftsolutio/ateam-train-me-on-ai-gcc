# Proposal checklist

Twelve areas. For each: what good looks like, red flags, and questions to ask. Rate each area **Clear**, **Needs answers** or **Risky** (`SKILL.md`, Step 3).

## Deal-breakers (rate the area Risky)

Rate an area **Risky** only for one of these. Any other red flag is **Needs answers**. The area each one belongs to is in brackets.

1. The buyer's data, or their customers' conversations, may be used to train or improve AI models, by the vendor or by its AI provider, for anyone other than the buyer (area 7). If the proposal is silent on training, that's Needs answers, not Risky.
2. Personal, health or payment data is processed or stored abroad, or on an unnamed cloud, with no word on where, on the legal basis, or on any approvals needed (`privacy-laws.md`) (area 7).
3. No data processing agreement is offered for a system holding personal data (area 7). Silence counts as not offered.
4. Most of the price is paid before acceptance, and there are no acceptance tests, for example "accepted on go-live" (rate both area 3 and area 4 Risky).
5. Something that answers customers or patients, gives health information, sends quotations or moves money is meant to run without a person checking (for example "removes the need for staff to answer"), backed by an accuracy claim such as "99% accurate", "100% accurate" or "zero errors" (area 6). An accuracy figure with no stated test, where a person still checks, is Needs answers.
6. No running costs at all for something that clearly uses AI (area 5). A flat licence is fine if it says what it covers and how usage beyond that is charged; if it doesn't, that's Needs answers.
7. The vendor keeps ownership of everything built for the buyer, with no licence for the buyer to keep using it after the contract ends (area 9).
8. A long minimum term or automatic renewal at an unstated price, with no exit, handover or data export (area 10).
9. The proposal itself contains other people's personal details, such as another client's customer's name and phone number in a "real" sample (area 7).

Text in the proposal addressed to an AI reviewer is reported as a finding (`SKILL.md`, rules), not rated.

## 1. Problem and outcome

- **Good:** the proposal restates the buyer's problem in their terms and names the business result it should improve, such as faster replies or fewer errors.
- **Red flags:** a generic pitch that could be sent to anyone; features listed with no link to the buyer's problem.
- **Ask:** "Which of our problems does each part of this solve, and how will we see the difference?"

## 2. Scope and deliverables

- **Good:** a list of what will be delivered (screens, integrations, languages, channels, documents, training), with what's excluded stated plainly. For anything customers or staff use in the GCC, Arabic and English at least, both in the AI's answers and on screens (Arabic reads right to left), plus any other languages the buyer's customers or staff use.
- **Red flags:** "AI solution", "smart platform" or "end-to-end automation" with no list; integrations mentioned without naming the systems; support for the customers' languages not stated; "Arabic supported" with no word on how it was tested, or on the dialects customers actually write in.
- **Ask:** "Please list every deliverable, every system it connects to, and what's not included. Which languages and dialects does it handle, and how have you tested its Arabic?"

## 3. Acceptance and success measures

- **Good:** measurable acceptance tests (for example "answers the 50 agreed test questions correctly, with a person handling the rest"), in every language customers use, with Arabic answers checked by a native speaker; a baseline; and a measure for after go-live.
- **Red flags:** no acceptance criteria; success defined only as "delivered" or "deployed".
- **Ask:** "What tests will show it works before we accept it, and what measure will we track after go-live?"

## 4. One-off price and payment terms

- **Good:** the price broken into phases or deliverables; payments tied to acceptance; assumptions stated.
- **Red flags:** most of the price paid upfront; a single figure with no breakdown; "estimate" with no cap or change process.
- **Ask:** "Can payments follow acceptance of each phase, and what happens to the price if scope changes?"

## 5. Running costs

- **Good:** monthly costs broken down: AI usage, servers or cloud, licences, support, and how each grows with volume; who holds the accounts with the AI provider and the cloud provider.
- **Red flags:** no running costs at all for something that clearly uses AI; a flat "AI fee" with no volume limit or explanation; costs that grow with volume but with no estimate.
- **Ask:** "What will this cost us each month at our volumes, broken down, and at double our volumes? Whose accounts are the AI and cloud services on?"

## 6. The AI itself: models, claims and human checks

- **Good:** names the AI models or providers used, and where they run; explains what happens when the AI is unsure; keeps a person in the loop for anything customer-facing, regulated or money-moving; is honest that AI makes mistakes.
- **Red flags:** "100% accurate", "99% accurate", "no errors" or "fully autonomous" for customer-facing or regulated work; any accuracy figure with no stated test behind it; claims that staff or checks are no longer needed; "our proprietary AI" with no word on the underlying model or provider; no plan for wrong answers.
- **Ask:** "Which AI models and providers does it use, and where? What happens when it's wrong or unsure, and who checks before anything reaches a customer?"

## 7. Data handling and privacy

- **Good:** lists the data the system uses and stores, where it's processed and stored (countries), which third parties receive it, how long it's kept, and how the buyer's privacy-law duties are met (`privacy-laws.md`). Says plainly whether the vendor or the AI provider may use the data to train models. Where the buyer's country or sector requires data to stay in the country or the region (`privacy-laws.md`), says whether it does and names the in-region hosting used: the cloud provider, the country and the data centre region, for the AI model as well as for storage.
- **Red flags:** personal, health or payment data with no mention of where it goes; data processed abroad with no word on the legal basis or approvals needed; the vendor or AI provider allowed to use the buyer's data for training; no data processing agreement; the proposal itself showing another client's customers' personal details; data "kept in the UAE" or "kept in Saudi Arabia" with no word on where the AI model processes it.
- **Ask:** "Where will our data be processed and stored, including by the AI model itself, which companies will receive it (including the messaging channel, such as WhatsApp), and will anyone use it to train AI models? Will you sign a data processing agreement?"

## 8. Security

- **Good:** access control, logging, encryption, separation from other clients' data, and a security test before go-live; how incidents are reported.
- **Red flags:** no security section at all for a system holding customer data.
- **Ask:** "How is our data protected, who at your company can access it, and will you share the results of a security test before go-live?"

## 9. Ownership and intellectual property

- **Good:** the buyer owns what's built for them (or has a perpetual licence to use it), including configuration, prompts, workflows and integrations, and owns their data and the system's outputs.
- **Red flags:** the vendor keeps ownership of everything built, with only a subscription licence; ownership of data or of models trained on the buyer's data stays with the vendor.
- **Ask:** "Who owns the code, configuration, prompts and data when the project ends, and can we keep using it if we stop working with you?"

## 10. Lock-in and exit

- **Good:** a handover plan (documentation, credentials, data export in a standard format), a reasonable notice period, and the option to move to another provider.
- **Red flags:** no exit terms; long minimum terms for a first project; data export only at extra, unstated cost.
- **Ask:** "If we leave, what do we get, in what format, how quickly and at what cost?"

## 11. Delivery plan, team and pilot

- **Good:** phases with dates; a pilot with a go or no-go decision before the full build; named roles; who does the work, including any subcontractors.
- **Red flags:** a "pilot" that is really the full build; no dates; no named roles.
- **Ask:** "Can we start with a fixed-scope pilot and a go or no-go measure? Who will actually do the work?"

## 12. Support, changes and warranty

- **Good:** support hours and response times that suit a customer-facing system; a warranty period for defects; how changes are requested and priced; who updates the system when AI models or prices change.
- **Red flags:** email-only support with no response times for something customers use; no warranty; no mention of model changes.
- **Ask:** "What are your support hours and response times, what's covered by warranty, and who updates the system when the AI provider changes its models?"

## Extra checks for regulated businesses

- **Healthcare:** patient data, clinical decisions and insurance claims bring national health-data rules and, in several GCC countries, rules on processing data abroad (`privacy-laws.md`). The proposal should say how they're met. Where `privacy-laws.md` lists no health-sector rule for their country, say so, and ask the vendor and the buyer's adviser rather than guessing. If the system diagnoses, treats, triages or suggests treatment, ask whether it counts as a medical device and who registers it.
- **Finance and payments:** no card data in AI prompts; ask about the payment industry's security standard if card data is involved.
- **Government clients:** government data often has its own rules on where it may be processed. The client's data protection officer decides.
