## About This Repository
Based on the blogs [Getting started with CAP on PostgreSQL (Node.js)](https://blogs.sap.com/2020/11/16/getting-started-with-cap-on-postgresql-node.js/) and [Run and Deploy CAP with PostgreSQL on SAP BTP Cloud Foundry (Node.js)](https://blogs.sap.com/2020/11/30/run-and-deploy-cap-with-postgresql-on-sap-cloud-platform-cloud-foundry-node.js/), several issues that were originally present have been addressed, resulting in this project.

Dependency versions for **local test**:
```
    "dependencies": {
        "@sap/cds": "5.1.5",
        "cds-dbm": "^0.0.26",
        "cds-pg": "0.0.51",
        "express": "^4"
    },
```

Dependency versions for **deployment to Cloud Foundry**:
```
    "dependencies": {
        "@sap/cds": "~6.6.1",
        "cds-dbm": "~0.1.4",
        "cds-pg": "~0.1.35",
        "express": "^4"
    },
```

The version of **APT Buildpack**:

https://github.com/cloudfoundry/apt-buildpack#v0.3.0

## Further References
- `cds-pg`: https://www.npmjs.com/package/cds-pg
- `cds-dbm`: https://www.npmjs.com/package/cds-dbm
- Another example app already using `cds-dbm` in combination with `cds-pg`: https://github.com/gregorwolf/pg-beershop


