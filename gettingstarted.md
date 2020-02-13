# This is a comment, it is not read by the bitcoin client application
# On first setting up, after downloading and installing the bitcoin-core client, run the program using the GUI, bitcoin-qt.
# This will automatically set locations for the data (blockchain), wallet, and bitcoin.conf setup file, copied here for your 
# convenience

# Actually click to edit it and you will what markup can do. It makes the github text look large, but in a bitcoin.conf 
# managemnet file , this is all hidden to the bitcoin application

testnet=1
# testnet3, not mainnet (with real money), or regtest (where you are king, banker, and maker of bitcoin)
# regtest=1, to use your imaginary regtest

prune=550
# pruning removes all blocks except the most vital, so you save space

# datadir=/path/to/the/testnet3/folder, or c:/documents and settings/path/to/the/testnet3/folder
# set your data directory above

# hashed with b2sum using b2rsum (recursive hashing)
# the hash format Blake is used, not sha256
# this can help you to ensure that the blockchain you download with bittorrent from us, and use, is the exact same blockchain 
# that we obtain off the bitcoin blockchain. We then pass the command 'prune=550'. This DELETES nearly all the downloaded 
# blockchain, cutting space from 30+GB on the bitcoin testnet blockchain, and providing a blockchain download of 2GB.
# Therefor, we come to the CRUX. Do you TRUST us to not put viruses or spyware in the blockchain files we provide. Do you 
# TRUST us not to rewite the blockchain data provided so, though it appears to be valid and 'work' in the bitcoin app, it will 
# one day copy your WALLET.DAT, and delete it, or send it to us so we can spend all your BITCOIN!

# This is the essence of BITCOIN-SHITSEC, to make an easily downloaded bittorrent and download source, that is convenient, but 
# risks sacrificing security, and therefore seeking to provide more security to reduce risks.

# https://github.com/alex2114/bitcoin-shitsec
# https://archive.org/download/bitcointestnet
# leave me messages on my github, and provide vour contact information if you want a reply

# Download sites: https://archive.org/download/bitcointestnet, the testnet3 files you need are compressed to a large zip file.
# https://archive.org/download/bitcointestnet/bitcointestnet_archive.torrent, or http download from the above site.
# The files are extracted into the folder testnet3 at the source loication (where you want), set the bitcoin.conf file where it  # be read
# When you extract this zip file the two folders can be seeded, using the torrent file at 
# https://github.com/Alex2114/bitcoin-shitsec/blob/master/bitcoin-shitsec.torrent and / or
# https://archive.org/download/bitcointestnet/bitcoin-shitsec.torrent
# IF YOU START DOWNLOADING AND SYNCING THE BITCOIN CLIENT THEN YOU WILL CHANGE HASH DATA. THIS WILL RUIN SYNCHRONIZATION WITH 
# YOUR BITTORRENT CLIENT! SO THE DATA WILL BE DIFFERENT, YOU MAY CORRUPT AND LOSE THE BLOCKCHAIN! DONT SYNC BITCOIN WHILE TRYING # TO TORRENT SEED IT! JUST DONT!

# Are you a testnet faucet?
# Would you like to advertise below?
# We accept donations to our testnet address (so we can send testnet bitcoin to others), as well as real bitcoin
# mainnet, real bitcoin-  1GPVQVvPbD4HwZnUAYzVpR67MMMmu55sdN
# testnet, bitcoin-opoly- 2NEA7PmXbZRd8GjMPfKau2heyiZz5yji7zi

# PLEASE HELP WITH INITIAL SEEDING! THAN YOU! PLEASE HELP WITH INITIAL SEEDING! THAN YOU! PLEASE HELP WITH INITIAL SEEDING! THA
