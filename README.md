# Team Git Workflow

To keep our work organized, we follow these rules:

1. Do not push directly to `main`
2. Create a separate branch for every task
3. Branch format: `type/short-name`
4. Commit format: `type(scope): short message`
5. Open a Pull Request after pushing
6. Another teammate must review before merge

## Branch examples

- `feat/add-homepage`
- `fix/readme-typo`
- `docs/update-readme`

## Commit example

- `feat: add homepage`
- `fix: correct typo in readme`
- `docs: add setup instructions`
- `feat(auth): implement JWT-based login`
- `fix(api): correct response schema for users endpoint`


For more details, see [CONTRIBUTING.md](./CONTRIBUTING.md).
sue occurs daily in classrooms and affects the efficiency and integrity of the educational process.

---

# Project Overview

**Smart Attendance System Using Face Recognition**

## 1 Idea Name

**Smart Attendance System Using Face Recognition**
A system that automatically records student attendance using a camera and AI-based face recognition.

## 2 Problem

In many educational institutions, attendance is recorded manually, which consumes lecture time and can lead to errors or manipulation.
Students may register attendance for others, reducing data accuracy.
This issue occurs daily in classrooms and affects the efficiency and integrity of the educational process.

## 3 Impact Area

The system can be used in universities, schools, and training centers.
The main beneficiaries are instructors and administrators, as it saves time and improves accuracy.
Students also benefit from a fair and transparent system.

## 4 Existing solutions

- Manual attendance using paper
- Digital systems requiring manual input
- Card-based or fingerprint systems

## 5 Limitations of Current Solutions

- Time-consuming
- Prone to manipulation (proxy attendance)
- Require continuous human involvement
- Some solutions are costly or complex

## 6 Proposed Solutoin

We propose building a system that uses face recognition to automatically record attendance.
The system captures images of students in the classroom, identifies them using a pre-registered database, and records attendance instantly.
This improves accuracy and reduces manual effort.

## 7 Scope

**Included in MVP:**

- Student registration (images + data)
- Face recognition via camera
- Automatic attendance recording
- Simple dashboard to view attendance

**Not included:**

- Full mobile application
- Large-scale user support
- Integration with external university systems

## 8 Risks

- Accuracy issues under different lighting conditions
- Need for sufficient training data
- Hardware/camera limitations
- Limited development time

## 9 Success Metrics + MVP

**Success Metrics:**

- High recognition accuracy (e.g., 90%+)
- Reduced time for attendance tracking
- Ease of use

**MVP Version 1:**

- Simple web application
- Student registration page
- Camera interface for attendance
- Dashboard displaying attendance records
