# AgriUT
Celo Project
This is a standard ERC20 token with certain specific additional functionality.
Since all transfer done within the Agrigata are paid for by Agrigata itself, we added ability for a account to indicate it wants to be managed by the main account.
This supports a new transfer command which is always executed by main wallet, to transfer amounts between managed accounts.
For managed accounts, the users never have direct access or knowledge of the accounts, but have to go via the Agrigata website.
If they transfer the tokens outside of the Agrigata network, it should function as a normal ERC token.

We also added ability to freeze accounts.stefan