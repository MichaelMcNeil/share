```
https://alariotech.servicedesk.atera.com/GetAgent/Msi/?customerId=11&integratorLogin=support%40alariotech.com&customerName=LVVS
```

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


```
curl -o setup.msi "https://alariotech.servicedesk.atera.com/GetAgent/Msi/?customerId=79&integratorLogin=support%40alariotech.com&customerName=Citizen%20Cider" && msiexec /i setup.msi /qn  IntegratorLogin=support@alariotech.com CompanyId=79
```

## Stackpole and French
Windows
```
curl -o setup.msi "https://alariotech.servicedesk.atera.com/GetAgent/Msi/?customerId=50&integratorLogin=support%40alariotech.com&customerName=Stackpole%20%26%20French%20Law%20Offices" && msiexec /i setup.msi /qn  IntegratorLogin=support@alariotech.com CompanyId=50
```
