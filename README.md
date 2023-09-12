# HexAddress-bigquery
Packing https://gist.github.com/Aziz87/bbf95f8525c5302c8c69644a12bc7d72 for use in a BigQuery UDF

### 1. Start an NPM package

```bash
npm init
```

Accept all defaults

### 2. Initialize `HexAddress.js`

From here: https://gist.githubusercontent.com/Aziz87/bbf95f8525c5302c8c69644a12bc7d72/raw/d29ccadaa27382b420ef2662e5632073eb47bc4f/HexAddress.js

### 3. Install `jssha`

```bash
npm i jssha
```

### 4. Make `index.js`

Show it works for this input (`418840e6c55b9ada326d211d818c34a994aeced808`), taken from [tron docs](https://developers.tron.network/docs/account#account-address-format):

```bash
$ node index.js 
TNPeeaaFB7K9cmo4uQpcU32zGK8G1NYqeL
```
