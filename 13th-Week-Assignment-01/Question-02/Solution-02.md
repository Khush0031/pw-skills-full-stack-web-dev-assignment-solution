# Solution-01.

A program that grades students based on their marks

```JavaScript
    function gradeStudent(marks) {
    let grade;

    if (marks > 90) {
        grade = 'A';
    } else if (marks >= 70 && marks <= 90) {
        grade = 'B';
    } else if (marks >= 50 && marks <= 70) {
        grade = 'C';
    } else {
        grade = 'F';
    }

    return grade;
}

// Example usage:
let studentMarks = 85;
console.log(`The student's grade is: ${gradeStudent(studentMarks)}`);

studentMarks = 45;
console.log(`The student's grade is: ${gradeStudent(studentMarks)}`);

studentMarks = 75;
console.log(`The student's grade is: ${gradeStudent(studentMarks)}`);

studentMarks = 95;
console.log(`The student's grade is: ${gradeStudent(studentMarks)}`);

```