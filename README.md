# CheckEmptyMessage.sol
CheckEmptyMessage.sol6
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract CheckEmptyMessage {
    string public message;
    function isEmpty() public view returns(bool){
        return bytes(message).length == 0;
    }
}
Add array and mapping examples
Update contract version
Improve variable naming
Add event for tracking changes
Simplify function logic
Update function logic
Fix edge scenario
