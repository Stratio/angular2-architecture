@Library('libpipelines@master') _

hose {
   EMAIL = 'egeo'
   MODULE = 'egeo-starter'
   REPOSITORY = 'github.com/egeo-starter'

   DEVTIMEOUT = 30
   RELEASETIMEOUT = 30

   DEV = { config ->
      doCompile(config)
      doUT(config)
      doDeploy(config)
   }
}