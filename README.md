### Lottery Solidity Smart Contract

#### Description
This is a simple lottery smart contract that allows users to buy tickets and the winner to claim the prize.//SPDX-License-Identifier: GPL-3.0 

#### How it works
  1. The contract picks the winner by generating a random number between 0 and the number of tickets sold.
    2. Resets the contract after the winner has claimed the prize. And allows users to buy tickets again.

    3. returns Contract balance.

    4. Sets up the contract admin.

    5. Sends the prize to the winner.

    6. Holds on to 10% of the prize as a fee.

    7. Generates a random number between 0 and the number of tickets sold.

    8. Admin not allowed to buy tickets.