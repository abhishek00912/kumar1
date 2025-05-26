📄 Counter Smart Contract
This is a basic smart contract written in Solidity that allows anyone to increment, decrement, reset, and view a counter value.

🧾 Contract Overview
solidity
Copy
Edit
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract Counter {
    int256 private count;

    function getCount() public view returns (int256) { ... }
    function increment() public { ... }
    function decrement() public { ... }
    function reset() public { ... }
}
⚙️ Functions
Function	Description	Access
getCount()	Returns the current value of the counter.	public view
increment()	Increases the counter by 1.	public
decrement()	Decreases the counter by 1.	public
reset()	Resets the counter value to 0.	public

✅ Features
Uses int256 so it can handle both positive and negative values.

All functions are publicly accessible (no restrictions).

Simple and easy to test on Remix, Hardhat, or Truffle.

🚀 Getting Started
Open Remix IDE

Create a new file named Counter.sol and paste the contract code.

Compile the contract with Solidity version ^0.8.0.

Deploy it to the JavaScript VM or your chosen environment.

Interact with the contract using the UI provided.

📌 Example Usage
Click increment() → Counter becomes 1

Click decrement() → Counter becomes 0

Click decrement() again → Counter becomes -1

Click reset() → Counter becomes 0

🛡️ License
This project is licensed under the MIT License.

Contact address 0xaa4baff860e34ab7273eda99891f4512b710b821
