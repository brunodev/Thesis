# Application structure

## Worker
### Spoofers
### Servers
### Tools
### Models
### Utils
___
## Controller
### Web UI
#### SignalR component
#### VueJS component
### Text UI
___
## Persistent data storage
Seperated from controller, but manageable from the controller; ie the controller decides the type of data layer.

### Encrypted JSON
### Unit tests

## Flow
*UI* Registers a controller which is fed into a new *Worker*. The controller contains a *persistent data storage entity* which is used to save the data. The *Worker* is responsible for saving the data using the registered *persistent data storage*.