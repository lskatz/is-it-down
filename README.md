# Is it down 

This is a repo dedicated to reporting whether any given service is down.
This is done through GitHub actions.
Each sticker below is the name of a service and tells you whether the test passed.

# Statuses

[![esearch](https://github.com/lskatz/is-it-down/actions/workflows/esearch.yml/badge.svg?branch=main)](https://github.com/lskatz/is-it-down/actions/workflows/esearch.yml)

## Example

To understand what the actual status means, for example the `esearch` test, click on the actual status sticker which will bring you to the GitHub Actions page for this repo.

Click on the correct workflow on the left side  
![image](https://user-images.githubusercontent.com/14798/126335354-7b0ebbd9-1821-4586-b2a0-75d6b126899f.png)

Click on the latest run  
![image](https://user-images.githubusercontent.com/14798/126335476-44a77729-cf54-4fcd-8f23-eb8ff620c201.png)

Click on the down arrow to expand a section and see what passed.
In this example, we are highlighting these two commands and their output.
    
    esearch -db biosample -query "SAMN00860590" >  SAMN00860590.xml
    cat SAMN00860590.xml

![image](https://user-images.githubusercontent.com/14798/126335091-fb95b264-5a73-44a2-8f2c-8d1c30ba59b6.png)

Thus letting you know that the `esearch` command with the Eutils API is still running.

...as recently as July 20!  
![image](https://user-images.githubusercontent.com/14798/126338625-aa4dfc2e-96a0-425c-8cbb-2f80399fd4e5.png)

# Contributing

See [CONTRUBUTING.md](CONTRIBUTING.md)
