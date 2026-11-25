M03L2 — AWS Service Selection Under Constraints

Overview

This project evaluates AWS services against eight business requests considering capability, latency, cost, language, compliance and output requirements.

Service Selection

Eight AWS service decisions were evaluated based on the business constraints.

Multi-Service Workflows

R2 — Pharmacy Consultation Transcription

1. Amazon Transcribe Medical — produces a medical transcript.
2. Amazon Comprehend Medical — identifies medication entities.

R8 — Compliance Filing Summary

1. Amazon Textract — extracts text from compliance filings.
2. Amazon Bedrock — generates a one-page board brief.

Console Verification

Amazon Comprehend PII detection was tested utilizing two English inputs: one structured and one conversational. Both Offsets and Labels modes were examined.

Cost Estimates

* R7 — Amazon Comprehend DetectSentiment: estimated $1,850 per month.
* R5 — Amazon Rekognition DetectModerationLabels: estimated $1,880 per month.
