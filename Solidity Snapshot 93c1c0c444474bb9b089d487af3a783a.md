# Solidity Snapshot

1. First We define the public variables
- employee _one
- employee _two
- employee _3
1. Then we created a constructor that accepts these functions
2. We then create the balance function that returns the contracts current balance. This will always return zero because we will return the remained to sender
3. Next, we created the deposit function. This splits the payments evenly between the three employee's in this contract.
4. To deal with the remained we take the msg.value and subtract the amount * 3.
5. Finally, we create a callback function to handle errors and make sure that the deposit function executes properly.

![Untitled](Solidity%20Snapshot%2093c1c0c444474bb9b089d487af3a783a/Untitled.png)

![Untitled](Solidity%20Snapshot%2093c1c0c444474bb9b089d487af3a783a/Untitled%201.png)