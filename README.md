---
services: Locks
platforms: dotnet
author: yaohaizh
---

# Getting started with managing resource locks in .NET #

          Azure sample for applying locks to resources
         
          Summary ...
         
          This sample shows examples of management locks usage on various resources.
         
          Details ...
         
          1. Create a number of various resources to apply locks to...
          2. Apply various locks to the resources
          3. Retrieve and show lock information
          4. Remove the locks and clean up


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/locks-dotnet-manage-locks.git

    cd locks-dotnet-manage-locks
  
    dotnet build
    
    bin\Debug\net452\ManageLocks.exe

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.