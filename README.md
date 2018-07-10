# customtokens
Custom Token tracking smart contract for EOS

# How to build

`eosiocpp -g customtokens.abi customtokens.cpp && eosiocpp -o customtokens.wast customtokens.cpp`

# How to deploy

`cleos set contract customtokens customtokens -p customtokens@active`
