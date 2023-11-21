# gtfobin-chacker
During the privilege escalation the most obivious way is to find SUID, GUID, Capability, extra privilege file discovering. After found some binaries we need search in goodle one by one to check is there any exxploit available in publicly. GTFObin is one of the best privilege escalation technique database. Where can find lots of valueable techniques based on the binary and the scenario. Its so annoying to go GTFObin and search one by one. This script will took a file name as an input and search all the the binaries in GTFObin if there is any techniques found will show that and the corresponding URL also. So if the vector match the secnario we can visit the URL and try the technique.

## Set-Up the Environment
```
git clone https://github.com/Raju-Talukder/gtfobin-chacker.git
cd gtfobin-chacker
```

## Useages 
```
./check_gtfobin filename
```