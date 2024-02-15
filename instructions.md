
# NanoScript Instruction Set and Fuel Costs

This table outlines the available instructions in NanoScript along with their respective fuel costs. These instructions enable developers to build efficient and effective DeFi applications on the Solana blockchain.


| Instruction Name        | Description                                       | Fuel Cost |
|-------------------------|---------------------------------------------------|-----------|
| LOAD                    | Load data from the stack                          | 1         |
| STORE                   | Store data to the stack                           | 1         |
| ADD                     | Add two numbers                                   | 2         |
| SUB                     | Subtract two numbers                              | 2         |
| MUL                     | Multiply two numbers                              | 3         |
| DIV                     | Divide two numbers                                | 3         |
| JUMP                    | Jump to a different instruction in the script     | 5         |
| JUMPIF                  | Conditional jump based on the top stack value     | 5         |
| EQ                      | Check if two values are equal                     | 1         |
| NEQ                     | Check if two values are not equal                 | 1         |
| LT                      | Check if one value is less than another           | 1         |
| GT                      | Check if one value is greater than another        | 1         |
| AND                     | Logical AND of two values                         | 1         |
| OR                      | Logical OR of two values                          | 1         |
| XOR                     | Logical XOR of two values                         | 1         |
| NOT                     | Logical NOT of a single value                     | 1         |
| CALL                    | Call another script                               | 10        |
| RETURN                  | Return from a script                              | 1         |
| PUSH                    | Push a value onto the stack                       | 1         |
| POP                     | Pop a value from the stack                        | 1         |
| LIQUIDITY_ADD           | Add liquidity to a pool                           | 20        |
| LIQUIDITY_REMOVE        | Remove liquidity from a pool                      | 20        |
| ORDER_EXECUTE           | Execute an order in the exchange                  | 50        |
| HASH                    | Compute a hash of data                            | 10        |
| VERIFY_SIG              | Verify a cryptographic signature                  | 20        |
| ENCRYPT                 | Encrypt data                                      | 15        |
| DECRYPT                 | Decrypt data                                      | 15        |
| LOG_EVENT               | Log an event to the blockchain                    | 5         |
| HANDLE_ERROR            | Handle an error in execution                      | 5         |
| MEMORY_ALLOCATE         | Allocate memory for dynamic data                  | 8         |
| MEMORY_FREE             | Free allocated memory                             | 8         |
| NETWORK_REQUEST         | Make a network request for off-chain data         | 100       |
| VERIFY_HASH             | Verify the hash of data matches a given hash      | 10        |
| READ_EXTERNAL_DATA      | Read data from an external source                 | 25        |
| WRITE_EXTERNAL_DATA     | Write data to an external source                  | 25        |
| TIMESTAMP               | Get the current timestamp                         | 5         |
| RANDOM                  | Generate a random number                          | 5         |
| SIGN_DATA               | Sign data with a private key                      | 20        |
| VERIFY_DATA_SIGNATURE   | Verify the signature of signed data               | 20        |
| CREATE_CONTRACT         | Deploy a new smart contract                       | 100       |
| CALL_CONTRACT           | Call a function of a deployed smart contract      | 20        |
| UPDATE_CONTRACT_STATE   | Update the state of a smart contract              | 30        |
| DESTROY_CONTRACT        | Remove a smart contract from the blockchain       | 50        |
| MERKLE_PROOF            | Verify a Merkle proof                             | 15        |
| ENQUEUE_TRANSACTION     | Enqueue a transaction for later execution         | 10        |
| DEQUEUE_TRANSACTION     | Dequeue a transaction for execution               | 10        |
| PEEK_TRANSACTION        | Peek at the next transaction without dequeuing    | 5         |
| EXECUTE_BATCH           | Execute a batch of instructions atomically        | 50        |
| PAUSE_EXECUTION         | Temporarily pause execution for a specified time  | 10        |
| RESUME_EXECUTION        | Resume execution after a pause                    | 5         |
| VERIFY_ACCOUNT_BALANCE  | Verify the balance of an account meets criteria   | 10        |
| ADJUST_FUEL             | Adjust the fuel cost for subsequent instructions  | 5         |
| SET_PRIORITY            | Set the execution priority of instructions        | 5         |
