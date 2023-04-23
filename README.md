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
    After placing the code, you need to compile it with the solidity compiler. After that click the deploy button and copy the account number but before that click the     total supply to make sure the balance of the account is zero
     
    You need to paste the account and need to paste the mint address and need to input the value. The same will be done with the burn. Next, just copy the account         balance and click the call
    
   ## Autors
   Edgardo L. Delos Angeles
   8214005@ntc.edu.ph
   
   ## License
   This project licensed under the MIT license - see the license.md file for details
   
 
