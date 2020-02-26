# OLIVE Service API

This document is based on [@jamescooke](https://github.com/jamescooke)'s template project [restapidocs](https://github.com/jamescooke/restapidocs), which was taken from projects mainly using [Django Rest Framework](https://github.com/tomchristie/django-rest-framework). Templating by Markdwon was inspired by [@iros](https://github.com/iros)'s documentation [gist](https://gist.github.com/iros/3426278).

Where full URLs are provided in reseponses, they are processed as if service is running on 'http://{ADDRESS}:{PORT}/'.

## Open Endpoints

Open endpoints require no authentication.

## Closed Endpoints

Closed endpoints require a valid token to be included in the header of the request. A token can be acquired from the open endpoints above (**FIXME** to be updated).

### Devices

Each endpoint manipulates or displays information related to `Device`.

* [Show devices](devices/get.md) : `GET /api/devices/`

### Account related
