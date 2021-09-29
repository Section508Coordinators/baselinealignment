---
# The layout must be 'testcase'; DO NOT Change
layout: testcase

# Brief, descriptive title for the test case
title: Sensory Characteristics - DNA: no Sensory Characteristics 


# The Test Case ID should follow the pattern: 
# TC[Baseline Test Procedure #]-[Test Instruction #]-
# [Expected Result (pass/fail/dna)]-[example #], e.g., TC05.1-1-fail-1
tcid: TC7.2-ic-dna-1


# Description of the Test Case, the included code sample, test considerations,
# and rationale for the expected result according to the applicable ICT
# Baseline test
descr: | 
    The code sample presents a page with no instructions that rely on Sensory Characteristics. A successful test should identify a DNA against Baseline Test 6.4 Sensory Characteristics.

# Reference and link to the applicable ICT Baseline test
app-baseline: | 
    [6.4 Test Procedure for Sensory Characteristics](https://github.com/Section508Coordinators/ICTTestingBaseline/blob/section508coordinators301/07Sensory.md#72-test-procedure-for-sensory-characteristics)

    **Baseline Test ID:** 6.4 Test Procedure for Sensory Characteristics
    
    **Test Instruction:** Identify Content

# Expected result that the ICT Baseline would predict
# [Pass | Fail | DNA]
result: DNA

# Brief description of the rationale for the expected result
result-descr: DNA since there are no instructions that rely on Sensory Characteristics.

# URL for the code sample
# In the sample code file, add id="tc_code" to the 
# element that contains the relevant code snippet.
#
# Then upload the code sample to the 'testfiles' folder 
# and provide the link (and only the url) below.
sample: /testfiles/TF1/TC7.2-ic-dna-1.html

# Table of test instructions, including the following table headers: 
# Test Instruction #; Instruction Detail; Expected Test Case Result
#
# Include the table in the content section below
---
| Test Instruction | Instruction Detail | Expected Test Case Result |
|------------------|--------------------|---------------------------|
| **IC-1** | Identify instructions for understanding and operating content that use sensory information to convey information. This may include references to shape, size, visual location, orientation, or sound.
| Not Applicable; page has no instructions that rely on Sensory Characteristics. |