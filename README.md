# Backend-development-best-pratices
In the world that development is not a manual task anymore and pure IA does not deliver quality codes. 

## 1. Its architecture begins with the folder structure. 

In the IA age complexes architecture tend to spend more tokens and in worst-case can to reduce its performance. This architecure is optimized solve this issue. Good old layered architecture.

```
project folder
|_ config
|_ controller
|  |  (new folders must be replicated for to other folders in the architecture, follow example with people folder)
|  |_ people
|_ dto
|  |_ people 
|_ enums
|  |_ people
|_ entity
|  (here must not to separate for additional folders, because this folders must be explicity mapped for schema in the database)
|_ exception
|  (must not be separeted for additional folders too)
|_ filter
|  (must not be separeted for additional folders too)
|_ repository
|  |_ people
|_ service
|_ people
|_ util
  (must not be separeted for additional folders too)
```
