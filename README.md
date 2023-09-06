# Module_18

## PyChain Ledger and Streamlit Interface - README Summary

This README offers a concise overview of the steps required to implement a PyChain ledger and user interface using Streamlit. The goal is to create a blockchain ledger that stores records, validate the blockchain, and showcase it through a user-friendly interface.

### Step 1: Create a Record Data Class

- Define a Python data class named `Record` with structured attributes: `sender`, `receiver`, and `amount`.
- Apply the `@dataclass` decorator to the `Record` class for efficient data management.

### Step 2: Modify the Existing Block Data Class

- Rename the `data` attribute in the `Block` class to `record`.
- Set the data type of the `record` attribute to the previously created `Record` class.

### Step 3: Add Relevant User Inputs to the Streamlit Interface

- Enhance the Streamlit interface to capture user input for `sender`, `receiver`, and `amount` for each transaction.
- Update the "Add Block" button functionality to create a `Block` instance with a `record` attribute containing sender, receiver, and amount values.
- Ensure that the `Block` instance includes `creator_id` and `prev_hash` attributes.

### Step 4: Test the PyChain Ledger by Storing Records

- Run the Streamlit application, allowing users to input sender, receiver, and amount values to store transactions as blocks in the PyChain ledger.
- Verify block contents and hashes using the Streamlit drop-down menu.
- Capture a screenshot of the Streamlit application displaying a blockchain with multiple blocks and include it in the README.md file.

![](Streamlit%20Pic.png)

