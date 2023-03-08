Assuming you are running your DERO wallet with these parameters:
```
--remote --wallet-file=wallet --rpc-server --rpc-bind=127.0.0.1:10103 --password=password
```
You can conduct a trial balance on your wallet's funds.

To download the program, first:
```
wget https://raw.githubusercontent.com/secretnamebasis/dero-trial-balance/main/scan
```
Then mark the file as executable
```
chmod +x scan
```
Then execute `scan`
```
./scan
```

Honestly, a thing of beauty 
```
./scan
Inflows:        4511828
Coinbase:       154029
Income:         4665857

Outflows:       3551679
Fees:           67431
Expenses        3619110

Subtotal:       1046747

Balance:        1046747

Diff:           0
```
