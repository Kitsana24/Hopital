PODS:
  - Firebase/CoreOnly (6.26.0):
    - FirebaseCore (= 6.7.2)
  - Firebase/Messaging (6.26.0):
    - Firebase/CoreOnly
    - FirebaseMessaging (~> 4.4.1)
  - firebase_core (0.5.0):
    - Firebase/CoreOnly (~> 6.26.0)
    - Flutter
  - firebase_messaging (7.0.0):
    - Firebase/CoreOnly (~> 6.26.0)
    - Firebase/Messaging (~> 6.26.0)
    - firebase_core
    - Flutter
  - FirebaseAnalyticsInterop (1.5.0)
  - FirebaseCore (6.7.2):
    - FirebaseCoreDiagnostics (~> 1.3)
    - FirebaseCoreDiagnosticsInterop (~> 1.2)
    - GoogleUtilities/Environment (~> 6.5)
    - GoogleUtilities/Logger (~> 6.5)
  - FirebaseCoreDiagnostics (1.5.0):
    - GoogleDataTransport (~> 7.0)
    - GoogleUtilities/Environment (~> 6.7)
    - GoogleUtilities/Logger (~> 6.7)
    - nanopb (~> 1.30905.0)
  - FirebaseCoreDiagnosticsInterop (1.2.0)
  - FirebaseInstallations (1.3.0):
    - FirebaseCore (~> 6.6)
    - GoogleUtilities/Environment (~> 6.6)
    - GoogleUtilities/UserDefaults (~> 6.6)
    - PromisesObjC (~> 1.2)
  - FirebaseInstanceID (4.3.4):
    - FirebaseCore (~> 6.6)
    - FirebaseInstallations (~> 1.0)
    - GoogleUtilities/Environment (~> 6.5)
    - GoogleUtilities/UserDefaults (~> 6.5)
  - FirebaseMessaging (4.4.1):
    - FirebaseAnalyticsInterop (~> 1.5)
    - FirebaseCore (~> 6.6)
    - FirebaseInstanceID (~> 4.3)
    - GoogleUtilities/AppDelegateSwizzler (~> 6.5)
    - GoogleUtilities/Environment (~> 6.5)
    - GoogleUtilities/Reachability (~> 6.5)
    - GoogleUtilities/UserDefaults (~> 6.5)
    - Protobuf (>= 3.9.2, ~> 3.9)
  - Flutter (1.0.0)
  - FMDB (2.7.5):
    - FMDB/standard (= 2.7.5)
  - FMDB/standard (2.7.5)
  - google_maps_flutter (0.0.1):
    - Flutter
    - GoogleMaps
  - GoogleDataTransport (7.2.0):
    - nanopb (~> 1.30905.0)
  - GoogleMaps (2.7.0):
    - GoogleMaps/Maps (= 2.7.0)
  - GoogleMaps/Base (2.7.0)
  - GoogleMaps/Maps (2.7.0):
    - GoogleMaps/Base
  - GoogleUtilities/AppDelegateSwizzler (6.7.2):
    - GoogleUtilities/Environment
    - GoogleUtilities/Logger
    - GoogleUtilities/Network
  - GoogleUtilities/Environment (6.7.2):
    - PromisesObjC (~> 1.2)
  - GoogleUtilities/Logger (6.7.2):
    - GoogleUtilities/Environment
  - GoogleUtilities/Network (6.7.2):
    - GoogleUtilities/Logger
    - "GoogleUtilities/NSData+zlib"
    - GoogleUtilities/Reachability
  - "GoogleUtilities/NSData+zlib (6.7.2)"
  - GoogleUtilities/Reachability (6.7.2):
    - GoogleUtilities/Logger
  - GoogleUtilities/UserDefaults (6.7.2):
    - GoogleUtilities/Logger
  - image_picker (0.0.1):
    - Flutter
  - location (0.0.1):
    - Flutter
  - nanopb (1.30905.0):
    - nanopb/decode (= 1.30905.0)
    - nanopb/encode (= 1.30905.0)
  - nanopb/decode (1.30905.0)
  - nanopb/encode (1.30905.0)
  - PromisesObjC (1.2.10)
  - Protobuf (3.13.0)
  - shared_preferences (0.0.1):
    - Flutter
  - sqflite (0.0.1):
    - Flutter
    - FMDB (~> 2.7.2)

DEPENDENCIES:
  - firebase_core (from `.symlinks/plugins/firebase_core/ios`)
  - firebase_messaging (from `.symlinks/plugins/firebase_messaging/ios`)
  - Flutter (from `Flutter`)
  - google_maps_flutter (from `.symlinks/plugins/google_maps_flutter/ios`)
  - image_picker (from `.symlinks/plugins/image_picker/ios`)
  - location (from `.symlinks/plugins/location/ios`)
  - shared_preferences (from `.symlinks/plugins/shared_preferences/ios`)
  - sqflite (from `.symlinks/plugins/sqflite/ios`)

SPEC REPOS:
  trunk:
    - Firebase
    - FirebaseAnalyticsInterop
    - FirebaseCore
    - FirebaseCoreDiagnostics
    - FirebaseCoreDiagnosticsInterop
    - FirebaseInstallations
    - FirebaseInstanceID
    - FirebaseMessaging
    - FMDB
    - GoogleDataTransport
    - GoogleMaps
    - GoogleUtilities
    - nanopb
    - PromisesObjC
    - Protobuf

EXTERNAL SOURCES:
  firebase_core:
    :path: ".symlinks/plugins/firebase_core/ios"
  firebase_messaging:
    :path: ".symlinks/plugins/firebase_messaging/ios"
  Flutter:
    :path: Flutter
  google_maps_flutter:
    :path: ".symlinks/plugins/google_maps_flutter/ios"
  image_picker:
    :path: ".symlinks/plugins/image_picker/ios"
  location:
    :path: ".symlinks/plugins/location/ios"
  shared_preferences:
    :path: ".symlinks/plugins/shared_preferences/ios"
  sqflite:
    :path: ".symlinks/plugins/sqflite/ios"

SPEC CHECKSUMS:
  Firebase: 7cf5f9c67f03cb3b606d1d6535286e1080e57eb6
  firebase_core: 3134fe79d257d430f163b558caf52a10a87efe8a
  firebase_messaging: 6061cbdfe4463502a0d4d7049820c25d1757a095
  FirebaseAnalyticsInterop: 3f86269c38ae41f47afeb43ebf32a001f58fcdae
  FirebaseCore: f42e5e5f382cdcf6b617ed737bf6c871a6947b17
  FirebaseCoreDiagnostics: 7535fe695737f8c5b350584292a70b7f8ff0357b
  FirebaseCoreDiagnosticsInterop: 296e2c5f5314500a850ad0b83e9e7c10b011a850
  FirebaseInstallations: 6f5f680e65dc374397a483c32d1799ba822a395b
  FirebaseInstanceID: cef67c4967c7cecb56ea65d8acbb4834825c587b
  FirebaseMessaging: 29543feb343b09546ab3aa04d008ee8595b43c44
  Flutter: 0e3d915762c693b495b44d77113d4970485de6ec
  FMDB: 2ce00b547f966261cd18927a3ddb07cb6f3db82a
  google_maps_flutter: df4e7de95264aa0a2f11aac0fc7e313acb8ffc7e
  GoogleDataTransport: 672fb0ce96fe7f7f31d43672fca62ad2c9c86f7b
  GoogleMaps: f79af95cb24d869457b1f961c93d3ce8b2f3b848
  GoogleUtilities: 7f2f5a07f888cdb145101d6042bc4422f57e70b3
  image_picker: 66aa71bc96850a90590a35d4c4a2907b0d823109
  location: 3a2eed4dd2fab25e7b7baf2a9efefe82b512d740
  nanopb: c43f40fadfe79e8b8db116583945847910cbabc9
  PromisesObjC: b14b1c6b68e306650688599de8a45e49fae81151
  Protobuf: 3dac39b34a08151c6d949560efe3f86134a3f748
  shared_preferences: af6bfa751691cdc24be3045c43ec037377ada40d
  sqflite: 4001a31ff81d210346b500c55b17f4d6c7589dd0

PODFILE CHECKSUM: aafe91acc616949ddb318b77800a7f51bffa2a4c

COCOAPODS: 1.10.0
