Algorithm: Student Performance Analytics Pipeline

Input:

Student data (Name, Attendance, Task Score)

Process:

1. Start.
2. Read the student data.
3. If there is no data, print **"No Data Found"** and Stop.
4. Repeat for each student:

   * Check if Attendance or Task Score is missing.
   * If missing, replace it with 0.
   * Calculate Average Score:

     * Average = (Attendance + Task Score) / 2
   * Decide the Performance Band:

     * If Average ≥ 80 → **Excellent**
     * Else if Average ≥ 60 → **Good**
     * Else if Average ≥ 40 → **Average**
     * Else → **Poor**
   * Save the student's result.
5. Show three insights:

   * Total Excellent, Good, Average, and Poor students.
   * Student with the highest score.
   * Student with the lowest score.

 Output:

* Performance Band of each student.
* Three final insights.

End
