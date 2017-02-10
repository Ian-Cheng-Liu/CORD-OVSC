# ovsc

define the configuration file for populating the flow rules to OVS programmatically

example cfg file:

    {
    "apps" : {
            "org.onosproject.ovsc" : {
               "ovsc-cfg" : {
                 "bridgeId" : "of:0000000000000001",
                 "forMACSecVNF" : "false",
                 "dataPlanePort" : 26,
                 "vmPortLeft" : 30,
                 "vmPortRight" : 31,
                 "leftVlan" : 100,
                 "rightVlan" : 200,
                 "defaultPriority" : 60000
                 }
             }
          }
    }
