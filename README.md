# Linked-List-Discovery 


## Tasks


1) Create a Linked List with functions to add and remove from the list 

2) Create a Triple Rotate Function which rotates every three elements once to the left

3) Create a reverse function which maintains the pointers correctly for the list

## Getting Started
## Software 
My implementation was fully in C++ and utilized the cmake platform for build automation and testing. The bulk of my algorithms are in my src folder.

## Installation and Usage

1. Clone the repo:
   ```sh
   git clone https://github.com/kazshah23/Linked-List-Discovery.git
   ```
2. Make the `build` directory :
    ```sh
    mkdir build
    ```
3. Change directory into the `build` folder:
    ```sh
    cd build
    ```
4. In the `build` directory, "run cmake .."
   ```sh
   cmake ..
   ```
5. In the `build` directory, run make test && ./test to make sure all tests are passing
   ```sh
    make test && ./test
   ```
6. To see the output and breakdown of the code run make main && ./main  
    ```sh
   make main && ./main
    ```    
## Conclusions
1) Create a Linked List with functions to add and remove from the list 
    - Added an insert front function which added an element to the front of the list 
    - Added an insert back function which added an element to the back of the list 
    - Created destroy function which would deallocate the list memory
    - See './src/List.hpp' function insertFront() and insertBack()
  
 2) Create a Triple Rotate Function which rotates every three elements once to the left
    - Stored the pointers locally in the function
    - Rotated every three elements with leaving the remaining ones untouched 
    - Maintained pointers to the next and previous elements
    - See './src/List.hpp' function triplerotate()
  
 3) Create a reverse function which maintains the pointers correctly for the list
    - Given a start point and an end point, reverse the list from those two specific points
    - See './src/List.hpp' functions reverse() and reverseNth()
 ## What I learned
 - Linked List
 - Reversing Linked Lists
 - Dynamic Programming
 - Pointers and References
 - How to use GDB to detect memory leaks
## Help

Any advise for common problems or issues.


## Authors

Contributors names and contact info

ex. Kazmain Shah
ex. [@kazshah23](kshah228@illinois.edu)
