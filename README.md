## ✅ Task 1: Simple Storage Smart Contract

### 💡 Description

This smart contract stores an integer value on the blockchain and allows users to increment and decrement the value. The stored value can be accessed publicly.

---

### ⚙️ Features

* Stores an integer value
* Increment function to increase the value
* Decrement function to decrease the value
* Public variable to read the value

---

### 🧾 Smart Contract Code

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract SimpleStorage {

    int public value;

    function increment() public {
        value += 1;
    }

    function decrement() public {
        value -= 1;
    }
}
```

---

### 🧪 How to Run

1. Open Remix IDE
2. Create a file named SimpleStorage.sol
3. Paste the code and compile
4. Deploy the contract
5. Use the functions:

   * Click increment to increase value
   * Click decrement to decrease value
   * Click value to view current number

---

### 📌 Example

Initial value:

```
0
```

After increment:

```
1
```

After decrement:

```
0
```

---

### 🎯 Outcome

The contract was successfully compiled, deployed, and tested in Remix IDE. The value updated correctly using increment and decrement functions.
# CodeAlpha_SimpleStorage
