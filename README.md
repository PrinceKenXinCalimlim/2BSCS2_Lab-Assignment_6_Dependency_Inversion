# 2BSCS2_Lab-Assignment_6_Dependency_Inversion

The NEU Library offers a variety of resources, including books, theses, capstones, internet access, journals, and newspapers.

Currently, the Student object has methods like borrowBook() and borrowJournal() with a parameter of title, which directly depends on specific resource types.

To adhere to the Dependency Inversion Principle (DIP) and ensure flexibility for future changes (such as introducing audio books or e-journals), we need to refactor the program while maintaining SOLID principles. The goal is to create a robust system that can seamlessly accommodate new resource types in the future.![UML_Class_Diagram]

Your solution should not violate other SOLID principles.

Create a repository in your GitHub account. Put your solution there. The readme file must include the problem statement, and UML Class Diagram of the proposed solution.

Make sure you have a TestProgram that will validate the proposed refactored codes.


![UML_Class_Diagram]!![UML DIAGRAM](https://github.com/PrinceKenXinCalimlim/2BSCS2_Lab-Assignment_6_Dependency_Inversion/assets/152839644/b4ace8ee-15ea-4cc2-9048-192b3c1c7bc3)
