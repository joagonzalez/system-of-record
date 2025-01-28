Initial prompt:

```
Im trying to build an Engineering SOR (system of record) to maintain the whole lifecycle of configuration parameters and 
designs that under the scope of Engineering team like network params, software versions, hardware versions, etc.

I would like to use a GitOps approach, where I persist this data using YAML files using a propoer directory
structure dividing by technology.

I am thinking in mixing this GitOps approach with a CI/CD pipeline to validate the data and add approval
workflows to the changes. Alos I would like to have an API that reads this data and expose it to other systems.
```