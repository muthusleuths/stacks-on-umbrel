## Stacks Community App Store for Umbrel

### Add the Stacks Appstore to your Umbrel

- Open the Appstore from your Umbrel Dashboard
- Click the three dots in the top right and select *Community App Store*
- Paste https://github.com/muthusleuths/stacks-on-umbrel.git and click ADD
- Click Open and install desired Stacks apps


Alternatively, you can use the Umbrel CLI as described below.

To add the Stacks app store:
```
sudo ~/umbrel/scripts/repo add https://github.com/muthusleuths/stacks-on-umbrel.git

sudo ~/umbrel/scripts/repo update
```

To install an app from the Stacks app store
```
sudo ~/umbrel/scripts/app install stacks-blockchain
```

To remove the Stacks app store:
```
sudo ~/umbrel/scripts/repo remove https://github.com/muthusleuths/stacks-on-umbrel.git
```
