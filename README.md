# SST-UG-Shortlist-and-Interview-Plan

## Overview
This project addresses the SST UG Admission assignment, which involves designing a shortlisting criteria for 24 students applying to the UG program at SST and scheduling two rounds of interviews for the shortlisted candidates. The solution is implemented in Python, processes the provided dataset, and generates a structured Markdown output containing the shortlisting criteria, shortlisted students, and interview schedules.

### Tasks Completed
1. **Task 1: Shortlisting Criteria**
   - Designed a scoring system based on 10th board (20%), 12th board (30%), entrance exams (30%), and technical achievements (up to 30 points).
   - Assigned tiers: Tier 1 (≥85), Tier 2 (70–84), Tier 3 (50–69).
   - Shortlisted the top 15 students (~60% of 24), scalable to 1000 students.
   - Assumptions: Normalized grades (e.g., 10 CGPA = 100%), capped tech achievements at 3.

2. **Task 2: Interview Scheduling**
   - Scheduled two rounds (R1 and R2) for 15 shortlisted students across 3 interviewers.
   - Each interviewer has 3 hours/day (6 slots, 30 minutes each).
   - Round 2 reshuffles students for fairness.
   - Assumptions: 30-minute interviews, 18 total slots/day sufficient for 15 students.

### Deliverables
- **Shortlisting Criteria and Shortlisted Students**: Detailed in `sst_admission_output.md`.
- **Interview Schedule**: Rounds 1 and 2 schedules in `sst_admission_output.md`.
- **Structured Output**: Aesthetically formatted Markdown file for easy consumption.

### Files
- **`sst_admission.py`**: Python script that processes the dataset and generates the output.
- **`sst_admission_output.md`**: Generated Markdown file with all deliverables (submit this link).
- **`README.md`**: This file, providing project overview and instructions.

### How to Run
1. **Prerequisites**:
   - Python 3.6+ installed ([Download Python](https://www.python.org/downloads/)).
   - Install the `tabulate` library: Run `pip install tabulate` in your terminal.

2. **Steps**:
   - Clone or download this repository.
   - Open a terminal in the project folder.
   - Run the script: `python sst_admission.py`.
   - Check the generated `sst_admission_output.md` file.

3. **Output**:
   - The script creates `sst_admission_output.md`, which contains all required deliverables.

### Assumptions and Scalability
- **Normalization**: Grades like 10 CGPA = 100%, A = 90%, B+ = 85%.
- **Entrance Scores**: Highest of JEE Mains, JEE Advanced, BITSAT (scaled), or Codechef (scaled).
- **Scalability**: The script can handle 1000+ students by adjusting the shortlist size in the code (e.g., top 60%).

### Submission
- **Link**: [View the output on GitHub](https://github.com/yourusername/sst-admission-task/blob/main/sst_admission_output.md)  
  *(Replace with your actual GitHub link after uploading)*

### Contact
For questions or issues, reach out to [your email] or submit an issue on this repository.

---
*Generated on March 19, 2025*
