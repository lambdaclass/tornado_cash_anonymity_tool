# Anonymity Research Tools for TCash Users

This is the public repository for the Anonymity Research Tools for Tornado Cash users. The final objective of the projected research and proposed tools is to help protect the privacy of TCash users.
The development of tools to protect anonymity must be focused around the different kinds of reveals that privacy perpetrators exploit. For this, our team will research and identify many common reveals using data science and data engineering techniques in order to warn the Tornado Cash user.

# The Problem
In the traditional financial system, bank accounts are publicly linked to a natural person. This means that given a bank account, one can directly reach its owner. However, banks keep all transactions on that account privately.

In most blockchain systems, transaction history is completely public. This means that you can track all the transactions made up to the beginning, given a wallet address.
In principle, this is not a problem because no personal data is needed to create a wallet. Thus, having access to the transactions that an account has made does not compromise the user’s privacy.
Nevertheless, it can be easy to figure out the owner of a wallet’s address in some cases. If the individual is identified, all transactions made by that person could be easily traced, seriously compromising the privacy of the user’s finances.

Tornado Cash is a technology conceived to handle this problem. In Tornado’s own words:
“Tornado Cash improves transaction privacy by breaking the on-chain link between source and destination addresses. It uses a smart contract that accepts ETH & other tokens deposits from one address and enables their withdrawal from a different address.”

But what happens if a user deposits from an account and withdraws using the same account? What if they withdraw using an account that has a long transaction history with the account that made the deposit? These are some of the most common reveals and privacy threa
