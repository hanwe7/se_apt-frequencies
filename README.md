# se_apt-frequencies
Radio frequencies for Swedish airports in *.cup file format. The intended use case is a database for the LX9000 gliding instrument connected to a radio with a radio bridge so that the correct radio frequency can be selected rapidly from the "nearest airport list" in the LX9000.

The database started with OpenAip daily export of Swedish airports 2022-08-08, accessed 2022-08-09 08:00 UTC.
https://storage.googleapis.com/29f98e10-a489-4c82-ae5e-489dbcd4912f/se_apt.cup

Data for each airport is manually verified against Swedish AIP chapter AD 1.1, AIRAC AMDT 4/2022, 16 JUN 2022, accessed 2022-08-09.
https://aro.lfv.se/Editorial/View/IAIP

Each airport with verified data is marked in the comments section as follows:
"NN YYMMDD", e.g. "HW 220809"
where "NN" is the initials of the checker,
"YYMMDD" is the year, month and date when the check was performed.

Additionaly, radio frequencies for Class G airspace in some sectors of "Sweden Control" are added, according to Swedish AIP chapter ENR 6.3-3, COM FREQ ACC Below FL 245/285, AIRAC AMDT 4/2022, 16 JUN 2022, accessed 2022-08-09. These radio frequencies are given an approximate coordinate roughly in the middle of the actual sector and given an appropriate name as follows:

Sector      | Designation
---         | ---
ESMM L      | SE-CTRL_S-Skåne
ESMM K      | SE-CTRL_SW-Småland
ESMM 4      | SE-CTRL_Bohuslän-Dalsland
ESMM 5      | SE-CTRL_Västergötland
ESOS 1:1-3  | SE-CTRL_N-Småland
ESOS 9:1-2  | SE-CTRL_E-Småland

The cup file adheres to [2022_SeeYou_CUP_file_format.pdf](https://github.com/hanwe7/se_apt-frequencies/blob/1d61ece9c515cba8cf2c339ae16851a2997f4c79/2022_SeeYou_CUP_file_format.pdf).
