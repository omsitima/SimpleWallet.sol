# SimpleWallet.sol
How to deploy a contract on Base Chain SimpleWallet.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SimpleWallet {
    function deposit() public payable {}

    function getBalance() public view returns (uint) {
        return address(this).balance;
    }
}
