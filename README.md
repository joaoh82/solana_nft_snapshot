# Solana NFT Snapshot
Takes a Solana NFT holder list based on mint address list.

### How to Use?

1. First go to https://tools.abstratica.art/ and in the wallet address copy and paste you CANDY MACHINE ID that you got from the metaplex create_candy_machine command.

2. Then click download and save the file.

3. Remove the "[" and "]" from the file and save it as "mints.txt"

4. Then run the script with the following command:
```sh
> node .\index.js mints.txt snapshot.txt
```

Voila!
