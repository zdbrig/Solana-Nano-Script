
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
