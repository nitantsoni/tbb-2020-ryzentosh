# tbb-2020-ryzentosh
TBB@2020 for Ryzentosh users

As of 17th May 2023, trying to run `brew install tbb@2020` no longer works. It fails with the error 

```
Error: tbb@2020 has been disabled because it is not supported upstream!
```

As such, this repo is for Ryzentosh users, if they need to install tbb or need the dylibs.

## Install
 - Download the `tbb@2020.rb` file from above
 - `cd` to the download directory for that file
 - Run `brew install --build-from-source tbb@2020.rb`
 - Brew should now begin downloading & installing tbb@2020

## Dylibs
 - Download tbb-dylibs.zip
 - Use as needed
 - No need to install tbb
 
