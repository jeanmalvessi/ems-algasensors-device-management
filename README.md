# device-management
This is a project built during the AlgaWorks Microservices Specialist Course (EMS) Level 1 - Software architecture and microservices.

See full description on [ems-algasensors-meta](https://github.com/jeanmalvessi/ems-algasensors-meta).

Sensors CRUD, configuration and remote management.

Endpoints:
- `POST /api/sensors`: create a new sensor
- `GET /api/sensors`: retrieve all sensors
- `GET /api/sensors/{sensorId}`: retrieve a specific sensor
- `PUT /api/sensors/{sensorId}`: update a specific sensor
- `DELETE /api/sensors/{sensorId}`: delete a specific sensor
- `PUT /api/sensors/{sensorId}/enable`: activate a specific sensor
- `DELETE /api/sensors/{sensorId}/enable`: deactivate a specific sensor
