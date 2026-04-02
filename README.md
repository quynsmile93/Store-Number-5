# Store-Number-5
Store Number.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract StoreNumber {
    uint public number;

    function setNumber(uint _num) public {
        number = _num;
    }
}
