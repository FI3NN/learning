Chapter 1
- 16 digit numbers = Zombie's DNA.
- Every two digits map to a trait.
- Different formulas for each digit pair translation allows reduction in variation. i.e. 7 head types by doing "digits % 7 + 1"

Chapter 2
- All solidity code should start with a 'version pragma'. This identifies the version of the Solidity compiler which should be used for this code, preventing any future changes to the compiler from breaking this code.
- To start a new project, write:

pragma solidity >=0.5.0 <0.6.0;

contract HelloWorld {

}

Chapter 3
- uint = unsigned integer = positive integer = uint256
- you can declare unsigned integers with less bits i.e. uint8, uint16, uint32

Chapter 4
- + addition
- - subtraction
- * mulptiplication
- / division
- % remainder
- ** exponential

Chapter 5
- structs

Chapter 6
- arrays
- fixed arrays = uint[length of uint array] ArrayName OR string[length of string array] ArrayName
- dynamic array = uint[] OR string[]
- array of structs = Zombie[] zombies;
- arrays can also be made public = Zombie[] public zombies;

Chapter 7 
- functions
- can be made public
- for data types including structs, mappings, arrays and strings, the memory keyword must be used to ensure that the function does not manipulate the original variable

Chapter 8
- arrays / structs can be added to using nameOfArray.push(newArrayItem)

Chapter 9
- private functions are named like this: _nameOfFunction
- they also use the private keyword instead of public

Chapter 10
- functions which do not modify any values are known as 'view' functions
- functions which do not access any data in the app are known as 'pure' functions
- both should be labelled with such keywords appropriately

Chapter 11
- keccak256(abi.encodePacked(string)) allows us to get a random 256-bit hexidecimal number
- we can typecast. For example, here's how we'd typecast a uint to a uint8... unit8(nameOfUintVariable)

Chapter 14
- 


