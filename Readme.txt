This project download the dataset of NYC Transit data of 2021 and 2022. This dset consists of tickets issued in the city: the type of the ticket, the date issued, the street name, region, 
the model andcolor of the car ticketed, etc.

All the codes should be run in Linux Shell of GCP virtual machine. The shell script files consolidates the codes that should be run

1) Run the python code Dataset_saving.py: download the dataset from NYCTransit API, in Json Format.
2) Run the shell script files: bash testweek.sh -> analyse the days of the week where most tickets are issued
bash testtype.sh -> analyse the type of cars with most tickets issued
bash testwhere.sh -> analyse the streets with most tickets issued
