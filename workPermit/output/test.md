---
client-id: ${CLIENT_ID}
consultant: ${CONSULTANT_NAME}
created-date: ${CREATION_DATE}
target-country: ${TARGET_COUNTRY}
---

# ${CLIENT_FULL_NAME} Immigration Profile


## 1. Basic Information
**Full Legal Name:** ${CLIENT_FULL_NAME}  
**Gender:** ${GENDER}  
**Date of Birth:** ${DOB_ISO}  
**Birthplace:** ${BIRTH_PLACE}  
**Birth Country:** ${BIRTH_COUNTRY}  
**UCI Number:** ${UCI_NUMBER}  
**Application #:** ${APPLICATION_NUMBER}  
**Nationality:** ${CURRENT_NATIONALITY}  
**Passport Number:** ${PASSPORT_NUM}  

**Current Country Status:**  
| Country       | Status               | Start Date   | End Date     |
|---------------|----------------------|--------------|--------------|
| ${CURRENT_COUNTRY} | ${CURRENT_STATUS}    | ${STATUS_START_DATE} | ${STATUS_END_DATE} |

**Language Tests:**  
| Language | Test Type | Listening | Speaking | Reading | Writing | Date       |
|----------|-----------|-----------|----------|---------|---------|------------|
${LANGUAGE_TEST_ROWS}

---

## 2. Employment History
| Employer       | Position     | Start Date | End Date  | Location   |
|----------------|--------------|------------|-----------|------------|
${EMPLOYMENT_HISTORY_ROWS}

**Document Status:**  
${EMPLOYMENT_DOC_CHECKLIST}

---

## 3. Education History
| Institution     | Degree       | Field       | Years     | Evaluation |
|-----------------|--------------|-------------|-----------|------------|
${EDUCATION_HISTORY_ROWS}

---

## 4. Relationship History
**Current Status:** ${MARITAL_STATUS}  
**Marriage Date:** ${MARRIAGE_DATE_ISO}  
**Spouse Name:** ${SPOUSE_FULL_NAME}  

**Previous Relationships:**  
${PREVIOUS_RELATIONSHIPS}

---

## 5. Family Members
**Core Family:**  
| Relationship | Name           | DOB        | Location     |
|--------------|----------------|------------|--------------|
${CORE_FAMILY_ROWS}

**Relatives Abroad:**  
${RELATIVES_ABROAD}

---

## 6. Travel History
| Entry Date   | Exit Date    | Destination | Purpose      |
|--------------|--------------|-------------|--------------|
${TRAVEL_HISTORY_ROWS}

**Visa Rejections:** ${VISA_REJECTION_COUNT}