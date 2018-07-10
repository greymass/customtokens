# customtokens
Custom Token tracking smart contract for EOS

# How to build

`eosiocpp -g customtokens.abi customtokens.cpp && eosiocpp -o customtokens.wast customtokens.cpp`

# How to deploy

`cleos set contract customtokens customtokens -p customtokens@active`


# Usage

### Add to the table

`cleos push action customtokens set '[1, "solveforanyx", "eosio.token", "0.0000 EOS"]' -p solveforanyx@active`

### Remove from the table

`cleos push action customtokens del '[1]' -p solveforanyx@active`

### View the table

`cleos get table customtokens customtokens tokens`
