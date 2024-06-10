# eth-project
We will create a contract together
Our contract will have public variables that store the details about Our coin (Token Name, Token Abbrv., Total Supply)
Our contract will have a mapping of addresses to balances (address => uint)
We will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the address by that amount.
Our contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.
Lastly, Our burn function should have conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.
