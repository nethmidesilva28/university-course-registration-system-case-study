# Acceptance Criteria

## US-02: Register for Courses Online

### Given
The student is logged into the system.

### When
The student selects an available course and submits registration.

### Then
The system shall successfully enroll the student and display a confirmation message.

---

## US-03: View Timetable

### Given
The student has registered for courses.

### When
The student accesses the timetable page.

### Then
The system shall display all registered classes in timetable format.

---

## US-05: Review Student Registrations

### Given
A registration request is pending approval.

### When
The academic advisor accesses the approval dashboard.

### Then
The system shall display the student's registration details and available actions.

---

## US-06: Approve Registration

### Given
A registration request is under review.

### When
The advisor selects "Approve".

### Then
The system shall update the registration status to Approved and notify the student.
