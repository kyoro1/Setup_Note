# Setup_Note

## For Ubuntu on Azure

### Change editor on Ubuntu
Need to set up editor for keeping our productivity :)

```sh
sudo update-alternatives --set editor /usr/bin/vim.basic
```

- Further detail: [heat sheet for some shortcuts](https://vim.rtorr.com/)

### SSH set-up

```sh
ssh-keygen
```
Set up 

- Refer [this link](https://docs.microsoft.com/en-us/azure/devops/repos/git/use-ssh-keys-to-authenticate?view=azure-devops#step-1-create-your-ssh-keys) for further operation

### Set up shutdown time
In case that we miss to stop the vm, this operation could be effective [this link](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-create-manage-compute-instance?tabs=python#schedule-automatic-start-and-stop-preview)




