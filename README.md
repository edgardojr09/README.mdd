FINAL ASSESMENT
Solidity is a conrtract oriented high level programming. The purpose of this contract is to allow us to create new tokens, which can be mindted and burned as needed.

## Description
Solidity contract is a basic implementation of a token contract called SolidityToken it allows to creation and distruction of the tokens through the mind and burn functionn.

## Getting Started
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the following code into the file:

pragma solidity 0.8.18;

/*

contract MyToken {

    string public tokenName = "mark";
    string public tokenAbbrv = "nabi";
    uint public totalSupply = 0;

    mapping(address => uint) public balances;

    function mint (address _address, uint _value) public {
        totalSupply += _value;
        balances [_address] += _value;
    }

    function burn (address _address, uint _value) public {
        if (balances[_address] >= _value) {
            totalSupply -= _value;
            balances[_address] -= _value;
        }
    }
}
