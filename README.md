# poc_azure_ci_ext

- install node
- npm install -g tfx-cli
- npm init -y
- npm install vss-web-extension-sdk --save
- npm install azure-pipelines-task-lib --save
- npm install @types/node --save-dev
- npm install @types/q --save-dev
- tsc --init
- tfx extension create --manifest-globs vss-extension.json



## References
- https://docs.microsoft.com/en-us/azure/devops/extend/develop/add-build-task?view=azure-devops
- https://docs.microsoft.com/en-us/azure/devops/extend/get-started/node?view=azure-devops
- https://docs.microsoft.com/en-us/azure/devops/integrate/index?view=azure-devops
- https://docs.microsoft.com/en-us/azure/devops/extend/overview?view=azure-devops
- https://docs.microsoft.com/en-us/azure/devops/extend/get-started/node?view=azure-devops
- https://docs.microsoft.com/en-us/azure/devops/extend/develop/samples-overview?view=azure-devops
- https://docs.microsoft.com/en-us/azure/devops/service-hooks/overview?view=azure-devops
- https://docs.microsoft.com/en-us/azure/devops/extend/publish/overview?view=azure-devops
- https://docs.microsoft.com/en-us/azure/devops/extend/publish/integration?view=azure-devops
