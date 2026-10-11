# Evaluation Questions 

A set of 62 test queries formulated in Spanish for the evaluation of a virtual educational assistant on pediatric type 1 diabetes. The questions were drafted based on thematic categories from a knowledge base; these categories were identified by researchers based on the concerns and information needs expressed in a questionnaire administered to parents and caregivers. They are not direct transcriptions of questionnaire responses, nor are they a random sample of real conversations.

## Content

`evaluation_question_virtual_assistant.csv` contains the following fields: `id`, `question`, `descriptive_thematic_category`, `included_in_ragas_evaluation`, and `reason_for_ragas_exclusion`.

Of the 62 queries, 58 were included in the RAGAS educational evaluation subset with an `ok` status; four urgent care queries were excluded because the assistant handles them through the safety layer rather than through conventional educational generation. The four excluded queries correspond to IDs 21 through 24.

The reference answers used in the original evaluation were automatically generated from entries retrieved from the knowledge base, without independent case-by-case clinical validation. Therefore, the evaluation does not establish clinical reliability or external validity.

The questions published here are test formulations, not verbatim statements from participants. This release does not include participant responses, personal data, or health records.
