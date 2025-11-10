c++

Linting tools: clang-tidy, cpplint, IntelliSense Code Linter, Vera++, cpp-linter, Cppcheck.

Testing tools: 

&nbsp;	Unit tests: Google Test, Catch2, Boost.Test, Microsoft Unit Testing Framework.

&nbsp;	Integration and End-to-End Testing: CTest, Qt Test. 

&nbsp;	Sanitizers: AddressSanitizer, ThreadSanitizer, UndefinedBehaviorSanitizer.

&nbsp;	Others: Valgrind, ZeroErr.

Building tools:

&nbsp;	Compilers: Microsoft Visual C++, GNU Compiler Collection, Clang, Intel C++ Compiler, Keil, MPLAB XC++.

&nbsp;	Build Systems (tools that manage the compilation process, handling dependencies, compilers and linkers): CMake, MSBuild, Ninja, Make.



Jenkins and GitHub Actions alternatives: Azure DevOps Server, CircleCI, GitLab, 

TeamCity, AWS CodePipeline, Bamboo, Bitbucket Pipelines.



Self-hosted setup would be a better choice for you if you have a bigger project, where you need more control over the setup and have resources nessesary to maintain and manage it, or if you need some specific tools e.g. a graphics card to run tests. 

Cloud-based setup would be better for a smaller project where you don't need any advanced options and don't have any special requierments. It lets you not worry about implementing the setup thus reducing the cost of production, provides accessibility from anywhere in the world. It also gives you better security as large cloud providers often have better security measures than a smaller business could implement on its own. 

