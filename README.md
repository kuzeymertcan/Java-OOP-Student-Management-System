# Student Management System

This Java program demonstrates an Object-Oriented Programming (OOP) approach for managing different types of students using abstract classes and interfaces.

## Usage

1. Compile the Java files using a Java compiler.
2. Run the `StudentApp` class to see the output.

## Code Structure

- `Student` (abstract class): Represents a generic student with midterm and final scores.
- `ProjectScoreBehaviour`: Interface for students with project scores.
- `ConferenceScoreBehaviour`: Interface for master students with conference scores.
- `ArticleScoreBehaviour`: Interface for PhD students with article scores.
- `BachelorStudent`, `MasterStudent`, `PhDStudent`: Concrete classes implementing specific student types.
- `StudentApp`: Main class for testing and displaying student information.

## Example Output

This is a Bachelour Student with the following academic achievements
ID: 1025727
Midterm Score: 70.0
Final Score: 80.0
Project Score: 20.0
Total Score: 96.0

This is a Master Student with the following academic achievements
ID: 5683429
Midterm Score: 90.0
Final Score: 80.0
Number of Conferences: 2
Conference Score: 10.0
Total Score: 94.0

This is a PhD Student with the following academic achievements
ID: 8976541
Midterm Score: 80.0
Final Score: 70.0
Number of Conferences: 6
Conference Score: 30.0
Number of Articles: 3
Article Score: 24.0
Total Score: 98.0

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
