# -s-T-ation-1
yours truly 
p_devs":0,"is_first_party":0,"bug_type":"309","os_version":"iPhone OS 18.0 (22A5338b)","roots_installed":0,"name":"com.ansjer.zccloud.NotificationService","incident_id":"07A56B37-6546-4491-BFBB-CA5A5FDA0454"}
{
  "uptime" : 34000,
  "procRole" : "Unspecified",
  "version" : 2,
  "userID" : 501,
  "deployVersion" : 210,
  "modelCode" : "iPhone14,3",
  "coalitionID" : 720,
  "osVersion" : {
    "isEmbedded" : true,
    "train" : "iPhone OS 18.0",
    "releaseType" : "Beta",
    "build" : "22A5338b"
  },
  "captureTime" : "2024-08-14 11:41:59.8532 -0500",
  "codeSigningMonitor" : 2,
  "incident" : "07A56B37-6546-4491-BFBB-CA5A5FDA0454",
  "pid" : 1781,
  "translated" : false,
  "cpuType" : "ARM-64",
  "roots_installed" : 0,
  "bug_type" : "309",
  "procLaunch" : "2024-08-14 11:41:53.5583 -0500",
  "procStartAbsTime" : 823917599752,
  "procExitAbsTime" : 824068653373,
  "procName" : "com.ansjer.zccloud.NotificationService",
  "procPath" : "\/private\/var\/containers\/Bundle\/Application\/E4FBFD70-5379-4A71-A23D-3EBC327EBF18\/ZosiSmart.app\/PlugIns\/com.ansjer.zccloud.NotificationService.appex\/com.ansjer.zccloud.NotificationService",
  "bundleInfo" : {"CFBundleShortVersionString":"3.2.25","CFBundleVersion":"2024061301","CFBundleIdentifier":"com.ansjer.zccloud.NotificationService"},
  "storeInfo" : {"itemID":"1355964934","storeCohortMetadata":"10|date=1640397600000&sf=143441&rdom=dvema.com&rapp=com.apple.mobilesafari&pgtp=Software&pgid=1355964934&ctxt=Today&lngid=1","distributorID":"com.apple.AppStore","deviceIdentifierForVendor":"798D16DE-AF12-4092-8BE4-761B7169DC20","softwareVersionExternalIdentifier":"866669243","applicationVariant":"1:iPhone14,3:15","thirdParty":true},
  "parentProc" : "launchd",
  "parentPid" : 1,
  "coalitionName" : "com.ansjer.zccloud.NotificationService",
  "crashReporterKey" : "eff91e0abb53a38f485213f0578f4d927ae83e92",
  "lowPowerMode" : 1,
  "wasUnlockedSinceBoot" : 1,
  "isLocked" : 1,
  "consecutiveCrashCount" : 320,
  "throttleTimeout" : 1200,
  "codeSigningID" : "com.ansjer.zccloud.NotificationService",
  "codeSigningTeamID" : "772N5HXAR2",
  "codeSigningFlags" : 570450689,
  "codeSigningValidationCategory" : 4,
  "codeSigningTrustLevel" : 5,
  "instructionByteStream" : {"beforePC":"fyMD1f17v6n9AwCRPOz\/l78DAJH9e8Go\/w9f1sADX9YQKYDSARAA1A==","atPC":"AwEAVH8jA9X9e7+p\/QMAkTHs\/5e\/AwCR\/XvBqP8PX9bAA1\/WECeA0g=="},
  "bootSessionUUID" : "1232C498-7E01-4C13-BE57-584FEAF010B5",
  "basebandVersion" : "4.02.05",
  "exception" : {"codes":"0x0000000000000000, 0x0000000000000000","rawCodes":[0,0],"type":"EXC_CRASH","signal":"SIGABRT"},
  "termination" : {"flags":0,"code":6,"namespace":"SIGNAL","indicator":"Abort trap: 6","byProc":"com.ansjer.zccloud.NotificationS","byPid":1781},
  "asi" : {"libsystem_c.dylib":["abort() called"]},
  "exceptionReason" : {"arguments":["NSNull","length","0x206db76c0"],"format_string":"-[%s %s]: unrecognized selector sent to instance %p","name":"NSInvalidArgumentException","type":"objc-exception","composed_message":"-[NSNull length]: unrecognized selector sent to instance 0x206db76c0","class":"NSException"},
  "lastExceptionBacktrace" : [{"imageOffset":540812,"symbol":"__exceptionPreprocess","symbolLocation":164,"imageIndex":7},{"imageOffset":94948,"symbol":"objc_exception_throw","symbolLocation":88,"imageIndex":5},{"imageOffset":1615816,"symbol":"+[NSObject(NSObject) _copyDescription]","symbolLocation":0,"imageIndex":7},{"imageOffset":137352,"symbol":"___forwarding___","symbolLocation":1560,"imageIndex":7},{"imageOffset":135600,"symbol":"_CF_forwarding_prep_0","symbolLocation":96,"imageIndex":7},{"imageOffset":348808,"symbol":"static String._unconditionallyBridgeFromObjectiveC(_:)","symbolLocation":444,"imageIndex":8},{"imageOffset":4912380,"symbol":"@objc static NSURLComponents._componentsWith(string:encodingInvalidCharacters:)","symbolLocation":40,"imageIndex":8},{"imageOffset":9041948,"symbol":"-[__NSPlaceholderURLComponents initWithString:encodingInvalidCharacters:]","symbolLocation":36,"imageIndex":8},{"imageOffset":322020,"symbol":"-[NSURL(NSURL) initWithString:relativeToURL:encodingInvalidCharacters:]","symbolLocation":284,"imageIndex":8},{"imageOffset":321464,"symbol":"+[NSURL(NSURL) URLWithString:relativeToURL:]","symbolLocation":44,"imageIndex":8},{"imageOffset":17552,"imageIndex":0},{"imageOffset":17068,"imageIndex":0},{"imageOffset":16592,"symbol":"_dispatch_client_callout","symbolLocation":20,"imageIndex":6},{"imageOffset":30080,"symbol":"_dispatch_continuation_pop","symbolLocation":596,"imageIndex":6},{"imageOffset":111932,"symbol":"_dispatch_source_latch_and_call","symbolLocation":420,"imageIndex":6},{"imageOffset":106756,"symbol":"_dispatch_source_invoke","symbolLocation":836,"imageIndex":6},{"imageOffset":76020,"symbol":"_dispatch_main_queue_drain","symbolLocation":744,"imageIndex":6},{"imageOffset":75260,"symbol":"_dispatch_main_queue_callback_4CF","symbolLocation":44,"imageIndex":6},{"imageOffset":356196,"symbol":"__CFRUNLOOP_IS_SERVICING_THE_MAIN_DISPATCH_QUEUE__","symbolLocation":16,"imageIndex":7},{"imageOffset":344456,"symbol":"__CFRunLoopRun","symbolLocation":1996,"imageIndex":7},{"imageOffset":341432,"symbol":"CFRunLoopRunSpecific","symbolLocation":572,"imageIndex":7},{"imageOffset":749312,"symbol":"-[NSRunLoop(NSRunLoop) runMode:beforeDate:]","symbolLocation":212,"imageIndex":8},{"imageOffset":749012,"symbol":"-[NSRunLoop(NSRunLoop) run]","symbolLocation":64,"imageIndex":8},{"imageOffset":114404,"symbol":"_xpc_objc_main","symbolLocation":336,"imageIndex":9},{"imageOffset":123984,"symbol":"_xpc_main","symbolLocation":64,"imageIndex":9},{"imageOffset":124464,"symbol":"_xpc_create_bootstrap_pipe","symbolLocation":0,"imageIndex":9},{"imageOffset":1407588,"symbol":"+[NSXPCListener serviceListener]","symbolLocation":0,"imageIndex":8},{"imageOffset":103708,"imageIndex":10},{"imageOffset":103336,"imageIndex":10},{"imageOffset":102500,"imageIndex":10},{"imageOffset":104568,"imageIndex":10},{"imageOffset":42772,"symbol":"EXExtensionMain","symbolLocation":288,"imageIndex":11},{"imageOffset":1837812,"symbol":"NSExtensionMain","symbolLocation":204,"imageIndex":8},{"imageOffset":212276,"symbol":"start","symbolLocation":2724,"imageIndex":12}],
  "faultingThread" : 0,
  "threads" : [{"triggered":true,"id":400710,"threadState":{"x":[{"value":0},{"value":0},{"value":0},{"value":0},{"value":9268432699},{"value":6104310352},{"value":110},{"value":90192},{"value":8203577695267798714},{"value":8203577686597114554},{"value":81},{"value":11},{"value":11},{"value":7007898500},{"value":45},{"value":4374872064},{"value":328},{"value":8676975616,"symbolLocation":0,"symbol":"_main_thread"},{"value":0},{"value":6},{"value":259},{"value":8676975840,"symbolLocation":224,"symbol":"_main_thread"},{"value":272},{"value":0},{"value":0},{"value":8676975840,"symbolLocation":224,"symbol":"_main_thread"},{"value":524296},{"value":8676961408,"symbolLocation":0,"symbol":"_dispatch_main_q"},{"value":8676961536,"symbolLocation":0,"symbol":"_dispatch_mgr_q"}],"flavor":"ARM_THREAD_STATE64","lr":{"value":9269317368},"cpsr":{"value":1073745920},"fp":{"value":6104310208},"sp":{"value":6104310176},"esr":{"value":1442840704,"description":" Address size fault"},"pc":{"value":8341729908,"matchesCrashFrame":1},"far":{"value":0}},"queue":"com.apple.main-thread","frames":[{"imageOffset":49780,"symbol":"__pthread_kill","symbolLocation":8,"imageIndex":1},{"imageOffset":32504,"symbol":"pthread_kill","symbolLocation":268,"imageIndex":2},{"imageOffset":490200,"symbol":"abort","symbolLocation":128,"imageIndex":3},{"imageOffset":79288,"symbol":"abort_message","symbolLocation":132,"imageIndex":4},{"imageOffset":7084,"symbol":"demangling_terminate_handler()","symbolLocation":348,"imageIndex":4},{"imageOffset":208388,"symbol":"_objc_terminate()","symbolLocation":156,"imageIndex":5},{"imageOffset":75900,"symbol":"std::__terminate(void (*)())","symbolLocation":16,"imageIndex":4},{"imageOffset":75808,"symbol":"std::terminate()","symbolLocation":108,"imageIndex":4},{"imageOffset":16612,"symbol":"_dispatch_client_callout","symbolLocation":40,"imageIndex":6},{"imageOffset":30080,"symbol":"_dispatch_continuation_pop","symbolLocation":596,"imageIndex":6},{"imageOffset":111932,"symbol":"_dispatch_source_latch_and_call","symbolLocation":420,"imageIndex":6},{"imageOffset":106756,"symbol":"_dispatch_source_invoke","symbolLocation":836,"imageIndex":6},{"imageOffset":76020,"symbol":"_dispatch_main_queue_drain","symbolLocation":744,"imageIndex":6},{"imageOffset":75260,"symbol":"_dispatch_main_queue_callback_4CF","symbolLocation":44,"imageIndex":6},{"imageOffset":356196,"symbol":"__CFRUNLOOP_IS_SERVICING_THE_MAIN_DISPATCH_QUEUE__","symbolLocation":16,"imageIndex":7},{"imageOffset":344456,"symbol":"__CFRunLoopRun","symbolLocation":1996,"imageIndex":7},{"imageOffset":341432,"symbol":"CFRunLoopRunSpecific","symbolLocation":572,"imageIndex":7},{"imageOffset":749312,"symbol":"-[NSRunLoop(NSRunLoop) runMode:beforeDate:]","symbolLocation":212,"imageIndex":8},{"imageOffset":749012,"symbol":"-[NSRunLoop(NSRunLoop) run]","symbolLocation":64,"imageIndex":8},{"imageOffset":114404,"symbol":"_xpc_objc_main","symbolLocation":336,"imageIndex":9},{"imageOffset":123984,"symbol":"_xpc_main","symbolLocation":64,"imageIndex":9},{"imageOffset":124464,"symbol":"xpc_main","symbolLocation":64,"imageIndex":9},{"imageOffset":1407588,"symbol":"-[NSXPCListener resume]","symbolLocation":308,"imageIndex":8},{"imageOffset":103708,"imageIndex":10},{"imageOffset":103336,"imageIndex":10},{"imageOffset":102500,"imageIndex":10},{"imageOffset":104568,"imageIndex":10},{"imageOffset":42772,"symbol":"EXExtensionMain","symbolLocation":288,"imageIndex":11},{"imageOffset":1837812,"symbol":"NSExtensionMain","symbolLocation":204,"imageIndex":8},{"imageOffset":212276,"symbol":"start","symbolLocation":2724,"imageIndex":12}]},{"id":400721,"frames":[{"imageOffset":5248,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":2}],"threadState":{"x":[{"value":6106017792},{"value":4615},{"value":6105481216},{"value":0},{"value":409604},{"value":18446744073709551615},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0}],"flavor":"ARM_THREAD_STATE64","lr":{"value":0},"cpsr":{"value":4096},"fp":{"value":0},"sp":{"value":6106017792},"esr":{"value":1442840704,"description":" Address size fault"},"pc":{"value":9269290112},"far":{"value":0}}}],
  "usedImages" : [
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 4362567680,
    "size" : 32768,
    "uuid" : "e975981d-c2a1-31bb-8bb6-1c5a30f83678",
    "path" : "\/private\/var\/containers\/Bundle\/Application\/E4FBFD70-5379-4A71-A23D-3EBC327EBF18\/ZosiSmart.app\/PlugIns\/com.ansjer.zccloud.NotificationService.appex\/com.ansjer.zccloud.NotificationService",
    "name" : "com.ansjer.zccloud.NotificationService"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 8341680128,
    "size" : 237564,
    "uuid" : "8d929b3b-d4d6-39bf-adbb-be59e928b332",
    "path" : "\/usr\/lib\/system\/libsystem_kernel.dylib",
    "name" : "libsystem_kernel.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 9269284864,
    "size" : 53236,
    "uuid" : "fcc77eb0-558f-3703-9267-5419c4d33ae7",
    "path" : "\/usr\/lib\/system\/libsystem_pthread.dylib",
    "name" : "libsystem_pthread.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 7134310400,
    "size" : 524276,
    "uuid" : "1ad666a0-01a8-31c1-88b9-808915fb97b4",
    "path" : "\/usr\/lib\/system\/libsystem_c.dylib",
    "name" : "libsystem_c.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 9268334592,
    "size" : 110592,
    "uuid" : "256c6581-e601-3bd1-972e-b869776bed2f",
    "path" : "\/usr\/lib\/libc++abi.dylib",
    "name" : "libc++abi.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6956253184,
    "size" : 331104,
    "uuid" : "1a127d44-47a3-3947-bc4d-9a51c4c4e157",
    "path" : "\/usr\/lib\/libobjc.A.dylib",
    "name" : "libobjc.A.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 7134023680,
    "size" : 286720,
    "uuid" : "b8c15e69-d076-317d-9296-1279500738fc",
    "path" : "\/usr\/lib\/system\/libdispatch.dylib",
    "name" : "libdispatch.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 7002984448,
    "size" : 5529600,
    "uuid" : "80d8c862-dbd0-3d99-850b-0601bd6f3860",
    "path" : "\/System\/Library\/Frameworks\/CoreFoundation.framework\/CoreFoundation",
    "name" : "CoreFoundation"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 6982221824,
    "size" : 13758464,
    "uuid" : "4128867e-fe6f-346b-94e8-7ea49b0983b7",
    "path" : "\/System\/Library\/Frameworks\/Foundation.framework\/Foundation",
    "name" : "Foundation"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 9269592064,
    "size" : 294912,
    "uuid" : "6e0a4093-fa26-301f-800d-35bff83e79a0",
    "path" : "\/usr\/lib\/system\/libxpc.dylib",
    "name" : "libxpc.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 7806062592,
    "size" : 237568,
    "uuid" : "2af01e14-ddd6-397c-9202-93effb6b5f50",
    "path" : "\/System\/Library\/PrivateFrameworks\/PlugInKit.framework\/PlugInKit",
    "name" : "PlugInKit"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 7255212032,
    "size" : 782336,
    "uuid" : "d9386b75-1550-3b9b-9495-08b6b8f500ac",
    "path" : "\/System\/Library\/Frameworks\/ExtensionFoundation.framework\/ExtensionFoundation",
    "name" : "ExtensionFoundation"
  },
  {
    "source" : "P",
    "arch" : "arm64e",
    "base" : 7631286272,
    "size" : 538260,
    "uuid" : "341811f0-021c-38fe-92fc-19ce7646dfe9",
    "path" : "\/usr\/lib\/dyld",
    "name" : "dyld"
  },
  {
    "size" : 0,
    "source" : "A",
    "base" : 0,
    "uuid" : "00000000-0000-0000-0000-000000000000"
  }
],
  "sharedCache" : {
  "base" : 6955204608,
  "size" : 4252188672,
  "uuid" : "86260d66-5a44-37e7-b080-0e244cd65aa4"
},
  "vmSummary" : "ReadOnly portion of Libraries: Total=427.4M resident=0K(0%) swapped_out_or_unallocated=427.4M(100%)\nWritable regions: Total=24.7M written=256K(1%) resident=256K(1%) swapped_out=0K(0%) unallocated=24.5M(99%)\n\n                                VIRTUAL   REGION \nREGION TYPE                        SIZE    COUNT (non-coalesced) \n===========                     =======  ======= \nActivity Tracing                   256K        1 \nDispatch continuations            6144K        1 \nKernel Alloc Once                   32K        1 \nMALLOC                            16.7M        7 \nMALLOC guard page                   32K        2 \nSTACK GUARD                         32K        2 \nStack                             1552K        2 \n__AUTH                             760K      116 \n__AUTH_CONST                      15.9M      332 \n__CTF                               824        1 \n__DATA                            3215K      297 \n__DATA_CONST                      8772K      334 \n__DATA_DIRTY                      1193K      288 \n__FONT_DATA                        2352        1 \n__INFO_FILTER                         8        1 \n__LINKEDIT                       188.9M        2 \n__OBJC_RW                         2936K        1 \n__TEXT                           238.6M      342 \n__TPRO_CONST                       272K        2 \nmapped file                       31.5M        3 \nowned unmapped memory               16K        1 \npage table in kernel               256K        1 \nshared memory                       80K        4 \n===========                     =======  ======= \nTOTAL                            516.4M     1742 \n",
  "legacyInfo" : {
  "threadTriggered" : {
    "queue" : "com.apple.main-thread"
  }
},
  "logWritingSignature" : "3053d886debd3de78fbdc99cb4ce6a89a2a95519",
  "trialInfo" : {
  "rollouts" : [
    {
      "rolloutId" : "6297d96be2c9387df974efa4",
      "factorPackIds" : {
        "SIRI_VALUE_INFERENCE_APP_RESOLUTION" : "65d92566bcbbe039283f5dce"
      },
      "deploymentId" : 250000026
    },
    {
      "rolloutId" : "60f8ddccefea4203d95cbeef",
      "factorPackIds" : {

      },
      "deploymentId" : 250000018
    }
  ],
  "experiments" : [
    {
      "treatmentId" : "6355f564-39d1-49c5-9c83-39960f62d745",
      "experimentId" : "63d2fb7d7a5f3575ceb2abf7",
      "deploymentId" : 400000033
    },
    {
      "treatmentId" : "de73b8b3-48a7-459f-a4dc-70237e06e95e",
      "experimentId" : "65086cda725afb490920e22b",
      "deploymentId" : 500000004
    }
  ]
}


sincerly brady fischer
