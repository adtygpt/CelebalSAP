@Library('piper-lib-os@v1.218.0') _
piper gctsDeploy
gctsDeploy(
  script: this,
  host: 'https://https://s4hana2020.cognitusconsulting.com:8001',
  client: '200',
  abapCredentialsId: 'ABAPUserPasswordCredentialsId',
  repository: 'myrepo',
  remoteRepositoryURL: "https://remote.repository.url.com",
  role: 'SOURCE',
  vSID: 'ABC',
  branch: 'feature1',
  commit: '80d45af',
  scope: 'LASTACTION',
  rollback: true,
  configuration: [VCS_AUTOMATIC_PULL: 'TRUE',VCS_AUTOMATIC_PUSH: 'TRUE',CLIENT_VCS_LOGLVL: 'debug']
)
