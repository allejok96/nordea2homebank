# Nordea2HomeBank

This very simple bash script uses sed to convert CSV files downloaded from [Nordea.se](https://www.nordea.se/) to a format that can be imported into [HomeBank](http://homebank.free.fr/).

```sh
# Download
git clone https://github.com/allejok96/nordea2homebank.git
cd nordea2homebank && chmod +x n2hb

# Run
./n2hb FILE.csv

# The new file will be saved as FILE_homebank.csv
```
