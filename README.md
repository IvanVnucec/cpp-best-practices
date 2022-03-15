# C/C++ Coding Standards and Best Practices

## About
This repo contains C/C++ tools, coding standards and best practices with which I've encountered over the years.

## List
### Tools
* [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint)
    - An automated checker to make sure a C++ file follows [Google's C++ style guide](https://github.com/google/styleguide)
* [ninja](https://ninja-build.org/)
    - Small build system with a focus on speed
    - Supports [CMake's](https://cmake.org/) Ninja backend
* [Cppcheck](https://cppcheck.sourceforge.io/)
    - Static analysis
    - [Misra rule](https://www.perforce.com/resources/qac/misra-c-cpp) texts
    - Open source
* [clang-format](https://clang.llvm.org/docs/ClangFormat.html)
    - C++ code formatter
    - Can be implemented in the Build server, [Link](https://embeddedartistry.com/blog/2017/10/30/clang-format-wrapper-script-examples/)
* [Clang indexer](https://clang.llvm.org/doxygen/group__CINDEX.html)
    - Parse source code into an [abstract syntax tree (AST)](https://en.wikipedia.org/wiki/Abstract_syntax_tree)
    - [Python bindings](https://pypi.org/project/libclang/)
* [GoogleTest](https://github.com/google/googletest)
    - Google’s C++ testing and mocking framework.
* [grep.app](https://grep.app/)
    - Search across a half million git repos
    - Very fast
* [Valgrind](https://valgrind.org/docs/manual/quick-start.html)
    - Number of debugging and profiling tools
    - Detects memory-related errors common in C/C++
* [Ditto](https://ditto-cp.sourceforge.io/)
    - Windows Clipboard manager
    - Helps with copy-paste-ing code
* [Everything](https://www.voidtools.com/)
    - Locate files and folders by name instantly
* [Compiler Explorer](https://godbolt.org/)
    - Lets you type code in one window and see the results of its compilation in another window

### Knowledge base
* [Interrupt blog](https://interrupt.memfault.com/blog/)
    - Blog about embedded C/C++ programming
* [Feabhas blog](https://blog.feabhas.com/)
    - Blog about developing software for real-time and embedded systems
* [Learn C++](https://www.learncpp.com/)
    - Website devoted to teaching you how to program in C++
* [Software Engineering at Google](https://www.oreilly.com/library/view/software-engineering-at/9781492082781/)
    - Book about Google Software engineering principles with designing, architecting, writing, and maintaining code.
* [Handbook of Data Structures and Applications](https://www.oreilly.com/library/view/handbook-of-data/9781351645645/)
    - Discussion of well-known classes of data structures: Priority Queues, Dictionary Structures and Multidimensional structures. 
    - Mechanisms and tools that were developed to facilitate the use of data structures in real programs. 
    - Examination of the applications of data structures

### Best practices
* [C/C++ Google Style Guides](https://google.github.io/styleguide/cppguide.html)
    - Most open-source projects developed by Google conform to the requirements in this guide.
* [cppbestpractices](https://lefticus.gitbooks.io/cpp-best-practices/content/)
    - Collaborative Collection of C++ Best Practices
* [C++ (and Rust, embedded, ...) Talks List](https://wovo.github.io/ctl/)
    - A list of talks about C++, Rust, embedded and related subjects compiled from youtube playlists
    - WARNING: Contains a lot of talks
