================================
Test Protocols and Test Reports
================================

Test Protocols
----------------

During the execution of each manual test, a test protocol must be created. The test protocol includes the following information:

    - Tester's Name
    - Date and Time
    - Duration of the Test Run
    - Revision Number (Commit Number) or Version Number of the tested system

Additionally, for each test case from the "Test Cases" document, the following aspects should be recorded in tabular form:

.. list-table:: Test Results
   :widths: 15 25 25 15 20
   :header-rows: 1

   * - Test Case No
     - Expected Outcome
     - Actual Outcome
     - Test Result
     - Remarks
   * - 1
     - Expected outcome for 1
     - Actual outcome for 1
     - Green (pass)
     - Any remarks
   * - 2
     - Expected outcome for 2
     - Actual outcome for 2
     - Red (fail)
     - Any remarks
   * - 3
     - Expected outcome for 3
     - Actual outcome for 3
     - Yellow (blocked)
     - Any remarks


Explanation of Columns:
    - Test Case No: Unique identifier for the test case.
    - Expected Outcome: The expected outcome or output of the system as per the test case.
    - Actual Outcome: The actual outcome or output observed during the test execution.
    - Test Result: Color-coded result indicating whether the test passed (Green), failed (Red), is blocked (Yellow), or is not available (No color).
    - Remarks: Any additional remarks or comments related to the test case.

Test Reports
--------------

The test report summarizes the test protocols and includes simple metrics, such as:

    - Total number of test cases
    - Number of executed test cases
    - Number of passed or failed test cases
    - Number of errors noted in the test protocol

These errors undergo a fault analysis:

    1. Identifying the fault: Determine if it is an actual software defect or a faulty test case, incorrect test execution, etc.
    2. Is the fault already known from previous tests?
    3. Fault Classification:
           - Class 1: Incorrect specification
           - Class 2: System crash
           - Class 3: Major functionality failure
           - Class 4: Functional deviation or limitation
           - Class 5: Minor deviation
           - Class 6: Cosmetic issue
    4. Prioritization:
           - Level 1: Immediate fix
           - Level 2: Fix in the next version
           - Level 3: Correction at some point
           - Level 4: Correction planning is open

Based on the fault analysis, the test report concludes the test run's result, which includes:

    - Evaluation of the software's condition
    - Achievement of quality goals
    - Consequences drawn from the current state, including measures to avoid future errors and improvements in the development process.
