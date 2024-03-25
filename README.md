# CI status

Target | Build status |  Run status
--- | --- | ---
[nightly.test.emulation.cloud](https://nightly.test.emulation.cloud) || [![Deploy to fresh VM](https://github.com/emulation-as-a-service/nightly-bot/actions/workflows/deploy.yaml/badge.svg)](https://github.com/emulation-as-a-service/nightly-bot/actions/workflows/deploy.yaml)
https://eaas.dev/eaas-installer || [![Installation test](https://github.com/emulation-as-a-service/eaas-installer/actions/workflows/test.yml/badge.svg)](https://github.com/emulation-as-a-service/eaas-installer/actions/workflows/test.yml)
https://eaas.dev/demo-ui | [![pipeline status](https://gitlab.com/emulation-as-a-service/demo-ui/badges/master/pipeline.svg)](https://gitlab.com/emulation-as-a-service/demo-ui/-/commits/master) | [![Playwright tests](https://github.com/emulation-as-a-service/demo-ui/actions/workflows/test.yml/badge.svg)](https://github.com/emulation-as-a-service/demo-ui/actions/workflows/test.yml)
https://eaas.dev/eaas-client | [![pipeline status](https://gitlab.com/emulation-as-a-service/eaas-client/badges/master/pipeline.svg)](https://gitlab.com/emulation-as-a-service/eaas-client/-/commits/master)
https://eaas.dev/eaas-server | [![pipeline status](https://gitlab.com/emulation-as-a-service/eaas-server/badges/master/pipeline.svg)](https://gitlab.com/emulation-as-a-service/eaas-server/-/commits/master)
https://eaas.dev/eaas-proxy |  [![pipeline status](https://gitlab.com/emulation-as-a-service/eaas-proxy/badges/master/pipeline.svg)](https://gitlab.com/emulation-as-a-service/eaas-proxy/-/commits/master)

## nightly.test.emulation.cloud

- https://nightly.test.emulation.cloud: `testing` branch of eaasi-client ([changelog](https://gitlab.com/eaasi/eaasi-client-pub/commits/testing))
  - username: `admin`, password: `admin`
  - one group with username: `groupadmin`, password: `groupadmin`  
- https://nightly.test.emulation.cloud/admin: `master` branch of demo-ui ([changelog](https://gitlab.com/emulation-as-a-service/demo-ui/commits/master))
- https://nightly.test.emulation.cloud/emil/admin/build-info: `master` branch of eaas-server ([changelog](https://gitlab.com/emulation-as-a-service/eaas-server/commits/master))
- gets redeployed every night at 03:30 UTC (existing data is **deleted**)
  - installed by `master` branch of eaas-installer ([changelog](https://gitlab.com/emulation-as-a-service/eaas-installer/commits/master))
