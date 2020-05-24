## dir2sh - Converts a directory to self extractable compressed script 

This linux/mac utility converts a directory to self extractable script.

## How it works?

   1. Given input directory ( IN  is converted to a tar.gz file ( IN.tar.gz ).
   2. The tar.gz file (IN.tar.gz) is then embedded in to a bash script ( OUT.tar.sh ) with self extraction feature.
   3. This self extractable tar script ( OUT.tar.sh ) can be transported to any linux computer/device and extracted. 

## How to extract directory(IN) from the tar script (OUT.tar.sh)  
   
   1. Just execute "./OUT.tar.sh"
   2. You will find directory (IN) in the current working directory.

## Installation

   1. Clone this repo and enter the repo directory
   2. cd src
   3. sudo ./install.sh #if you have root permission directly execute ./install.sh 

## Usage 
   
   $dir2sh <director_name - with full path> <output script name>

## Example
   
   $dir2sh /home/test test.tar.sh

## Use Case

This utility is useful to transport directory as a self extractable package/script between linux/mac systems.

