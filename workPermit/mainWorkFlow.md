# Work Permit Process

## 1. Initial Consultation
- **Understand Client’s Needs**: Discuss the client’s background, job offer, and type of work permit they require (e.g., employer-specific or open work permit).
- **Eligibility Check**: Assess if the client meets the eligibility criteria for the work permit they are applying for.

## 2. Eligibility Assessment
- **Review Documents and Requirements**: Confirm that the client has a valid job offer, required qualifications, and if applicable, a positive LMIA (or LMIA exemption).
- **Determine Work Permit Type**: Decide on the appropriate work permit based on the client’s situation (e.g., employer-specific, open, or International Mobility Program).

## 3. Document Collection
- **Create Document Checklist**: Prepare a list of required documents (e.g., job offer letter, passport, proof of qualifications, biometrics, etc.).
- **Collect Documents**: Guide the client to gather all necessary documents and ensure they meet IRCC requirements.

## 4. Prepare and Submit Application
- **Complete Forms**: Fill out the work permit application forms accurately.
- **Ensure Accuracy**: Double-check all documents and forms for completeness and correctness.
- **Submit Application**: Submit the application to IRCC, either online or by paper, based on the client’s case.

# Main Steps interacting with AI
- **Step 1:** Generate a simple questionnaire to locate the client's needs and confirm the work permit type. You can also use a standard work permit interview template in Word without generating. 
  - Input: none
  - Template: prompt_outlineInterview.md
  - Output: A interview document for a new client to fill out.

- **Step 2:** Generate an analysis report that need to be prepared. 
  - Input: A interview document filled out by client.
  - Template: prompt_analysisReport.md
  - Output: analysis report.

- **Step 3:** Generate a document list which need to be prepared by client.
  - Input: A interview document filled out by client, Type of work permit
  - Template: imm5548e, imm5556, prompt_documentList.md
  - Output: A document List to client

- **Step 3:** Input data in our system
  - No interacting with Ai. Input the data in our system, which the data is collected from prepared client's documents. 

- **Step 4:** Generate applicant's affidavit
  - Input: Complete data, prepared document list
  - Template: prompt_affidavitForPrincipal.md
  - Output: applicant's affidavit

- **Step 5:** Generate employer's affidavit
  - Input: Complete employer's data, prepared employer's document list
  - Template: prompt_affidavitForEmployer.md
  - Output: Employer's Affidavit

- **Step 6:** Generate submission letter
  - Input: Complete principal data
  - Template: prompt_submissionLetter.md
  - Output: Submission Letter
