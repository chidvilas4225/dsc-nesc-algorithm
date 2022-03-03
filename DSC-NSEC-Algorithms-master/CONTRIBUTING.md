# Contribution Guidelines

## Before Contributing
Welcome to [DSC NSEC Algorithms](https://github.com/dscnsec/DSC-NSEC-Algorithms)! Before submitting pull requests, please make sure that you have 
**read the whole guidelines**. If you have any doubts about this contribution guide, please open 
[an issue](https://github.com/dscnsec/DSC-NSEC-Algorithms/issues/new/choose) and clearly state your concerns.

## Contributing

### Contributor
We are very happy that you consider implementing algorithms and data structures for others! This repository is referred to and used by many learners. Being one of our contributors, you agree and confirm that:
- You did your own work.
    - No plagiarism allowed.  Any plagiarized work will not be merged.
- Your work will be distributed under [MIT License](License) once your pull request has been merged.
- You submitted work fulfils or mostly fulfils our styles and standards.

**New implementation** New implementation are welcome!

**Improving comments** in existing algorithms are much appreciated.

**Issues** Please avoid opening issues asking to be "assigned” to a particular algorithm.  This merely creates unnecessary noise for maintainers.  Instead, please submit your implementation in a pull request and it will be evaluated by project maintainers.

### Making Changes

#### Code
- Please use the directory structure of the repository.
- File extension for code should be *.cpp.
- Please use **bits/stdc++.h**.
- If an implementation of the algorithm already exists, please refer to the [file-name section below](#new-file-name-guidelines).
- You can suggest reasonable changes to existing algorithms.
- Strictly use snake_case (underscore_separated) in filenames.
- If you have added or modified code, please make sure the code compiles before submitting.
- **Be consistent in use of these guidelines.**

#### Documentation
- Make sure you put useful comments in your code.
- Please avoid creating new directories if at all possible. Try to fit your work into the existing directory structure. 
- Do not update README.md along with other changes, first create an issue and then link to that issue in your pull request to suggest specific changes required to README.md

#### Typical structure of a program:
```cpp
/**
 * @file 
 * @brief Add one line description here
 * @details 
 * This is a multi line
 * description containing links, references,
 * math equations, etc
 * @author [Name](https://github.com/handle)
 */

#include <bits/stdc++.h>
using namespace std;

datatype solve() {
  //write your code here
}
// Main function
int main() {
  int t;
  cin>>t;
  while(t--) {
    solve();
  }
  return 0;
}
```
##### Linked List
````cpp
/**
 * @file 
 * @brief Add one line description here
 * @details 
 * This is a multi line
 * description containing links, references,
 * math equations, etc
 * @author [Name](https://github.com/handle)
 */
 
#include <bits/stdc++.h> 
using namespace std; 

class Node { 
public: 
    // val is the key or the value that 
    // has to be added to the data part 
    int val; 
    Node* next; 
}; 

//Main function  
int main() 
{ 
    //write your code here,
    //including forming linked list
    // and taking input
    return 0;
} 
````

##### Binary Tree
````cpp
/**
 * @file 
 * @brief Add one line description here
 * @details 
 * This is a multi line
 * description containing links, references,
 * math equations, etc
 * @author [Name](https://github.com/handle)
 */
 
#include <bits/stdc++.h> 
using namespace std; 

struct Node { 
    int data; 
    struct Node* left; 
    struct Node* right;   
    // val is the key or the value that 
    // has to be added to the data part 
    Node(int val) 
    { 
        data = val; 
        // Left and right child for node 
        // will be initialized to null 
        left = NULL; 
        right = NULL; 
    } 
}; 
//Main function  
int main() 
{ 
    //write your code here,
    //including forming binary tree
    // and taking input
    return 0;
} 
````

#### New File Name guidelines
- Use lowercase words with ``"_"`` as separator
- For instance
```
MyNewCppClass.CPP       is incorrect
my_new_cpp_class.cpp    is correct format
```
#### Commit Guidelines
- It is recommended to keep your changes grouped logically within individual commits. Maintainers find it easier to understand changes that are logically spilt across multiple commits.  Try to modify just one or two files in the same directory.  Pull requests that span multiple directories are often rejected.

#### PR Guidelines
Make sure your PR checks all the below points.

- [ ] Code is added in right directory(Folder).
- [ ] Brief Description of Solution is given.
- [ ] Time and Space Complexity is mentioned
- [ ] Code is well indented.
- [ ] Comments are clearly written wherever necessary
- [ ] Code is successfully compiled and passes all test cases.


**Happy Coding!**
