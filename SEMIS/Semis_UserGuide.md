# SEMIS end-user manual: individual Tracker data capture (web) { #semis_web_user_manual }

**SEMIS version:** 2.1

## Introduction { #semis_web_introduction }

This manual guides users and trainers through data capture in the SEMIS web app. It explains student and staff workflows with step-by-step instructions and screenshots.

The student modules are **Enrollment**, **Attendance**, **Performance**, **Final Result**, and **Transfer**. The staff modules are **Staff Registry**, **Attendance**, **Transfer**, and **Re-enroll**.

## About SEMIS { #semis_web_about }

SEMIS manages school, student, and staff information in DHIS2. It supports individual records for enrollment, attendance, performance, and other education information.

School data capture includes routine tasks involving many people, such as recording attendance or assessment results for an entire class. SEMIS provides interfaces and bulk operations to simplify these tasks.

## Before you begin { #semis_web_prerequisites }

Your administrator must install the SEMIS app and configure access and the required settings. If you cannot see the app, contact your administrator.

> **Important**
>
> For the web workflows described in this manual, use a computer, tablet, or phone with an internet connection and a web browser, such as Google Chrome or Mozilla Firefox. Obtain your DHIS2 instance address and individual login credentials from your administrator.

### Log in { #semis_web_log_in }

1. Open your web browser.
2. Enter the DHIS2 web address provided by your administrator and press **Enter**.
3. Wait for the login page to load.
4. Enter your assigned username and password.
5. Click **Log in**.

   ![Log in: reference image 1](SEMISimages/01_log_in.png)

> **Note**
>
> Enter your credentials exactly as provided, including capital letters and special characters. The interface language follows the language settings configured for your user account.

### Log out { #semis_web_log_out }

1. Click your user account initials in the top-right corner.
2. Select **Log out**.

![Log out: reference image](SEMISimages/02_log_out.png)

## Open SEMIS { #semis_web_navigation }

1. After logging in, open the **App Menu** in the top-right corner of DHIS2.

   ![Open SEMIS: reference image 3](SEMISimages/03_open_semis.png)

2. Search for **SEMIS** in the search bar, or locate it in the list of applications.
3. Click **SEMIS** to open the app.

![Open SEMIS: reference image 4](SEMISimages/04_open_semis.png)

## Student data entry { #semis_web_student_data_entry }

The student program contains five modules:

| Module | Purpose |
| --- | --- |
| Enrollment | Register new learners and manage their school enrollment details. |
| Attendance | Record daily attendance for learners, including multiple learners on one screen. |
| Performance | Record numeric assessment results for an academic year using the locally configured grading scale. |
| Final Result | Record academic outcomes and promote selected learners to the next grade. |
| Transfer | Move learners between schools while retaining their history; the receiving school reviews the transfer. |

![Student data entry: reference image 5](SEMISimages/05_student_data_entry.png)

### Enrollment { #semis_web_student_enrollment }

Use **Enrollment** to register new learners and manage enrollment information.

> **Important**
>
> Register each learner only once as an individual in the system. Registration is different from enrollment in an academic year. Reuse the existing learner record for subsequent academic years, promotions, and transfers instead of creating a duplicate person record.

#### Search for an existing student { #semis_web_student_search }

Always search before creating a new learner record, including when a learner moves from primary to secondary school.

To view the learners in a class:

1. Select the correct **Academic Year**.
2. Select the **School**, **Grade**, and **Section** or class.

   ![Search for an existing student: reference image 6](SEMISimages/06_search_for_an_existing_student.png)

3. Review the list of students in the selected class.

![Search for an existing student: reference image 7](SEMISimages/07_search_for_an_existing_student.png)

To search for a learner:

1. Open **Search Student**.
2. Complete at least one search field.
3. Review the matching learners.
4. Use the action in the learner's row to open their enrollment history. Review the schools and academic years already recorded.

![Search for an existing student: reference image 8](SEMISimages/08_search_for_an_existing_student.png)

![Search for an existing student: reference image 9](SEMISimages/09_search_for_an_existing_student.png)

![Search for an existing student: reference image 10](SEMISimages/10_search_for_an_existing_student.png)

If the learner exists but has no enrollment for the selected academic year, use the available enrollment action for that existing record. Do not create a second learner record. If no existing learner record is found, follow [Register a new student](#semis_web_new_student).

Available enrollment action:

![Search for an existing student: reference image 11](SEMISimages/11_search_for_an_existing_student.png)

![Search for an existing student: reference image 12](SEMISimages/12_search_for_an_existing_student.png)

#### Register a new student { #semis_web_new_student }

You can register one learner at a time or import several learners using an Excel template.

##### Register a single student { #semis_web_single_student }

1. Click the registration button shown below.

   ![Register a single student: reference image 13](SEMISimages/13_register_a_single_student.png)

2. Complete the enrollment details, such as **Academic Year**, **Grade**, and **Class**.
3. Complete the student profile, including name and date of birth, and the annual profile details.
4. Submit the details using the form's save action.


   ![Register a single student: reference image 14](SEMISimages/14_register_a_single_student.png)

5. If you select **Save and close**, check that the newly enrolled student appears in the list.

   ![Register a single student: reference image 16](SEMISimages/16_register_a_single_student.png)

##### Use bulk enrollment { #semis_web_bulk_student_enrollment }

Bulk enrollment provides options to enroll new students or update existing students.

1. Open the bulk enrollment area and choose the appropriate operation.
2. Click the download-template button.
3. Enter the number of rows required. Each row represents one student; for example, enter **100** for 100 students.
4. Click **Submit** to download the template.
5. Complete the template with the required student information and save the Excel file.
6. For new registrations, select **Enroll new student** and upload or drag the completed file into the dialog.
7. Click **Continue**, then use the import action to begin processing the data.
8. Review any validation errors or conflicts. Correct the Excel file and upload it again as needed.
9. When the data is valid, click **Import students** to complete the import.
10. Check that the imported students appear in the list.

![Use bulk enrollment: reference image 17](SEMISimages/17_use_bulk_enrollment.png)

![Use bulk enrollment: reference image 18](SEMISimages/18_use_bulk_enrollment.png)

![Use bulk enrollment: reference image 19](SEMISimages/19_use_bulk_enrollment.png)

![Use bulk enrollment: reference image 20](SEMISimages/20_use_bulk_enrollment.png)

![Use bulk enrollment: reference image 21](SEMISimages/21_use_bulk_enrollment.png)

![Use bulk enrollment: reference image 22](SEMISimages/22_use_bulk_enrollment.png)

![Use bulk enrollment: reference image 23](SEMISimages/23_use_bulk_enrollment.png)

### Student attendance { #semis_web_student_attendance }

Use **Attendance** to record attendance for enrolled learners.

![Student attendance: reference image 24](SEMISimages/24_student_attendance.png)

Open the module from the student **Attendance** tile's three-line menu on the SEMIS home page, or select **Attendance** from the left-side menu.

#### Record student attendance { #semis_web_record_student_attendance }

1. Select **School**, **Grade**, **Class**, and **Academic Year**.
2. Click **Take Attendance** to display the enrolled learners.
3. Check the attendance date.
4. Click **Start Attendance** to mark learners as present for the selected day.
5. Mark absent learners as **Absent** and enter the **Reason for Absence**.
6. Review the total numbers of present and absent learners in the top bar.

> **Note**
>
> The example screenshots show a class with only one enrolled learner. Your list reflects the learners enrolled in the selected class.

![Record student attendance: reference image 25](SEMISimages/25_record_student_attendance.png)

![Record student attendance: reference image 26](SEMISimages/26_record_student_attendance.png)

![Record student attendance: reference image 27](SEMISimages/27_record_student_attendance.png)

![Record student attendance: reference image 28](SEMISimages/28_record_student_attendance.png)

#### View student attendance records { #semis_web_view_student_attendance }

1. Click **View Attendance Records**.
2. In the calendar view, select the end date for the period you want to review.
3. Review each learner's attendance status for the displayed dates.
4. Click **View Reason for Absence** to inspect the reason recorded for an absent day.

![View student attendance records: reference image 29](SEMISimages/29_view_student_attendance_records.png)

![View student attendance records: reference image 30](SEMISimages/30_view_student_attendance_records.png)

![View student attendance records: reference image 31](SEMISimages/31_view_student_attendance_records.png)

#### Import student attendance { #semis_web_bulk_student_attendance }

If bulk attendance is used in your implementation:

1. Open **Bulk Attendance**.
2. Select **Import Student Attendance**.
3. Upload the completed attendance file to record attendance in bulk.

![Import student attendance: reference image 32](SEMISimages/32_import_student_attendance.png)

![Import student attendance: reference image 33](SEMISimages/33_import_student_attendance.png)

### Student performance { #semis_web_student_performance }

Use **Performance** to capture learner scores and results for terms within an academic year.

![Student performance: reference image 34](SEMISimages/34_student_performance.png)

1. Open **Performance**.
2. Select the correct **Academic Year**, **School**, **Grade**, and **Class**.
3. Select the required term, such as **Term 1**, **Term 2**, or **Term 3**. In the example, the selected term changes from green to orange.
4. Click **Allow Edit Mode**.
5. Enter each score in the cell at the intersection of the learner's row and the subject's column.
6. Check the save feedback: a green cell border indicates that the entered value has been saved.

![Student performance: reference image 35](SEMISimages/35_student_performance.png)

![Student performance: reference image 36](SEMISimages/36_student_performance.png)

### Final results and promotion { #semis_web_student_final_result }

Use **Final Result** to record outcomes and progress learners to the next grade.

![Final results and promotion: reference image 37](SEMISimages/37_final_results_and_promotion.png)

1. Select the relevant school, grade, and class.
2. Use the checkboxes to select the learners whose results you want to record.
3. Assign the appropriate outcome, including promotion, failure, or dropout, as applicable.
4. Click **Submit** and review the result.
5. Select the learners marked for promotion.
6. Click **Perform Promotion**.
7. Update the academic year, grade, transfer-in status, first-time-in-grade status, class, and enrollment date for the selected learners.
8. Click **Perform Promotion** to complete the process.

![Final results and promotion: reference image 38](SEMISimages/38_final_results_and_promotion.png)

![Final results and promotion: reference image 39](SEMISimages/39_final_results_and_promotion.png)

![Final results and promotion: reference image 40](SEMISimages/40_final_results_and_promotion.png)

### Student transfers { #semis_web_student_transfer }

Use **Transfer** to move learners between schools while retaining their school history.

![Student transfers: reference image 41](SEMISimages/41_student_transfers.png)

Select the origin school to view the transfer tabs.

| Tab | Purpose |
| --- | --- |
| Outgoing transfer | View learners transferred from the selected school and the status of each transfer. |
| Incoming transfer | Review learners transferring into the selected school and approve or reject their transfers. |

#### Initiate an outgoing student transfer { #semis_web_student_outgoing_transfer }

1. Click **Perform Transfer** to display learners at the selected school.
2. Filter by grade, class, and academic year as needed.
3. Select the checkboxes for learners moving to the same destination school.
4. Click **Execute Transfer**.
5. Select the destination school. Expand the organisation unit hierarchy using the arrows until you reach the school level, then click the school.
6. Select the reason for transfer from the available list.
7. Click **Perform Transfer**.
8. Check for the green confirmation message: **Transfer executed successfully**.

![Initiate an outgoing student transfer: reference image 42](SEMISimages/42_initiate_an_outgoing_student_transfer.png)

![Initiate an outgoing student transfer: reference image 43](SEMISimages/43_initiate_an_outgoing_student_transfer.png)

![Initiate an outgoing student transfer: reference image 44](SEMISimages/44_initiate_an_outgoing_student_transfer.png)

![Initiate an outgoing student transfer: reference image 45](SEMISimages/45_initiate_an_outgoing_student_transfer.png)

![Initiate an outgoing student transfer: reference image 46](SEMISimages/46_initiate_an_outgoing_student_transfer.png)

#### Review incoming student transfers { #semis_web_student_incoming_transfer }

At the receiving school:

1. Open **Incoming transfer** to review incoming learners.
2. In the transfer status column, click the green thumb icon to approve a learner who has joined the school, or the red thumb icon to reject a learner who is not joining.
3. After approval, check that the learner appears in the receiving school's learner list and relevant modules.

![Review incoming student transfers: reference image 47](SEMISimages/47_review_incoming_student_transfers.png)

![Review incoming student transfers: reference image 48](SEMISimages/48_review_incoming_student_transfers.png)

## Staff data entry { #semis_web_staff_data_entry }

The staff program contains four modules:

| Module | Purpose |
| --- | --- |
| Staff Registry | Register teaching and non-teaching staff and maintain their details. |
| Attendance | Record staff attendance and monitor presence and absences. |
| Transfer | Move staff between schools while retaining their assignment history. |
| Re-enroll | Review staff details and employment status and carry eligible staff forward into a new academic year. |

Staff re-enrollment supports reviewing employment information and updating roles, deployments, contracts, and statuses where these fields are configured. Multiple staff members can be processed together.

![Staff data entry: reference image 49](SEMISimages/49_staff_data_entry.png)

### Staff registry { #semis_web_staff_registry }

Use **Staff Registry** to register new teaching and non-teaching staff.

> **Important**
>
> Register each staff member only once as an individual. Use the existing staff record for transfers and subsequent academic-year re-enrollments.

1. Select the school where the staff member will be registered. Users assigned to one school will see only that school.
2. Select the correct **Academic Year**.
3. Review the staff list.

You can register staff individually or import several staff members using an Excel file.

#### Register a single staff member { #semis_web_single_staff }

1. Click the registration button shown below.

   ![Register a single staff member: reference image 50](SEMISimages/50_register_a_single_staff_member.png)

2. Enter the staff member's details in the dialog.
3. Complete all required fields and click **Submit**.

![Register a single staff member: reference image 51](SEMISimages/51_register_a_single_staff_member.png)

![Register a single staff member: reference image 52](SEMISimages/52_register_a_single_staff_member.png)

![Register a single staff member: reference image 53](SEMISimages/53_register_a_single_staff_member.png)

#### Use bulk staff enrollment { #semis_web_bulk_staff_enrollment }

1. Click **Bulk Enrollment**.
2. Select **Enroll New Staff** to add staff, or **Update Existing Staff** to modify existing records.
3. Click **Export Empty Template** to download the Excel template.
4. Complete all required staff information and save the file.
5. Upload the completed template.
6. Review the uploaded data and correct any errors.
7. Submit the file to complete the process.

![Use bulk staff enrollment: reference image 54](SEMISimages/54_use_bulk_staff_enrollment.png)

![Use bulk staff enrollment: reference image 55](SEMISimages/55_use_bulk_staff_enrollment.png)

![Use bulk staff enrollment: reference image 56](SEMISimages/56_use_bulk_staff_enrollment.png)

### Staff attendance { #semis_web_staff_attendance }

Use staff **Attendance** to record daily attendance for teachers and other staff and review attendance patterns.

![Staff attendance: reference image 57](SEMISimages/57_staff_attendance.png)

#### Record staff attendance { #semis_web_record_staff_attendance }

1. Select **School**, **Type of Staff**, **Employment Type**, and **Academic Year**.
2. Click **Take Attendance**.
3. Review the staff list, including names, employment types, and staff types.
4. Confirm the selected date.
5. Click **Mark all as present** to mark all staff present, or use the individual **Present**, **Absent**, and **Late** options.
6. For absent staff, update **Reason of Absence**.

![Record staff attendance: reference image 58](SEMISimages/58_record_staff_attendance.png)

#### View staff attendance records { #semis_web_view_staff_attendance }

1. Click **View Attendance Records**.
2. In the calendar view, select the end date for the period to review.
3. Review each staff member's attendance status for the displayed dates.
4. Click **View Reason for Absence** to inspect a recorded absence reason.

![View staff attendance records: reference image 59](SEMISimages/59_view_staff_attendance_records.png)

#### Import staff attendance { #semis_web_bulk_staff_attendance }

If bulk attendance is used in your implementation:

1. Open **Bulk Attendance**.
2. Select **Import Staff Attendance**.
3. Upload the completed attendance file.

![Import staff attendance: reference image 60](SEMISimages/60_import_staff_attendance.png)

### Staff transfers { #semis_web_staff_transfer }

Use staff **Transfer** to move staff between schools while retaining their school assignment history.

Select the origin school to view the transfer tabs.

| Tab | Purpose |
| --- | --- |
| Outgoing transfer | View staff transferred from the selected school and their transfer status. |
| Incoming transfer | Review incoming staff and approve or reject their transfers. |

#### Initiate an outgoing staff transfer { #semis_web_staff_outgoing_transfer }

1. Click **Perform Transfer** to display staff from the selected school.
2. Filter by **Type of Staff**, **Employment Type**, and **Academic Year** as needed.
3. Select the checkboxes for staff moving to the same destination school.
4. Click **Execute Transfer**.
5. Expand the organisation unit hierarchy to the school level and select the destination school.
6. Select **Reason for Transfer** from the available list.
7. Click **Perform Transfer**.
8. Check for the green confirmation message: **Transfer executed successfully**.

![Initiate an outgoing staff transfer: reference image 61](SEMISimages/61_initiate_an_outgoing_staff_transfer.png)

![Initiate an outgoing staff transfer: reference image 62](SEMISimages/62_initiate_an_outgoing_staff_transfer.png)

![Initiate an outgoing staff transfer: reference image 63](SEMISimages/63_initiate_an_outgoing_staff_transfer.png)

#### Review incoming staff transfers { #semis_web_staff_incoming_transfer }

At the receiving school:

1. Open **Incoming Transfer**.
2. In the **Transfer Status** column, click the green thumb icon to approve a staff member joining the school, or the red thumb icon to reject the transfer.
3. After approval, check that the staff member appears in the receiving school's staff list and relevant modules.

![Review incoming staff transfers: reference image 64](SEMISimages/64_review_incoming_staff_transfers.png)

### Staff re-enrollment { #semis_web_staff_re_enrollment }

Use **Re-enroll** to update and confirm staff details at the beginning of each academic year.

![Staff re-enrollment: reference image 65](SEMISimages/65_staff_re_enrollment.png)

![Staff re-enrollment: reference image 66](SEMISimages/66_staff_re_enrollment.png)

#### Select staff and assign a status { #semis_web_staff_re_enrollment_status }

1. Select **School**, **Type of Staff**, **Employment Type**, and **Academic Year**.
2. Select the checkbox beside each staff member to re-enroll. Check the number of selected rows.
3. Click **Assign Re-Enrollment Status**.
4. Choose the appropriate status for the selected staff members.
5. Save your selection.

![Select staff and assign a status: reference image 67](SEMISimages/67_select_staff_and_assign_a_status.png)

#### Perform staff re-enrollment { #semis_web_perform_staff_re_enrollment }

1. After assigning the status, click **Perform Re-Enrollment**.
2. Confirm the action when prompted.
3. Check the confirmation message indicating that re-enrollment was completed successfully.

![Perform staff re-enrollment: reference image 68](SEMISimages/68_perform_staff_re_enrollment.png)

#### Use bulk staff re-enrollment { #semis_web_bulk_staff_re_enrollment }

If bulk staff re-enrollment is used in your implementation:

1. Click **Bulk Staff Re-Enrollment**.
2. Download the re-enrollment template, if required.
3. Complete the template with the correct staff re-enrollment details.
4. Upload the completed file to re-enroll staff in bulk.

## School calendar { #semis_web_school_calendar }

The **School Calendar** module allows authorised users to create, view, and edit the academic calendar.

> **Important**
>
> School calendar settings affect the application's workflows. Access is controlled by user roles and permissions; only users with the required administrative rights can manage this module. See the [SEMIS configuration manual](https://docs.dhis2.org/en/implement/education/semis/semis-configuartion.html) for configuration details.
