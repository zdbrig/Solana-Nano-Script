
# NanoScript Instruction Set and Fuel Costs

This table outlines the available instructions in NanoScript along with their respective fuel costs. These instructions enable developers to build efficient and effective DeFi applications on the Solana blockchain.

| Instruction Name | Description                                    | Fuel Cost |
|------------------|------------------------------------------------|-----------|
| `LOAD`           | Loads a value into the stack.                  | 1         |
| `STORE`          | Stores a value from the stack into memory.     | 2         |
| `ADD`            | Adds two top values from the stack.            | 2         |
| `SUB`            | Subtracts the top stack value from the second. | 2         |
| `MULT`           | Multiplies two top values from the stack.      | 3         |
| `DIV`            | Divides the second top value by the top value. | 3         |
| `JUMP`           | Jumps to a specified instruction.              | 5         |
| `JUMPI`          | Conditional jump based on a flag.              | 5         |
| `EQ`             | Checks if two values are equal.                | 1         |
| `GT`             | Checks if second value is greater than top.    | 1         |
| `LT`             | Checks if second value is less than top.       | 1         |
| `AND`            | Logical AND on top two values.                 | 1         |
| `OR`             | Logical OR on top two values.                  | 1         |
| `NOT`            | Logical NOT on the top value.                  | 1         |
| `CALL`           | Calls another script or function.              | 10        |
| `RETURN`         | Returns from the current script/function.      | 2         |
| `SWAP`           | Swaps tokens according to specified parameters.| 20        |
| `LIQUIDITY_ADD`  | Adds liquidity to a pool.                      | 30        |
| `LIQUIDITY_REMOVE`| Removes liquidity from a pool.                | 30        |
| `ORDER_EXECUTE`  | Executes an order in a decentralized exchange. | 50        |
| `HASH`                    | Compute a hash of data                            | 10        |
| `VERIFY_SIG`              | Verify a cryptographic signature                  | 20        |
| `ENCRYPT`                 | Encrypt data                                      | 15        |
| `DECRYPT`                 | Decrypt data                                      | 15        |
| `LOG_EVENT`               | Log an event to the blockchain                    | 5         |
| `HANDLE_ERROR`            | Handle an error in execution                      | 5         |
| `MEMORY_ALLOCATE`         | Allocate memory for dynamic data                  | 8         |
| `MEMORY_FREE`             | Free allocated memory                             | 8         |
| `NETWORK_REQUEST`         | Make a network request for off-chain data         | 100       |

| `VERIFY_HASH`             | Verify the hash of data matches a given hash      | 10        |
| `READ_EXTERNAL_DATA`      | Read data from an external source                 | 25        |
| `WRITE_EXTERNAL_DATA`     | Write data to an external source                  | 25        |
| `TIMESTAMP`               | Get the current timestamp                         | 5         |
| `RANDOM`                  | Generate a random number                          | 5         |
| `SIGN_DATA`               | Sign data with a private key                      | 20        |
| `VERIFY_DATA_SIGNATURE`   | Verify the signature of signed data               | 20        |
| `CREATE_CONTRACT`         | Deploy a new smart contract                       | 100       |
| `CALL_CONTRACT`           | Call a function of a deployed smart contract      | 20        |
| `UPDATE_CONTRACT_STATE`   | Update the state of a smart contract              | 30        |
| `DESTROY_CONTRACT`        | Remove a smart contract from the blockchain       | 50        |
| `MERKLE_PROOF`            | Verify a Merkle proof                             | 15        |
| `ENQUEUE_TRANSACTION`     | Enqueue a transaction for later execution         | 10        |
| `DEQUEUE_TRANSACTION`     | Dequeue a transaction for execution               | 10        |
| `PEEK_TRANSACTION`        | Peek at the next transaction without dequeuing    | 5         |
| `EXECUTE_BATCH`           | Execute a batch of instructions atomically        | 50        |
| `PAUSE_EXECUTION`         | Temporarily pause execution for a specified time  | 10        |
| `RESUME_EXECUTION`        | Resume execution after a pause                    | 5         |
| `VERIFY_ACCOUNT_BALANCE`  | Verify the balance of an account meets criteria   | 10        |
| `ADJUST_FUEL`             | Adjust the fuel cost for subsequent instructions  | 5         |
| `SET_PRIORITY`            | Set the execution priority of instructions        | 5         |
