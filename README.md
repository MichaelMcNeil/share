[Discovery Windows](https://alariotech.servicedesk.atera.com/GetAgent/Msi/?customerId=92&integratorLogin=support%40alariotech.com&customerName=Discovery%20Bicycle%20Tours)
```
curl -o setup.msi "https://alariotech.servicedesk.atera.com/GetAgent/Msi/?customerId=92&integratorLogin=support%40alariotech.com&customerName=Discovery%20Bicycle%20Tours" && msiexec /i setup.msi /qn  IntegratorLogin=support@alariotech.com CompanyId=92
```

MACs
```
sudo curl "https://alariotech.servicedesk.atera.com/GetAgent/mac/0033z00002zDykmAAC/92" | sudo bash
```

Remove the AEM Agent old 
```
sudo bash /Applications/AEM\ Agent.app/Contents/Resources/uninstall.sh
```
