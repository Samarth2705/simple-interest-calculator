Script File (`simple-interest.sh`)
Create a file named `simple-interest.sh` and paste the following executable shell script:

```bash
#!/bin/bash
# Do not change this script name.
# This script calculates simple interest given principal, annual rate of interest and time period in years.
# Do not use this in production. Sample code for demonstration purposes only.

# Author: IBM / Coursera Learner
# Additional Authors:
# <your-github-username>

# Input:
# p, principal amount
# t, time period in years
# r, annual rate of interest

# Output:
# simple interest = p*t*r

echo "Enter the principal:"
read p
echo "Enter rate of interest per year:"
read r
echo "Enter time period in years:"
read t

s=`expr $p \* $t \* $r / 100`
echo "The simple interest is: "
echo $s
