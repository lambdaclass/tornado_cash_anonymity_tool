# Figures documentation

## Heuristic 1: Address reuse
- addresscount2depositcount_hist.png:
    For each possible value of the number of linked deposits, counts how many addresses have those linked deposits. Depending on the timestamp
    that the address made the withdrawal, different amount of deposits will appear linked. For this plot, we are taking the maximum number of
    linked deposits for every address. 

- withdrawcount2depositcount_hist.png:
    For each possible value of the number of linked deposits, counts how many withdraw transactions have those linked deposits. Same as above,
    but in this case we are focusing on the transaction rather than the address. If one address made more than 1 withdrawal, then it will 
    appear more than one time in this would plot.

## Heuristic 2: Same gas price
- linked_transaction_pie_charts.png:
    Pie charts of linked deposit transactions by pool.
    Left: Ether pools.
    Right: Token pools.

## Heuristic 3: Outside TCash intereactions
- nlinkeddeposits_vs_nwithdraws_per_address.png
    Scatter plot. Every point represents an address.
    X axis -> Number of withdraws of that address.
    Y axis -> Number of linked deposits to that address by this heuristic.

- withdraw2daddr_hist.png:
    For every possible number of linked deposit addresses, count how many withdraw txs have that number of linked deposits addresses.

- withdraw2deposits_hist.png:
    For every possible number of linked deposit txs, count how many withdraw txs have that number of linked txs.   
    
- waddr2deposits_hist.png:
    For every possible number of linked deposit txs, count how many withdraw addresses have that number of linked txs.

- h3_compromised_vs_uncompromised.png:
    Absolute value of compromised vs Uncompromised deposit transactions for every pool.
    Left: Ether pools
    Right: Token pools

- h3_compromised_vs_uncompromised_rates.png:
    Rates of compromised vs uncompromised deposit transactions for every pool
    Left: Ether pools
    Right: Token pools

- outside_tcash_recurrent_interactions.png:
    For every possible number of pair of addresses that interacted with TCash, count how many interactions were made, i.e., how
    recurrent the interactions are.  


## Heuristic 5: Careless Anonimity Mining
- linked_withdraws_by_pool_pie.png:
    Pie chart of linked transactions in each pool.

- notes_count2blocks_hist.png:
    For every possible number of blocks a note is inside TCash, count how many notes have been in inside by each block.

