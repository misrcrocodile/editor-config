# 1. Clean the APT Cache (And Do It Regularly)
```
du -sh /var/cache/apt/archives
sudo apt-get clean
```
# 2. 2. Remove Old Kernels (If No Longer Required)
```
sudo apt-get autoremove --purge
```

# 3. Uninstall Apps & Games You Never Use (And Be Honest!)
```
' remove specific app
sudo apt-get remove package-name1 package-name2
' remove no longer required dependencies
sudo apt-get autoremove
```
