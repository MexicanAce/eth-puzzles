## 🔢 Prime Wallet

In the world of cryptography, prime numbers are the building blocks of
encryption.

Your mission is to generate a Prime Wallet™ and deploy the following contract
with it:

```solidity
contract Greeter {
    address public owner;

    constructor() {
        owner = msg.sender;
    }

    function greet() public pure returns (string memory) {
        return "Hello, World!";
    }
}
```

Submit the address of the contract as your answer.

### What is a Prime Wallet™?

A Prime Wallet™ is a wallet with a public address such that if you remove all
the letters in the address, you are left with a prime number.

### Example

1. Given a wallet address: `0x123456789ABCDEF67890ABCDEF78901234567890`
2. Remove all the letters: `0123456789689078901234567890`
3. Check if the number is prime: `0123456789689078901234567890` is not prime!
