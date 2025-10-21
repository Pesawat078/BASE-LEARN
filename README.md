### 1. Create the File in Remix

1.  Go to the GitHub link you provided
2.  Copy all the code from that page.
3.  In Remix, create a **new file** (click the "Create New File" icon).
4.  Name this new file.
    *(It is important to add the `.sol` extension so Remix knows it's a Solidity file).*
5.  Paste the code into this new `Arrays.sol` file.

---

### 2. Compile the Contract

1.  Go to the "Solidity Compiler" tab.
2.  The code uses `pragma solidity ^0.8.20;`, so make sure a compiler version like `0.8.20` (or newer) is selected.
3.  Click the **Compile** button.
4.  Look for the green checkmark to confirm it compiled successfully.

---

### 3. Deploy the Contract

1.  Go to the "Deploy & Run Transactions" tab.
2.  Keep the **Remix VM (London)** environment.
3.  In the **CONTRACT** dropdown, select `.sol`.
4.  Click the orange **Deploy** button.
5.  You will see the new contract appear under "Deployed Contracts."

---

* **To remove a number (e.g., the 2nd one):**
    1.  Find the **remove** function.
    2.  Enter `1` (to remove the item at index 1).
    3.  Click **transact**.
    4.  If you call **getNumbers** again, the array will now be `[25, 50]`.
