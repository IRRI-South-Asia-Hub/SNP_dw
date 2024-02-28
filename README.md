# SNP_dw
This is a publicly available open-source python package, which can be used to download genotypic files from snp seek database 

## how to run
The basic steps like downloading Python and an IDE for python can be followed from any tutorial
After we are done with the python and IDE download,we move to the following steps

### Step1:
Open Python IDE and run :

```
pip install Sudip-snpdw

```
make sure we have good internet at each step

### Step2:
Open a new Python file and import the library as shown below
```
from Sudip_snpdw import snp_dw

```

### Step 3:
You must have the gene IDs as shown below in a .txt file

```
LOC_Os01g01010
LOC_Os01g01019
LOC_Os01g01030
LOC_Os01g01040
LOC_Os01g01050
LOC_Os01g01060
```
If yes then run the following code

```
from Sudip_snpdw import snp_dw #skip if it's done already after opening the Python file
snp_dw("D:/IRRI task/100_LOC_IDs.txt") # plseas replace with our own location and file name

```

##### files will automatically start downloading given that  we have google chrome with us
