# ARM-LAB2
my-lab

az deployment group validate \
  --resource-group myResourceGroup \
  --template-file template.json \
  --parameters @parameters.json

  az deployment group show \
  --resource-group myResourceGroup \
  --name template.json

  az vm list-ip-addresses \
  --resource-group myResourceGroup \
  --name <VM_NAME> \
  -o table
