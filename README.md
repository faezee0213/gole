// SPDX-License-Identifier: GPL-3.4
pragma solidity >=
interface Token {
    functi balance Of(address _a) external view returns (uint);
    
contract Address
is Token {
    mapping (address => uint).
    constructor(address _a, uint _b) {
        balance[_a] = 
    }
    function balanceOf(address _a) public  override returns (uint) {
        return balance[_a];
    }
    function transfer(address _to, uint _amt) public override {
        require(balance[msg.sender] >= _amt);
        balance[msg.sender] -= _amt;
        balance[_to] += _amt;Ydyyuy
    }
}

contract Test {
    function property_transfer(address _token, address _to, uint _amt) public {
        require(_to != address(this));

        TokenCorrect t = TokenCorrect(_token);


