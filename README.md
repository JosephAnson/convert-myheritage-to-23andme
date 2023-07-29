# Convert myheritage to 23andme

This is a node script to convert a myheritage DNA file to a 23andme DNA file.

## Getting Started

First you will need to download your raw DNA file from myheritage. Place the file in the same directory as the script.

After you can run the script with the following command:

```bash
npm run convert
```

### How it works

This script will convert the csv file name MyHeritage_raw_dna_data.csv you place in the same directory. It will prompt you for your first and last name when running the script to create the file name and comment within the file.

It will then create a 23andme DNA file in the same directory as your myheritage DNA file.
