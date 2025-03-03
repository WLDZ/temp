# User Acceptance Testing (UAT) Checklist

---

**Instructions:**
1. **Use the relevant checklist** for the type of testing you are performing. For example, if you are testing the new flat file, follow the checklist under "1. New Flat File Testing."
2. **Check off tasks as you complete them**. If any additional checks or actions are needed based on the specific test case, add them to the checklist as you proceed.

---

## 1. New Flat File Testing
- [ ] Ensured the location and accessibility of the file in the test area
- [ ] Confirmed the file format, structure, and schema matched specifications
- [ ] Checked data integrity and completeness
- [ ] Validated data mappings against specifications
- [ ] Ensured successful data load into the database within the test environment
- [ ] Reconciled the source file with the target tables
- [ ] Obtained stakeholder approval for file data and transformation

**Additional Checks (if needed):**
- [ ] Verified file version and timestamp for accuracy

**Expected Outcome:** The data was correctly imported, and transformations were applied as per requirements

---

## 2. Changes to Existing Report
- [ ] Compared the old and new report structures
- [ ] Validated data accuracy for modified fields
- [ ] Verified filter and parameter functionality
- [ ] Performed performance testing on large datasets
- [ ] Validated report output against expected business logic

**Additional Checks (if needed):**
- [ ] Checked compatibility with previous report versions

**Expected Outcome:** The report reflected the required changes without data discrepancies

---

## 3. New Table or View
- [ ] Ensured the table/view structure matched the approved design
- [ ] Validated primary keys, indexes, constraints, and relationships
- [ ] Performed sample inserts, updates, and deletes to ensure data integrity
- [ ] Confirmed with stakeholders that the data met their requirements
- [ ] Verified permissions and access control
- [ ] Ran queries to ensure correct data retrieval
- [ ] Obtained formal stakeholder approval

**Additional Checks (if needed):**
- [ ] Checked indexing performance with sample queries

**Expected Outcome:** The table/view functioned as intended and met business requirements

---

## 4. Changes to Existing Table or View
- [ ] Validated changes against the approved schema design
- [ ] Tested backward compatibility with existing queries
- [ ] Ran data validation checks before and after the change
- [ ] Verified indexing and performance implications
- [ ] Confirmed security and access permissions

**Additional Checks (if needed):**
- [ ] Tested the impact on stored procedures and triggers

**Expected Outcome:** There was no negative impact on dependent applications or reports

---

## 5. Import Data from New Source
- [ ] Obtained complete requirements from stakeholders
- [ ] Validated data extraction from the new source
- [ ] Confirmed transformation rules were correctly applied
- [ ] Verified data completeness and accuracy
- [ ] Checked for duplicates and ensured data consistency
- [ ] Compared imported data with source records

**Additional Checks (if needed):**
- [ ] Validated data type consistency across systems

**Expected Outcome:** Data from the new source was correctly ingested and transformed

---

## 6. Changes to Existing Data
- [ ] Identified impacted tables and records
- [ ] Validated update scripts for correctness
- [ ] Checked referential integrity before and after the change
- [ ] Verified reports and queries reflected expected results
- [ ] Tested rollback strategy if necessary

**Additional Checks (if needed):**
- [ ] Validated the timing of data updates to avoid conflicts

**Expected Outcome:** Data changes were successfully applied and did not break business logic

---

## 7. Provide Data via Linked Server
- [ ] Validated connectivity and authentication to the linked server
- [ ] Ran sample queries to fetch and compare data
- [ ] Checked performance impact on source and target systems
- [ ] Ensured data consistency between the linked server and local queries
- [ ] Tested permissions and security configurations

**Additional Checks (if needed):**
- [ ] Verified latency and throughput between systems

**Expected Outcome:** Data access via the linked server was secure, accurate, and performant

---

## Sign-Off Checklist
- [ ] Confirmed that all UAT test cases were executed successfully
- [ ] Ensured all stakeholders had reviewed and approved test results
- [ ] Obtained formal sign-off from the Test Manager and key stakeholders
- [ ] Addressed all feedback from stakeholders
- [ ] Confirmed that no critical issues remained unresolved
`
