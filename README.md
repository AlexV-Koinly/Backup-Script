1. Generate a single "Transaction History" report from adminCP, make sure to include all the years that has transactions.

2. Place the report in the "backup_script" folder where the "backup_script.py" file is.

3. Run the "backup_script.py" and follow the prompts.

4. Open the "backup" folder to find the generated files.

Notes:
You'll need to install python 3 to run the script.

I suggest renaming the "Transaction History" report to something shorter because you will have to type in the name of the file when running the script.

If the user has transactions labeled "Sent to/received from pool" then the script will create CSV files for the "pool" wallets that are normally hidden. So there might be more CSV files generated than the number of wallets that it says the user has synced on Koinly.
Those files can just be uploaded to custom wallets that will act as the hidden "pool" wallets.
