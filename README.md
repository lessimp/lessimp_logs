# lessimp_logs
Logs for view when needed


ken@Kens-MBP ios % flutter run --verbose
[ +148 ms] executing: sysctl hw.optional.arm64
[  +24 ms] Exit code 1 from: sysctl hw.optional.arm64
[   +1 ms] sysctl: unknown oid 'hw.optional.arm64'
[   +8 ms] executing: [/Users/Ken/Development/flutter/] git -c
log.showSignature=false log -n 1 --pretty=format:%H
[  +23 ms] Exit code 0 from: git -c log.showSignature=false log -n 1
--pretty=format:%H
[        ] fb57da5f945d02ef4f98dfd9409a72b7cce74268
[   +1 ms] executing: [/Users/Ken/Development/flutter/] git tag --points-at
fb57da5f945d02ef4f98dfd9409a72b7cce74268
[ +138 ms] Exit code 0 from: git tag --points-at
fb57da5f945d02ef4f98dfd9409a72b7cce74268
[   +1 ms] 3.0.1
[  +10 ms] executing: [/Users/Ken/Development/flutter/] git rev-parse
--abbrev-ref --symbolic @{u}
[  +10 ms] Exit code 0 from: git rev-parse --abbrev-ref --symbolic @{u}
[        ] origin/stable
[        ] executing: [/Users/Ken/Development/flutter/] git ls-remote --get-url
origin
[  +11 ms] Exit code 0 from: git ls-remote --get-url origin
[   +1 ms] git@github.com:flutter/flutter.git
[ +152 ms] executing: [/Users/Ken/Development/flutter/] git rev-parse
--abbrev-ref HEAD
[  +16 ms] Exit code 0 from: git rev-parse --abbrev-ref HEAD
[        ] stable
[   +9 ms] executing: sw_vers -productName
[  +29 ms] Exit code 0 from: sw_vers -productName
[        ] macOS
[        ] executing: sw_vers -productVersion
[  +24 ms] Exit code 0 from: sw_vers -productVersion
[        ] 12.4
[        ] executing: sw_vers -buildVersion
[  +22 ms] Exit code 0 from: sw_vers -buildVersion
[        ] 21F79
[        ] executing: uname -m
[  +10 ms] Exit code 0 from: uname -m
[   +4 ms] x86_64
[ +108 ms] Artifact Instance of 'AndroidGenSnapshotArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'AndroidInternalBuildArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'IOSEngineArtifacts' is not required, skipping
update.
[        ] Artifact Instance of 'FlutterWebSdk' is not required, skipping
update.
[  +15 ms] Artifact Instance of 'WindowsEngineArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'WindowsUwpEngineArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'MacOSEngineArtifacts' is not required, skipping
update.
[        ] Artifact Instance of 'LinuxEngineArtifacts' is not required, skipping
update.
[        ] Artifact Instance of 'LinuxFuchsiaSDKArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'MacOSFuchsiaSDKArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'FlutterRunnerSDKArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'FlutterRunnerDebugSymbols' is not required,
skipping update.
[  +87 ms] executing: /Users/ken/Library/Android/sdk/platform-tools/adb devices
-l
[  +17 ms] executing: sysctl hw.optional.arm64
[   +7 ms] Exit code 1 from: sysctl hw.optional.arm64
[        ] sysctl: unknown oid 'hw.optional.arm64'
[        ] executing: xcrun xcodebuild -version
[ +270 ms] Exit code 0 from: xcrun xcodebuild -version
[        ] Xcode 13.4
           Build version 13F17a
[   +4 ms] executing: xcrun xcdevice list --timeout 2
[   +4 ms] xcrun simctl list --json devices
[        ] executing: xcrun simctl list --json devices
[   +6 ms] executing: xcrun simctl list
[ +181 ms] Exit code 0 from: xcrun simctl list
[   +1 ms] == Device Types ==
           iPhone 4s (com.apple.CoreSimulator.SimDeviceType.iPhone-4s)
           iPhone 5 (com.apple.CoreSimulator.SimDeviceType.iPhone-5)
           iPhone 5s (com.apple.CoreSimulator.SimDeviceType.iPhone-5s)
           iPhone 6 Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-6-Plus)
           iPhone 6 (com.apple.CoreSimulator.SimDeviceType.iPhone-6)
           iPhone 6s (com.apple.CoreSimulator.SimDeviceType.iPhone-6s)
           iPhone 6s Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-6s-Plus)
           iPhone SE (1st generation)
           (com.apple.CoreSimulator.SimDeviceType.iPhone-SE)
           iPhone 7 (com.apple.CoreSimulator.SimDeviceType.iPhone-7)
           iPhone 7 Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-7-Plus)
           iPhone 8 (com.apple.CoreSimulator.SimDeviceType.iPhone-8)
           iPhone 8 Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-8-Plus)
           iPhone X (com.apple.CoreSimulator.SimDeviceType.iPhone-X)
           iPhone Xs (com.apple.CoreSimulator.SimDeviceType.iPhone-XS)
           iPhone Xs Max (com.apple.CoreSimulator.SimDeviceType.iPhone-XS-Max)
           iPhone Xʀ (com.apple.CoreSimulator.SimDeviceType.iPhone-XR)
           iPhone 11 (com.apple.CoreSimulator.SimDeviceType.iPhone-11)
           iPhone 11 Pro (com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro)
           iPhone 11 Pro Max
           (com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro-Max)
           iPhone SE (2nd generation)
           (com.apple.CoreSimulator.SimDeviceType.iPhone-SE--2nd-generation-)
           iPhone 12 mini (com.apple.CoreSimulator.SimDeviceType.iPhone-12-mini)
           iPhone 12 (com.apple.CoreSimulator.SimDeviceType.iPhone-12)
           iPhone 12 Pro (com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro)
           iPhone 12 Pro Max
           (com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro-Max)
           iPhone 13 Pro (com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro)
           iPhone 13 Pro Max
           (com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro-Max)
           iPhone 13 mini (com.apple.CoreSimulator.SimDeviceType.iPhone-13-mini)
           iPhone 13 (com.apple.CoreSimulator.SimDeviceType.iPhone-13)
           iPhone SE (3rd generation)
           (com.apple.CoreSimulator.SimDeviceType.iPhone-SE-3rd-generation)
           iPod touch (7th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPod-touch--7th-generation-)
           iPad 2 (com.apple.CoreSimulator.SimDeviceType.iPad-2)
           iPad Retina (com.apple.CoreSimulator.SimDeviceType.iPad-Retina)
           iPad Air (com.apple.CoreSimulator.SimDeviceType.iPad-Air)
           iPad mini 2 (com.apple.CoreSimulator.SimDeviceType.iPad-mini-2)
           iPad mini 3 (com.apple.CoreSimulator.SimDeviceType.iPad-mini-3)
           iPad mini 4 (com.apple.CoreSimulator.SimDeviceType.iPad-mini-4)
           iPad Air 2 (com.apple.CoreSimulator.SimDeviceType.iPad-Air-2)
           iPad Pro (9.7-inch)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--9-7-inch-)
           iPad Pro (12.9-inch) (1st generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro)
           iPad (5th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad--5th-generation-)
           iPad Pro (12.9-inch) (2nd generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--12-9-inch---2nd-gene
           ration-)
           iPad Pro (10.5-inch)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--10-5-inch-)
           iPad (6th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad--6th-generation-)
           iPad (7th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad--7th-generation-)
           iPad Pro (11-inch) (1st generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--11-inch-)
           iPad Pro (12.9-inch) (3rd generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--12-9-inch---3rd-gene
           ration-)
           iPad Pro (11-inch) (2nd generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--11-inch---2nd-genera
           tion-)
           iPad Pro (12.9-inch) (4th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--12-9-inch---4th-gene
           ration-)
           iPad mini (5th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-mini--5th-generation-)
           iPad Air (3rd generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Air--3rd-generation-)
           iPad (8th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad--8th-generation-)
           iPad (9th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-9th-generation)
           iPad Air (4th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Air--4th-generation-)
           iPad Pro (11-inch) (3rd generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro-11-inch-3rd-generatio
           n)
           iPad Pro (12.9-inch) (5th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro-12-9-inch-5th-generat
           ion)
           iPad Air (5th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Air-5th-generation)
           iPad mini (6th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-mini-6th-generation)
           Apple TV (com.apple.CoreSimulator.SimDeviceType.Apple-TV-1080p)
           Apple TV 4K (com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-4K)
           Apple TV 4K (at 1080p)
           (com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-1080p)
           Apple TV 4K (2nd generation)
           (com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2nd-generation-4K)
           Apple TV 4K (at 1080p) (2nd generation)
           (com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2nd-generation-108
           0p)
           Apple Watch - 38mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-38mm)
           Apple Watch - 42mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-42mm)
           Apple Watch Series 2 - 38mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-2-38mm)
           Apple Watch Series 2 - 42mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-2-42mm)
           Apple Watch Series 3 - 38mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-3-38mm)
           Apple Watch Series 3 - 42mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-3-42mm)
           Apple Watch Series 4 - 40mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-4-40mm)
           Apple Watch Series 4 - 44mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-4-44mm)
           Apple Watch Series 5 - 40mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-5-40mm)
           Apple Watch Series 5 - 44mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-5-44mm)
           Apple Watch SE - 40mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-SE-40mm)
           Apple Watch SE - 44mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-SE-44mm)
           Apple Watch Series 6 - 40mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-6-40mm)
           Apple Watch Series 6 - 44mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-6-44mm)
           Apple Watch Series 7 - 41mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-7-41mm)
           Apple Watch Series 7 - 45mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-7-45mm)
           == Runtimes ==
           iOS 15.5 (15.5 - 19F70) - com.apple.CoreSimulator.SimRuntime.iOS-15-5
           tvOS 15.4 (15.4 - 19L439) -
           com.apple.CoreSimulator.SimRuntime.tvOS-15-4
           watchOS 8.5 (8.5 - 19T241) -
           com.apple.CoreSimulator.SimRuntime.watchOS-8-5
           == Devices ==
           -- iOS 15.5 --
               iPhone 8 (18811BFB-C258-49EC-AB73-6E9FFF4D75EC) (Shutdown) 
               iPhone 8 Plus (0173A5F1-4288-4C05-AF7F-04964DFB789E) (Shutdown) 
               iPhone 11 (70396614-24D5-4104-A736-08D322BB3FDF) (Shutdown) 
               iPhone 11 Pro (5F56FFED-31C2-4AAF-B960-D4499BEA12DC) (Shutdown) 
               iPhone 11 Pro Max (D865C90F-2860-4E0D-A900-5D744A64D116)
               (Shutdown)
               iPhone 12 mini (3B059333-96F6-433E-87AB-1F1129B17204) (Shutdown) 
               iPhone 12 (052F17AD-D52D-4885-97F8-6CDD27C6640E) (Shutdown) 
               iPhone 12 Pro (A39824F9-D33A-458D-9331-1F3925B218B9) (Shutdown) 
               iPhone 12 Pro Max (DB4021F0-3F6D-49E9-B911-2BD44BA3074F)
               (Shutdown)
               iPhone 13 Pro (E5026D1F-DC9E-426F-BA7B-3AA93451E4FC) (Shutdown) 
               iPhone 13 Pro Max (048108E4-D2A3-48FF-A4F5-7FF86434839F)
               (Shutdown)
               iPhone 13 mini (80C8B9CB-8814-4FF5-9CF6-94F6F7077A34) (Shutdown) 
               iPhone 13 (3631D8FA-C8D7-4BF5-9C0B-D1CA0FCB767F) (Shutdown) 
               iPhone SE (3rd generation) (DE894E91-DCB8-4BE0-93B5-34B787114A91)
               (Shutdown)
               iPod touch (7th generation)
               (A985A663-9AFD-4DD1-BBE9-981AA630F00D) (Shutdown)
               iPad Pro (9.7-inch) (22EB516F-8480-4217-9935-2F007AA9F42C)
               (Shutdown)
               iPad (9th generation) (5C739224-2EDE-4CE6-ADB5-54B5F8B11BEF)
               (Shutdown)
               iPad Pro (11-inch) (3rd generation)
               (2D84767E-BC58-4AFD-AFFD-6A9D7670B16B) (Shutdown)
               iPad Pro (12.9-inch) (5th generation)
               (8C7E6ED4-9F9B-4675-BEF4-736C7544375C) (Shutdown)
               iPad Air (5th generation) (FA9FA89C-AC7B-41B4-8CBF-1583B52F1662)
               (Shutdown)
               iPad mini (6th generation) (25F13879-BE70-4256-BE00-E5EDBD9B2D3E)
               (Shutdown)
           -- tvOS 15.4 --
               Apple TV (07E03BEA-CA86-41A9-B410-61ADDAEB8647) (Shutdown) 
               Apple TV 4K (2nd generation)
               (ADC10806-83B1-4874-B27B-BD557B2589A5) (Shutdown)
               Apple TV 4K (at 1080p) (2nd generation)
               (F160B929-761C-4736-B36B-F0172B2018A1) (Shutdown)
           -- watchOS 8.5 --
               Apple Watch Series 5 - 40mm
               (64A75137-3482-4AB5-A821-FBC0AAA57C45) (Shutdown)
               Apple Watch Series 5 - 44mm
               (24C02FB0-7E3B-4CC0-9BCB-7683D67F611A) (Shutdown)
               Apple Watch Series 6 - 40mm
               (F86B0909-88A3-4088-ACD0-084A9C753974) (Shutdown)
               Apple Watch Series 6 - 44mm
               (F525CACE-0538-4101-9BFF-EE9BBB57439E) (Shutdown)
               Apple Watch Series 7 - 41mm
               (51B4BC91-1DF6-4316-A25D-4D98A1080B92) (Shutdown)
               Apple Watch Series 7 - 45mm
               (890EB1B4-A249-4890-86BF-1CDF11DC3F4C) (Shutdown)
           -- Unavailable: com.apple.CoreSimulator.SimRuntime.iOS-15-2 --
               iPhone 8 (3C9AE000-CCEF-4DE7-8BE4-0AC053511EE1) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 8 Plus (4E90F5C3-4D0A-4802-A3A9-AFA660ED4702) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 11 (4D8CD72D-6935-4594-AB91-5DFBCB69A388) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 11 Pro (69847AAD-F3DC-4D4C-8E1A-2BBD620D5DD6) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 11 Pro Max (5A954F8E-B939-4BCD-9F7F-C970E8602AE8)
               (Shutdown) (unavailable, runtime profile not found)
               iPhone SE (2nd generation) (1E7FEB58-2102-4792-ADE0-2275CCA8E9B1)
               (Shutdown) (unavailable, runtime profile not found)
               iPhone 12 mini (D50577CF-EB32-40B2-A7A8-CF646059781C) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 12 (7E9E0CC7-1A72-4148-876C-F13A01227304) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 12 Pro (DA3845B9-4BCA-4414-9B1D-436AD61F8819) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 12 Pro Max (49BFF121-F815-4573-A517-0905B53FF113)
               (Shutdown) (unavailable, runtime profile not found)
               iPhone 13 Pro (B15947C1-7D56-4DC6-B591-4A0CFAE8814F) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 13 Pro Max (801D6BE8-2F18-4337-A817-19A87902A579)
               (Shutdown) (unavailable, runtime profile not found)
               iPhone 13 mini (77F365B1-0E60-412F-80DF-DC0568BDB52A) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 13 (368C2A57-CC77-4BFA-81D9-62DD16F9354B) (Shutdown)
               (unavailable, runtime profile not found)
               iPod touch (7th generation)
               (C7C2B69A-59AE-4530-86A1-475A1116C71E) (Shutdown) (unavailable,
               runtime profile not found)
               iPad Pro (9.7-inch) (1E71062D-928A-4058-A90A-36608C4553AD)
               (Shutdown) (unavailable, runtime profile not found)
               iPad (9th generation) (94012AA4-0140-4EFE-ACE8-63BBAB147A0D)
               (Shutdown) (unavailable, runtime profile not found)
               iPad Air (4th generation) (5FA2692B-6D94-46FF-9FF9-8DD8BF1F0EF0)
               (Shutdown) (unavailable, runtime profile not found)
               iPad Pro (11-inch) (3rd generation)
               (CA638B36-C00D-45F5-B88C-DCBF8564FC55) (Shutdown) (unavailable,
               runtime profile not found)
               iPad Pro (12.9-inch) (5th generation)
               (29E60055-6766-4F29-9529-4B39FECDA921) (Shutdown) (unavailable,
               runtime profile not found)
               iPad mini (6th generation) (D47447BF-D325-49F0-8120-BFABB3158FD2)
               (Shutdown) (unavailable, runtime profile not found)
           -- Unavailable: com.apple.CoreSimulator.SimRuntime.tvOS-15-2 --
               Apple TV (F0D148A6-95E5-4C2B-AAD9-20B343F581F7) (Shutdown)
               (unavailable, runtime profile not found)
               Apple TV 4K (2nd generation)
               (9F4EC24E-D238-4FB8-A949-BE0B64852223) (Shutdown) (unavailable,
               runtime profile not found)
               Apple TV 4K (at 1080p) (2nd generation)
               (8E300EEC-2A09-4D34-941D-35E3043F28AC) (Shutdown) (unavailable,
               runtime profile not found)
           -- Unavailable: com.apple.CoreSimulator.SimRuntime.watchOS-8-3 --
               Apple Watch Series 5 - 40mm
               (9535A885-DB9F-4928-8225-4E43C09A72C3) (Shutdown) (unavailable,
               runtime profile not found)
               Apple Watch Series 5 - 44mm
               (96916268-CA7A-4B02-A34B-F735689703F8) (Shutdown) (unavailable,
               runtime profile not found)
               Apple Watch Series 6 - 40mm
               (64A76DC4-C517-4C5A-A3FD-A9DA39B05BA6) (Shutdown) (unavailable,
               runtime profile not found)
               Apple Watch Series 6 - 44mm
               (257BA6A9-9B49-4377-93D4-81DE64354F93) (Shutdown) (unavailable,
               runtime profile not found)
               Apple Watch Series 7 - 41mm
               (591F5F99-3035-4FDD-BE1F-F5C22BF8C6CB) (Shutdown) (unavailable,
               runtime profile not found)
               Apple Watch Series 7 - 45mm
               (7D056D33-57EA-47CB-9DC0-51867464EAF6) (Shutdown) (unavailable,
               runtime profile not found)
           == Device Pairs ==
           E3493809-5950-4040-8D3F-B4E3510FE138 (active, disconnected)
               Watch: Apple Watch Series 5 - 40mm
               (64A75137-3482-4AB5-A821-FBC0AAA57C45) (Shutdown)
               Phone: iPhone 12 Pro (A39824F9-D33A-458D-9331-1F3925B218B9)
               (Shutdown)
           62CC4BEE-A555-4CF1-9455-310BD9CDCFF5 (active, disconnected)
               Watch: Apple Watch Series 5 - 44mm
               (24C02FB0-7E3B-4CC0-9BCB-7683D67F611A) (Shutdown)
               Phone: iPhone 12 Pro Max (DB4021F0-3F6D-49E9-B911-2BD44BA3074F)
               (Shutdown)
           1FB9F4D6-A284-4F1C-9CEA-EF32B6AB8FDB (active, disconnected)
               Watch: Apple Watch Series 6 - 40mm
               (F86B0909-88A3-4088-ACD0-084A9C753974) (Shutdown)
               Phone: iPhone 13 Pro (E5026D1F-DC9E-426F-BA7B-3AA93451E4FC)
               (Shutdown)
           24FDEFA3-9801-4C0C-8CE2-2523B5872B99 (active, disconnected)
               Watch: Apple Watch Series 6 - 44mm
               (F525CACE-0538-4101-9BFF-EE9BBB57439E) (Shutdown)
               Phone: iPhone 13 Pro Max (048108E4-D2A3-48FF-A4F5-7FF86434839F)
               (Shutdown)
           6294322F-6302-41E4-AC52-78F33B9D0FE1 (active, disconnected)
               Watch: Apple Watch Series 7 - 41mm
               (51B4BC91-1DF6-4316-A25D-4D98A1080B92) (Shutdown)
               Phone: iPhone 13 mini (80C8B9CB-8814-4FF5-9CF6-94F6F7077A34)
               (Shutdown)
           4A1E91E1-185E-4FC1-BFDB-91B847FB36C0 (active, disconnected)
               Watch: Apple Watch Series 7 - 45mm
               (890EB1B4-A249-4890-86BF-1CDF11DC3F4C) (Shutdown)
               Phone: iPhone 13 (3631D8FA-C8D7-4BF5-9C0B-D1CA0FCB767F)
               (Shutdown)
           0E153606-A902-4BFF-862C-AEB6C47DC7C3 (unavailable)
               Watch: Apple Watch Series 5 - 40mm
               (9535A885-DB9F-4928-8225-4E43C09A72C3) (Shutdown)
               Phone: iPhone 12 Pro (DA3845B9-4BCA-4414-9B1D-436AD61F8819)
               (Shutdown)
           42B96B43-360C-4D26-86C6-ED51809564F4 (unavailable)
               Watch: Apple Watch Series 5 - 44mm
               (96916268-CA7A-4B02-A34B-F735689703F8) (Shutdown)
               Phone: iPhone 12 Pro Max (49BFF121-F815-4573-A517-0905B53FF113)
               (Shutdown)
           9A11A9EE-D68D-4F4C-AB6E-D183ED49806D (unavailable)
               Watch: Apple Watch Series 6 - 40mm
               (64A76DC4-C517-4C5A-A3FD-A9DA39B05BA6) (Shutdown)
               Phone: iPhone 13 Pro (B15947C1-7D56-4DC6-B591-4A0CFAE8814F)
               (Shutdown)
           C85D6AF7-412F-40B6-945E-7271FDE9C24F (unavailable)
               Watch: Apple Watch Series 6 - 44mm
               (257BA6A9-9B49-4377-93D4-81DE64354F93) (Shutdown)
               Phone: iPhone 13 Pro Max (801D6BE8-2F18-4337-A817-19A87902A579)
               (Shutdown)
           39AA247E-895E-4498-A55A-47A716EEB547 (unavailable)
               Watch: Apple Watch Series 7 - 41mm
               (591F5F99-3035-4FDD-BE1F-F5C22BF8C6CB) (Shutdown)
               Phone: iPhone 13 mini (77F365B1-0E60-412F-80DF-DC0568BDB52A)
               (Shutdown)
           2E005628-9805-412D-B163-092D0A79A0DF (unavailable)
               Watch: Apple Watch Series 7 - 45mm
               (7D056D33-57EA-47CB-9DC0-51867464EAF6) (Shutdown)
               Phone: iPhone 13 (368C2A57-CC77-4BFA-81D9-62DD16F9354B)
               (Shutdown)
[ +145 ms] List of devices attached
                    LMQ610TA3526ef8        device usb:337641472X
                    product:cv5a_lao_com model:LM_Q610_FGN_ device:cv5a
                    transport_id:3
[ +239 ms] {
                      "devices" : {
                        "com.apple.CoreSimulator.SimRuntime.watchOS-8-5" : [
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/64A75137-3482-4AB5-A821-FBC0AAA57C45\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/64A7513
                            7-3482-4AB5-A821-FBC0AAA57C45",
                            "udid" : "64A75137-3482-4AB5-A821-FBC0AAA57C45",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-S
                            eries-5-40mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 5 - 40mm"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/24C02FB0-7E3B-4CC0-9BCB-7683D67F611A\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/24C02FB
                            0-7E3B-4CC0-9BCB-7683D67F611A",
                            "udid" : "24C02FB0-7E3B-4CC0-9BCB-7683D67F611A",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-S
                            eries-5-44mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 5 - 44mm"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/F86B0909-88A3-4088-ACD0-084A9C753974\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/F86B090
                            9-88A3-4088-ACD0-084A9C753974",
                            "udid" : "F86B0909-88A3-4088-ACD0-084A9C753974",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-S
                            eries-6-40mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 6 - 40mm"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/F525CACE-0538-4101-9BFF-EE9BBB57439E\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/F525CAC
                            E-0538-4101-9BFF-EE9BBB57439E",
                            "udid" : "F525CACE-0538-4101-9BFF-EE9BBB57439E",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-S
                            eries-6-44mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 6 - 44mm"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/51B4BC91-1DF6-4316-A25D-4D98A1080B92\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/51B4BC9
                            1-1DF6-4316-A25D-4D98A1080B92",
                            "udid" : "51B4BC91-1DF6-4316-A25D-4D98A1080B92",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-S
                            eries-7-41mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 7 - 41mm"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/890EB1B4-A249-4890-86BF-1CDF11DC3F4C\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/890EB1B
                            4-A249-4890-86BF-1CDF11DC3F4C",
                            "udid" : "890EB1B4-A249-4890-86BF-1CDF11DC3F4C",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-S
                            eries-7-45mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 7 - 45mm"
                          }
                        ],
                        "com.apple.CoreSimulator.SimRuntime.tvOS-15-4" : [
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/07E03BEA-CA86-41A9-B410-61ADDAEB8647\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/07E03BE
                            A-CA86-41A9-B410-61ADDAEB8647",
                            "udid" : "07E03BEA-CA86-41A9-B410-61ADDAEB8647",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-TV-1080
                            p",
                            "state" : "Shutdown",
                            "name" : "Apple TV"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/ADC10806-83B1-4874-B27B-BD557B2589A5\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/ADC1080
                            6-83B1-4874-B27B-BD557B2589A5",
                            "udid" : "ADC10806-83B1-4874-B27B-BD557B2589A5",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2
                            nd-generation-4K",
                            "state" : "Shutdown",
                            "name" : "Apple TV 4K (2nd generation)"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/F160B929-761C-4736-B36B-F0172B2018A1\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/F160B92
                            9-761C-4736-B36B-F0172B2018A1",
                            "udid" : "F160B929-761C-4736-B36B-F0172B2018A1",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2
                            nd-generation-1080p",
                            "state" : "Shutdown",
                            "name" : "Apple TV 4K (at 1080p) (2nd generation)"
                          }
                        ],
                        "com.apple.CoreSimulator.SimRuntime.iOS-15-2" : [
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/3C9AE000-CCEF-4DE7-8BE4-0AC053511EE1\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/3C9AE00
                            0-CCEF-4DE7-8BE4-0AC053511EE1",
                            "udid" : "3C9AE000-CCEF-4DE7-8BE4-0AC053511EE1",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-8",
                            "state" : "Shutdown",
                            "name" : "iPhone 8"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/4E90F5C3-4D0A-4802-A3A9-AFA660ED4702\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/4E90F5C
                            3-4D0A-4802-A3A9-AFA660ED4702",
                            "udid" : "4E90F5C3-4D0A-4802-A3A9-AFA660ED4702",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-8-Plus
                            ",
                            "state" : "Shutdown",
                            "name" : "iPhone 8 Plus"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/4D8CD72D-6935-4594-AB91-5DFBCB69A388\/data",
                            "dataPathSize" : 1036697600,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/4D8CD72
                            D-6935-4594-AB91-5DFBCB69A388",
                            "udid" : "4D8CD72D-6935-4594-AB91-5DFBCB69A388",
                            "isAvailable" : false,
                            "logPathSize" : 352256,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-11",
                            "state" : "Shutdown",
                            "name" : "iPhone 11"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/69847AAD-F3DC-4D4C-8E1A-2BBD620D5DD6\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/69847AA
                            D-F3DC-4D4C-8E1A-2BBD620D5DD6",
                            "udid" : "69847AAD-F3DC-4D4C-8E1A-2BBD620D5DD6",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro
                            ",
                            "state" : "Shutdown",
                            "name" : "iPhone 11 Pro"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/5A954F8E-B939-4BCD-9F7F-C970E8602AE8\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/5A954F8
                            E-B939-4BCD-9F7F-C970E8602AE8",
                            "udid" : "5A954F8E-B939-4BCD-9F7F-C970E8602AE8",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro
                            -Max",
                            "state" : "Shutdown",
                            "name" : "iPhone 11 Pro Max"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/1E7FEB58-2102-4792-ADE0-2275CCA8E9B1\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/1E7FEB5
                            8-2102-4792-ADE0-2275CCA8E9B1",
                            "udid" : "1E7FEB58-2102-4792-ADE0-2275CCA8E9B1",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-SE--2n
                            d-generation-",
                            "state" : "Shutdown",
                            "name" : "iPhone SE (2nd generation)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/D50577CF-EB32-40B2-A7A8-CF646059781C\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/D50577C
                            F-EB32-40B2-A7A8-CF646059781C",
                            "udid" : "D50577CF-EB32-40B2-A7A8-CF646059781C",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-12-min
                            i",
                            "state" : "Shutdown",
                            "name" : "iPhone 12 mini"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/7E9E0CC7-1A72-4148-876C-F13A01227304\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/7E9E0CC
                            7-1A72-4148-876C-F13A01227304",
                            "udid" : "7E9E0CC7-1A72-4148-876C-F13A01227304",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-12",
                            "state" : "Shutdown",
                            "name" : "iPhone 12"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/DA3845B9-4BCA-4414-9B1D-436AD61F8819\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/DA3845B
                            9-4BCA-4414-9B1D-436AD61F8819",
                            "udid" : "DA3845B9-4BCA-4414-9B1D-436AD61F8819",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro
                            ",
                            "state" : "Shutdown",
                            "name" : "iPhone 12 Pro"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/49BFF121-F815-4573-A517-0905B53FF113\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/49BFF12
                            1-F815-4573-A517-0905B53FF113",
                            "udid" : "49BFF121-F815-4573-A517-0905B53FF113",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro
                            -Max",
                            "state" : "Shutdown",
                            "name" : "iPhone 12 Pro Max"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/B15947C1-7D56-4DC6-B591-4A0CFAE8814F\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/B15947C
                            1-7D56-4DC6-B591-4A0CFAE8814F",
                            "udid" : "B15947C1-7D56-4DC6-B591-4A0CFAE8814F",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro
                            ",
                            "state" : "Shutdown",
                            "name" : "iPhone 13 Pro"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/801D6BE8-2F18-4337-A817-19A87902A579\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/801D6BE
                            8-2F18-4337-A817-19A87902A579",
                            "udid" : "801D6BE8-2F18-4337-A817-19A87902A579",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro
                            -Max",
                            "state" : "Shutdown",
                            "name" : "iPhone 13 Pro Max"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/77F365B1-0E60-412F-80DF-DC0568BDB52A\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/77F365B
                            1-0E60-412F-80DF-DC0568BDB52A",
                            "udid" : "77F365B1-0E60-412F-80DF-DC0568BDB52A",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-13-min
                            i",
                            "state" : "Shutdown",
                            "name" : "iPhone 13 mini"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/368C2A57-CC77-4BFA-81D9-62DD16F9354B\/data",
                            "dataPathSize" : 1363148800,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/368C2A5
                            7-CC77-4BFA-81D9-62DD16F9354B",
                            "udid" : "368C2A57-CC77-4BFA-81D9-62DD16F9354B",
                            "isAvailable" : false,
                            "logPathSize" : 434176,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-13",
                            "state" : "Shutdown",
                            "name" : "iPhone 13"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/C7C2B69A-59AE-4530-86A1-475A1116C71E\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/C7C2B69
                            A-59AE-4530-86A1-475A1116C71E",
                            "udid" : "C7C2B69A-59AE-4530-86A1-475A1116C71E",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPod-touch--7
                            th-generation-",
                            "state" : "Shutdown",
                            "name" : "iPod touch (7th generation)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/1E71062D-928A-4058-A90A-36608C4553AD\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/1E71062
                            D-928A-4058-A90A-36608C4553AD",
                            "udid" : "1E71062D-928A-4058-A90A-36608C4553AD",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPad-Pro--9-7
                            -inch-",
                            "state" : "Shutdown",
                            "name" : "iPad Pro (9.7-inch)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/94012AA4-0140-4EFE-ACE8-63BBAB147A0D\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/94012AA
                            4-0140-4EFE-ACE8-63BBAB147A0D",
                            "udid" : "94012AA4-0140-4EFE-ACE8-63BBAB147A0D",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPad-9th-gene
                            ration",
                            "state" : "Shutdown",
                            "name" : "iPad (9th generation)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/5FA2692B-6D94-46FF-9FF9-8DD8BF1F0EF0\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/5FA2692
                            B-6D94-46FF-9FF9-8DD8BF1F0EF0",
                            "udid" : "5FA2692B-6D94-46FF-9FF9-8DD8BF1F0EF0",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPad-Air--4th
                            -generation-",
                            "state" : "Shutdown",
                            "name" : "iPad Air (4th generation)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/CA638B36-C00D-45F5-B88C-DCBF8564FC55\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/CA638B3
                            6-C00D-45F5-B88C-DCBF8564FC55",
                            "udid" : "CA638B36-C00D-45F5-B88C-DCBF8564FC55",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPad-Pro-11-i
                            nch-3rd-generation",
                            "state" : "Shutdown",
                            "name" : "iPad Pro (11-inch) (3rd generation)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/29E60055-6766-4F29-9529-4B39FECDA921\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/29E6005
                            5-6766-4F29-9529-4B39FECDA921",
                            "udid" : "29E60055-6766-4F29-9529-4B39FECDA921",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPad-Pro-12-9
                            -inch-5th-generation",
                            "state" : "Shutdown",
                            "name" : "iPad Pro (12.9-inch) (5th generation)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/D47447BF-D325-49F0-8120-BFABB3158FD2\/data",
                            "dataPathSize" : 13312000,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/D47447B
                            F-D325-49F0-8120-BFABB3158FD2",
                            "udid" : "D47447BF-D325-49F0-8120-BFABB3158FD2",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPad-mini-6th
                            -generation",
                            "state" : "Shutdown",
                            "name" : "iPad mini (6th generation)"
                          }
                        ],
                        "com.apple.CoreSimulator.SimRuntime.iOS-15-5" : [
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/18811BFB-C258-49EC-AB73-6E9FFF4D75EC\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/18811BF
                            B-C258-49EC-AB73-6E9FFF4D75EC",
                            "udid" : "18811BFB-C258-49EC-AB73-6E9FFF4D75EC",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-8",
                            "state" : "Shutdown",
                            "name" : "iPhone 8"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/0173A5F1-4288-4C05-AF7F-04964DFB789E\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/0173A5F
                            1-4288-4C05-AF7F-04964DFB789E",
                            "udid" : "0173A5F1-4288-4C05-AF7F-04964DFB789E",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-8-Plus
                            ",
                            "state" : "Shutdown",
                            "name" : "iPhone 8 Plus"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/70396614-24D5-4104-A736-08D322BB3FDF\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/7039661
                            4-24D5-4104-A736-08D322BB3FDF",
                            "udid" : "70396614-24D5-4104-A736-08D322BB3FDF",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-11",
                            "state" : "Shutdown",
                            "name" : "iPhone 11"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/5F56FFED-31C2-4AAF-B960-D4499BEA12DC\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/5F56FFE
                            D-31C2-4AAF-B960-D4499BEA12DC",
                            "udid" : "5F56FFED-31C2-4AAF-B960-D4499BEA12DC",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro
                            ",
                            "state" : "Shutdown",
                            "name" : "iPhone 11 Pro"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/D865C90F-2860-4E0D-A900-5D744A64D116\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/D865C90
                            F-2860-4E0D-A900-5D744A64D116",
                            "udid" : "D865C90F-2860-4E0D-A900-5D744A64D116",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro
                            -Max",
                            "state" : "Shutdown",
                            "name" : "iPhone 11 Pro Max"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/3B059333-96F6-433E-87AB-1F1129B17204\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/3B05933
                            3-96F6-433E-87AB-1F1129B17204",
                            "udid" : "3B059333-96F6-433E-87AB-1F1129B17204",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-12-min
                            i",
                            "state" : "Shutdown",
                            "name" : "iPhone 12 mini"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/052F17AD-D52D-4885-97F8-6CDD27C6640E\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/052F17A
                            D-D52D-4885-97F8-6CDD27C6640E",
                            "udid" : "052F17AD-D52D-4885-97F8-6CDD27C6640E",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-12",
                            "state" : "Shutdown",
                            "name" : "iPhone 12"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/A39824F9-D33A-458D-9331-1F3925B218B9\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/A39824F
                            9-D33A-458D-9331-1F3925B218B9",
                            "udid" : "A39824F9-D33A-458D-9331-1F3925B218B9",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro
                            ",
                            "state" : "Shutdown",
                            "name" : "iPhone 12 Pro"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/DB4021F0-3F6D-49E9-B911-2BD44BA3074F\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/DB4021F
                            0-3F6D-49E9-B911-2BD44BA3074F",
                            "udid" : "DB4021F0-3F6D-49E9-B911-2BD44BA3074F",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro
                            -Max",
                            "state" : "Shutdown",
                            "name" : "iPhone 12 Pro Max"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/E5026D1F-DC9E-426F-BA7B-3AA93451E4FC\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/E5026D1
                            F-DC9E-426F-BA7B-3AA93451E4FC",
                            "udid" : "E5026D1F-DC9E-426F-BA7B-3AA93451E4FC",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro
                            ",
                            "state" : "Shutdown",
                            "name" : "iPhone 13 Pro"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/048108E4-D2A3-48FF-A4F5-7FF86434839F\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/048108E
                            4-D2A3-48FF-A4F5-7FF86434839F",
                            "udid" : "048108E4-D2A3-48FF-A4F5-7FF86434839F",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro
                            -Max",
                            "state" : "Shutdown",
                            "name" : "iPhone 13 Pro Max"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/80C8B9CB-8814-4FF5-9CF6-94F6F7077A34\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/80C8B9C
                            B-8814-4FF5-9CF6-94F6F7077A34",
                            "udid" : "80C8B9CB-8814-4FF5-9CF6-94F6F7077A34",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-13-min
                            i",
                            "state" : "Shutdown",
                            "name" : "iPhone 13 mini"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/3631D8FA-C8D7-4BF5-9C0B-D1CA0FCB767F\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/3631D8F
                            A-C8D7-4BF5-9C0B-D1CA0FCB767F",
                            "udid" : "3631D8FA-C8D7-4BF5-9C0B-D1CA0FCB767F",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-13",
                            "state" : "Shutdown",
                            "name" : "iPhone 13"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/DE894E91-DCB8-4BE0-93B5-34B787114A91\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/DE894E9
                            1-DCB8-4BE0-93B5-34B787114A91",
                            "udid" : "DE894E91-DCB8-4BE0-93B5-34B787114A91",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPhone-SE-3rd
                            -generation",
                            "state" : "Shutdown",
                            "name" : "iPhone SE (3rd generation)"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/A985A663-9AFD-4DD1-BBE9-981AA630F00D\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/A985A66
                            3-9AFD-4DD1-BBE9-981AA630F00D",
                            "udid" : "A985A663-9AFD-4DD1-BBE9-981AA630F00D",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPod-touch--7
                            th-generation-",
                            "state" : "Shutdown",
                            "name" : "iPod touch (7th generation)"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/22EB516F-8480-4217-9935-2F007AA9F42C\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/22EB516
                            F-8480-4217-9935-2F007AA9F42C",
                            "udid" : "22EB516F-8480-4217-9935-2F007AA9F42C",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPad-Pro--9-7
                            -inch-",
                            "state" : "Shutdown",
                            "name" : "iPad Pro (9.7-inch)"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/5C739224-2EDE-4CE6-ADB5-54B5F8B11BEF\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/5C73922
                            4-2EDE-4CE6-ADB5-54B5F8B11BEF",
                            "udid" : "5C739224-2EDE-4CE6-ADB5-54B5F8B11BEF",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPad-9th-gene
                            ration",
                            "state" : "Shutdown",
                            "name" : "iPad (9th generation)"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/2D84767E-BC58-4AFD-AFFD-6A9D7670B16B\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/2D84767
                            E-BC58-4AFD-AFFD-6A9D7670B16B",
                            "udid" : "2D84767E-BC58-4AFD-AFFD-6A9D7670B16B",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPad-Pro-11-i
                            nch-3rd-generation",
                            "state" : "Shutdown",
                            "name" : "iPad Pro (11-inch) (3rd generation)"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/8C7E6ED4-9F9B-4675-BEF4-736C7544375C\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/8C7E6ED
                            4-9F9B-4675-BEF4-736C7544375C",
                            "udid" : "8C7E6ED4-9F9B-4675-BEF4-736C7544375C",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPad-Pro-12-9
                            -inch-5th-generation",
                            "state" : "Shutdown",
                            "name" : "iPad Pro (12.9-inch) (5th generation)"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/FA9FA89C-AC7B-41B4-8CBF-1583B52F1662\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/FA9FA89
                            C-AC7B-41B4-8CBF-1583B52F1662",
                            "udid" : "FA9FA89C-AC7B-41B4-8CBF-1583B52F1662",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPad-Air-5th-
                            generation",
                            "state" : "Shutdown",
                            "name" : "iPad Air (5th generation)"
                          },
                          {
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/25F13879-BE70-4256-BE00-E5EDBD9B2D3E\/data",
                            "dataPathSize" : 13316096,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/25F1387
                            9-BE70-4256-BE00-E5EDBD9B2D3E",
                            "udid" : "25F13879-BE70-4256-BE00-E5EDBD9B2D3E",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.iPad-mini-6th
                            -generation",
                            "state" : "Shutdown",
                            "name" : "iPad mini (6th generation)"
                          }
                        ],
                        "com.apple.CoreSimulator.SimRuntime.tvOS-15-2" : [
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/F0D148A6-95E5-4C2B-AAD9-20B343F581F7\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/F0D148A
                            6-95E5-4C2B-AAD9-20B343F581F7",
                            "udid" : "F0D148A6-95E5-4C2B-AAD9-20B343F581F7",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-TV-1080
                            p",
                            "state" : "Shutdown",
                            "name" : "Apple TV"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/9F4EC24E-D238-4FB8-A949-BE0B64852223\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/9F4EC24
                            E-D238-4FB8-A949-BE0B64852223",
                            "udid" : "9F4EC24E-D238-4FB8-A949-BE0B64852223",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2
                            nd-generation-4K",
                            "state" : "Shutdown",
                            "name" : "Apple TV 4K (2nd generation)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/8E300EEC-2A09-4D34-941D-35E3043F28AC\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/8E300EE
                            C-2A09-4D34-941D-35E3043F28AC",
                            "udid" : "8E300EEC-2A09-4D34-941D-35E3043F28AC",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2
                            nd-generation-1080p",
                            "state" : "Shutdown",
                            "name" : "Apple TV 4K (at 1080p) (2nd generation)"
                          }
                        ],
                        "com.apple.CoreSimulator.SimRuntime.watchOS-8-3" : [
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/9535A885-DB9F-4928-8225-4E43C09A72C3\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/9535A88
                            5-DB9F-4928-8225-4E43C09A72C3",
                            "udid" : "9535A885-DB9F-4928-8225-4E43C09A72C3",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-S
                            eries-5-40mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 5 - 40mm"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/96916268-CA7A-4B02-A34B-F735689703F8\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/9691626
                            8-CA7A-4B02-A34B-F735689703F8",
                            "udid" : "96916268-CA7A-4B02-A34B-F735689703F8",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-S
                            eries-5-44mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 5 - 44mm"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/64A76DC4-C517-4C5A-A3FD-A9DA39B05BA6\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/64A76DC
                            4-C517-4C5A-A3FD-A9DA39B05BA6",
                            "udid" : "64A76DC4-C517-4C5A-A3FD-A9DA39B05BA6",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-S
                            eries-6-40mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 6 - 40mm"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/257BA6A9-9B49-4377-93D4-81DE64354F93\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/257BA6A
                            9-9B49-4377-93D4-81DE64354F93",
                            "udid" : "257BA6A9-9B49-4377-93D4-81DE64354F93",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-S
                            eries-6-44mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 6 - 44mm"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/591F5F99-3035-4FDD-BE1F-F5C22BF8C6CB\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/591F5F9
                            9-3035-4FDD-BE1F-F5C22BF8C6CB",
                            "udid" : "591F5F99-3035-4FDD-BE1F-F5C22BF8C6CB",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-S
                            eries-7-41mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 7 - 41mm"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" :
                            "\/Users\/ken\/Library\/Developer\/CoreSimulator\/De
                            vices\/7D056D33-57EA-47CB-9DC0-51867464EAF6\/data",
                            "dataPathSize" : 0,
                            "logPath" :
                            "\/Users\/ken\/Library\/Logs\/CoreSimulator\/7D056D3
                            3-57EA-47CB-9DC0-51867464EAF6",
                            "udid" : "7D056D33-57EA-47CB-9DC0-51867464EAF6",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" :
                            "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-S
                            eries-7-45mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 7 - 45mm"
                          }
                        ]
                      }
                    }
[+3099 ms] [
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone13,1",
                        "identifier" : "3B059333-96F6-433E-87AB-1F1129B17204",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-12-mini-1",
                        "modelName" : "iPhone 12 mini",
                        "name" : "iPhone 12 mini"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone12,5",
                        "identifier" : "D865C90F-2860-4E0D-A900-5D744A64D116",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-11-pro-max-1",
                        "modelName" : "iPhone 11 Pro Max",
                        "name" : "iPhone 11 Pro Max"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone13,4",
                          "identifier" : "DB4021F0-3F6D-49E9-B911-2BD44BA3074F",
                          "architecture" : "x86_64",
                          "modelUTI" : "com.apple.iphone-12-pro-max-1",
                          "modelName" : "iPhone 12 Pro Max",
                          "name" : "iPhone 12 Pro Max"
                        },
                        "modelCode" : "Watch5,4",
                        "identifier" : "24C02FB0-7E3B-4CC0-9BCB-7683D67F611A",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.watch-series5-1",
                        "modelName" : "Apple Watch Series 5 - 44mm",
                        "name" : "Apple Watch Series 5 - 44mm"
                      },
                      {
                        "simulator" : false,
                        "operatingSystemVersion" : "12.4 (21F79)",
                        "interface" : "usb",
                        "available" : true,
                        "platform" : "com.apple.platform.macosx",
                        "modelCode" : "MacBookPro12,1",
                        "identifier" : "95C58049-A66F-5CA1-BABD-6925E2ECE851",
                        "architecture" : "x86_64h",
                        "modelUTI" : "com.apple.macbookpro-13-retina-display",
                        "modelName" : "MacBook Pro",
                        "name" : "My Mac"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone14,2",
                          "identifier" : "E5026D1F-DC9E-426F-BA7B-3AA93451E4FC",
                          "architecture" : "x86_64",
                          "modelUTI" : "com.apple.iphone-13-pro-1",
                          "modelName" : "iPhone 13 Pro",
                          "name" : "iPhone 13 Pro"
                        },
                        "modelCode" : "Watch6,1",
                        "identifier" : "F86B0909-88A3-4088-ACD0-084A9C753974",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.watch-series6-1",
                        "modelName" : "Apple Watch Series 6 - 40mm",
                        "name" : "Apple Watch Series 6 - 40mm"
                      },
                      {
                        "simulator" : false,
                        "operatingSystemVersion" : "15.4.1 (19E258)",
                        "interface" : "usb",
                        "available" : true,
                        "platform" : "com.apple.platform.iphoneos",
                        "modelCode" : "iPhone12,1",
                        "identifier" : "00008030-0004551014E8802E",
                        "architecture" : "arm64e",
                        "modelUTI" : "com.apple.iphone-11-2",
                        "modelName" : "iPhone 11",
                        "name" : "iPhone (2)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad13,17",
                        "identifier" : "FA9FA89C-AC7B-41B4-8CBF-1583B52F1662",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.ipad-air5-1",
                        "modelName" : "iPad Air (5th generation)",
                        "name" : "iPad Air (5th generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone10,5",
                        "identifier" : "0173A5F1-4288-4C05-AF7F-04964DFB789E",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-8-plus-2",
                        "modelName" : "iPhone 8 Plus",
                        "name" : "iPhone 8 Plus"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone12,3",
                        "identifier" : "5F56FFED-31C2-4AAF-B960-D4499BEA12DC",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-11-pro-1",
                        "modelName" : "iPhone 11 Pro",
                        "name" : "iPhone 11 Pro"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad13,5",
                        "identifier" : "2D84767E-BC58-4AFD-AFFD-6A9D7670B16B",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.ipad-pro-11-3rd-1",
                        "modelName" : "iPad Pro (11-inch) (3rd generation)",
                        "name" : "iPad Pro (11-inch) (3rd generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone14,6",
                        "identifier" : "DE894E91-DCB8-4BE0-93B5-34B787114A91",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-se3-1",
                        "modelName" : "iPhone SE (3rd generation)",
                        "name" : "iPhone SE (3rd generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone14,4",
                          "identifier" : "80C8B9CB-8814-4FF5-9CF6-94F6F7077A34",
                          "architecture" : "x86_64",
                          "modelUTI" : "com.apple.iphone-13-mini-1",
                          "modelName" : "iPhone 13 mini",
                          "name" : "iPhone 13 mini"
                        },
                        "modelCode" : "Watch6,6",
                        "identifier" : "51B4BC91-1DF6-4316-A25D-4D98A1080B92",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.watch-series7-1",
                        "modelName" : "Apple Watch Series 7 - 41mm",
                        "name" : "Apple Watch Series 7 - 41mm"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.4 (19L439)",
                        "available" : true,
                        "platform" : "com.apple.platform.appletvsimulator",
                        "modelCode" : "AppleTV11,1",
                        "identifier" : "ADC10806-83B1-4874-B27B-BD557B2589A5",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.apple-tv-4k-2nd",
                        "modelName" : "Apple TV 4K (2nd generation)",
                        "name" : "Apple TV 4K (2nd generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone14,3",
                        "identifier" : "048108E4-D2A3-48FF-A4F5-7FF86434839F",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-13-pro-max-1",
                        "modelName" : "iPhone 13 Pro Max",
                        "name" : "iPhone 13 Pro Max"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone13,3",
                        "identifier" : "A39824F9-D33A-458D-9331-1F3925B218B9",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-12-pro-1",
                        "modelName" : "iPhone 12 Pro",
                        "name" : "iPhone 12 Pro"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPod9,1",
                        "identifier" : "A985A663-9AFD-4DD1-BBE9-981AA630F00D",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.ipod-touch-7-2",
                        "modelName" : "iPod touch (7th generation)",
                        "name" : "iPod touch (7th generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.4 (19L439)",
                        "available" : true,
                        "platform" : "com.apple.platform.appletvsimulator",
                        "modelCode" : "AppleTV5,3",
                        "identifier" : "07E03BEA-CA86-41A9-B410-61ADDAEB8647",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.apple-tv-4",
                        "modelName" : "Apple TV",
                        "name" : "Apple TV"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad12,2",
                        "identifier" : "5C739224-2EDE-4CE6-ADB5-54B5F8B11BEF",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.ipad-9-wwan-1",
                        "modelName" : "iPad (9th generation)",
                        "name" : "iPad (9th generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone14,5",
                        "identifier" : "3631D8FA-C8D7-4BF5-9C0B-D1CA0FCB767F",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-13-1",
                        "modelName" : "iPhone 13",
                        "name" : "iPhone 13"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone10,4",
                        "identifier" : "18811BFB-C258-49EC-AB73-6E9FFF4D75EC",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-8-2",
                        "modelName" : "iPhone 8",
                        "name" : "iPhone 8"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone14,4",
                        "identifier" : "80C8B9CB-8814-4FF5-9CF6-94F6F7077A34",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-13-mini-1",
                        "modelName" : "iPhone 13 mini",
                        "name" : "iPhone 13 mini"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad6,4",
                        "identifier" : "22EB516F-8480-4217-9935-2F007AA9F42C",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.ipad-pro-9point7-a1674-b9b7ba",
                        "modelName" : "iPad Pro (9.7-inch)",
                        "name" : "iPad Pro (9.7-inch)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone14,2",
                        "identifier" : "E5026D1F-DC9E-426F-BA7B-3AA93451E4FC",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-13-pro-1",
                        "modelName" : "iPhone 13 Pro",
                        "name" : "iPhone 13 Pro"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad14,1",
                        "identifier" : "25F13879-BE70-4256-BE00-E5EDBD9B2D3E",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.ipad-mini6-1",
                        "modelName" : "iPad mini (6th generation)",
                        "name" : "iPad mini (6th generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone13,4",
                        "identifier" : "DB4021F0-3F6D-49E9-B911-2BD44BA3074F",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-12-pro-max-1",
                        "modelName" : "iPhone 12 Pro Max",
                        "name" : "iPhone 12 Pro Max"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone12,1",
                        "identifier" : "70396614-24D5-4104-A736-08D322BB3FDF",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-11-1",
                        "modelName" : "iPhone 11",
                        "name" : "iPhone 11"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone13,3",
                          "identifier" : "A39824F9-D33A-458D-9331-1F3925B218B9",
                          "architecture" : "x86_64",
                          "modelUTI" : "com.apple.iphone-12-pro-1",
                          "modelName" : "iPhone 12 Pro",
                          "name" : "iPhone 12 Pro"
                        },
                        "modelCode" : "Watch5,3",
                        "identifier" : "64A75137-3482-4AB5-A821-FBC0AAA57C45",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.watch-series5-1",
                        "modelName" : "Apple Watch Series 5 - 40mm",
                        "name" : "Apple Watch Series 5 - 40mm"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone14,5",
                          "identifier" : "3631D8FA-C8D7-4BF5-9C0B-D1CA0FCB767F",
                          "architecture" : "x86_64",
                          "modelUTI" : "com.apple.iphone-13-1",
                          "modelName" : "iPhone 13",
                          "name" : "iPhone 13"
                        },
                        "modelCode" : "Watch6,9",
                        "identifier" : "890EB1B4-A249-4890-86BF-1CDF11DC3F4C",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.watch-series7-1",
                        "modelName" : "Apple Watch Series 7 - 45mm",
                        "name" : "Apple Watch Series 7 - 45mm"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone14,3",
                          "identifier" : "048108E4-D2A3-48FF-A4F5-7FF86434839F",
                          "architecture" : "x86_64",
                          "modelUTI" : "com.apple.iphone-13-pro-max-1",
                          "modelName" : "iPhone 13 Pro Max",
                          "name" : "iPhone 13 Pro Max"
                        },
                        "modelCode" : "Watch6,2",
                        "identifier" : "F525CACE-0538-4101-9BFF-EE9BBB57439E",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.watch-series6-1",
                        "modelName" : "Apple Watch Series 6 - 44mm",
                        "name" : "Apple Watch Series 6 - 44mm"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.4 (19L439)",
                        "available" : true,
                        "platform" : "com.apple.platform.appletvsimulator",
                        "modelCode" : "AppleTV11,1",
                        "identifier" : "F160B929-761C-4736-B36B-F0172B2018A1",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.apple-tv-4k-2nd",
                        "modelName" : "Apple TV 4K (at 1080p) (2nd generation)",
                        "name" : "Apple TV 4K (at 1080p) (2nd generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad13,10",
                        "identifier" : "8C7E6ED4-9F9B-4675-BEF4-736C7544375C",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.ipad-pro-12point9-5th-1",
                        "modelName" : "iPad Pro (12.9-inch) (5th generation)",
                        "name" : "iPad Pro (12.9-inch) (5th generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone13,2",
                        "identifier" : "052F17AD-D52D-4885-97F8-6CDD27C6640E",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-12-1",
                        "modelName" : "iPhone 12",
                        "name" : "iPhone 12"
                      }
                    ]

                    2022-05-26 04:45:42.802 xcdevice[10284:75503] Requested but did not find extension point with identifier
                    Xcode.IDEKit.ExtensionSentinelHostApplications for extension Xcode.DebuggerFoundation.AppExtensionHosts.watchOS of plug-in
                    com.apple.dt.IDEWatchSupportCore
                    2022-05-26 04:45:42.802 xcdevice[10284:75503] Requested but did not find extension point with identifier
                    Xcode.IDEKit.ExtensionPointIdentifierToBundleIdentifier for extension
                    Xcode.DebuggerFoundation.AppExtensionToBundleIdentifierMap.watchOS of plug-in com.apple.dt.IDEWatchSupportCore
[  +32 ms] /Users/ken/Library/Android/sdk/platform-tools/adb -s LMQ610TA3526ef8 shell getprop
[ +139 ms] Artifact Instance of 'AndroidInternalBuildArtifacts' is not required, skipping update.
[  +30 ms] Artifact Instance of 'WindowsEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'WindowsUwpEngineArtifacts' is not required, skipping update.
[  +14 ms] Artifact Instance of 'LinuxEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'LinuxFuchsiaSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'MacOSFuchsiaSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterRunnerSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterRunnerDebugSymbols' is not required, skipping update.
[  +75 ms] Changing current working directory to: /Users/ken/StudioProjects/lessimp
[ +153 ms] Multiple devices found:
[   +2 ms] ro.hardware = cv5a
[        ] ro.build.characteristics = default
[   +9 ms] LM Q610 FGN (mobile) • LMQ610TA3526ef8           • android-arm • Android 9 (API 28)
[   +1 ms] iPhone (2) (mobile)  • 00008030-0004551014E8802E • ios         • iOS 15.4.1 19E258
[   +1 ms] [1]: LM Q610 FGN (LMQ610TA3526ef8)
[        ] [2]: iPhone (2) (00008030-0004551014E8802E)
[   +3 ms] Please choose one (To quit, press "q/Q")
[        ] : 
[  +83 ms] 
[        ] Please choose one (To quit, press "q/Q")
[        ] : 
[+4712 ms] q
[  +18 ms] "flutter run" took 23,898ms.
[  +62 ms] 
           #0      throwToolExit (package:flutter_tools/src/base/common.dart:10:3)
           #1      DeviceManager._chooseOneOfAvailableDevices (package:flutter_tools/src/device.dart:314:7)
           <asynchronous suspension>
           #2      DeviceManager.findTargetDevices (package:flutter_tools/src/device.dart:302:37)
           <asynchronous suspension>
           #3      FlutterCommand.findAllTargetDevices (package:flutter_tools/src/runner/flutter_command.dart:1378:28)
           <asynchronous suspension>
           #4      RunCommand.validateCommand (package:flutter_tools/src/commands/run.dart:482:15)
           <asynchronous suspension>
           #5      FlutterCommand.verifyThenRunCommand (package:flutter_tools/src/runner/flutter_command.dart:1298:5)
           <asynchronous suspension>
           #6      FlutterCommand.run.<anonymous closure> (package:flutter_tools/src/runner/flutter_command.dart:1183:27)
           <asynchronous suspension>
           #7      AppContext.run.<anonymous closure> (package:flutter_tools/src/base/context.dart:150:19)
           <asynchronous suspension>
           #8      CommandRunner.runCommand (package:args/command_runner.dart:209:13)
           <asynchronous suspension>
           #9      FlutterCommandRunner.runCommand.<anonymous closure> (package:flutter_tools/src/runner/flutter_command_runner.dart:281:9)
           <asynchronous suspension>
           #10     AppContext.run.<anonymous closure> (package:flutter_tools/src/base/context.dart:150:19)
           <asynchronous suspension>
           #11     FlutterCommandRunner.runCommand (package:flutter_tools/src/runner/flutter_command_runner.dart:229:5)
           <asynchronous suspension>
           #12     run.<anonymous closure>.<anonymous closure> (package:flutter_tools/runner.dart:62:9)
           <asynchronous suspension>
           #13     AppContext.run.<anonymous closure> (package:flutter_tools/src/base/context.dart:150:19)
           <asynchronous suspension>
           #14     main (package:flutter_tools/executable.dart:94:3)
           <asynchronous suspension>
       
[ +174 ms] ensureAnalyticsSent: 170ms
[   +1 ms] Running shutdown hooks
[        ] Shutdown hooks complete
[        ] exiting with code 1
ken@Kens-MBP ios % clr
zsh: command not found: clr
ken@Kens-MBP ios % clear

ken@Kens-MBP ios % flutter run --verbose
[ +147 ms] executing: sysctl hw.optional.arm64
[  +24 ms] Exit code 1 from: sysctl hw.optional.arm64
[   +1 ms] sysctl: unknown oid 'hw.optional.arm64'
[   +9 ms] executing: [/Users/Ken/Development/flutter/] git -c log.showSignature=false log -n 1 --pretty=format:%H
[  +13 ms] Exit code 0 from: git -c log.showSignature=false log -n 1 --pretty=format:%H
[        ] fb57da5f945d02ef4f98dfd9409a72b7cce74268
[        ] executing: [/Users/Ken/Development/flutter/] git tag --points-at fb57da5f945d02ef4f98dfd9409a72b7cce74268
[  +28 ms] Exit code 0 from: git tag --points-at fb57da5f945d02ef4f98dfd9409a72b7cce74268
[        ] 3.0.1
[  +12 ms] executing: [/Users/Ken/Development/flutter/] git rev-parse --abbrev-ref --symbolic @{u}
[  +11 ms] Exit code 0 from: git rev-parse --abbrev-ref --symbolic @{u}
[        ] origin/stable
[        ] executing: [/Users/Ken/Development/flutter/] git ls-remote --get-url origin
[  +13 ms] Exit code 0 from: git ls-remote --get-url origin
[        ] git@github.com:flutter/flutter.git
[ +150 ms] executing: [/Users/Ken/Development/flutter/] git rev-parse --abbrev-ref HEAD
[  +19 ms] Exit code 0 from: git rev-parse --abbrev-ref HEAD
[   +1 ms] stable
[   +8 ms] executing: sw_vers -productName
[  +32 ms] Exit code 0 from: sw_vers -productName
[   +1 ms] macOS
[        ] executing: sw_vers -productVersion
[  +30 ms] Exit code 0 from: sw_vers -productVersion
[        ] 12.4
[        ] executing: sw_vers -buildVersion
[  +30 ms] Exit code 0 from: sw_vers -buildVersion
[   +1 ms] 21F79
[        ] executing: uname -m
[   +8 ms] Exit code 0 from: uname -m
[   +1 ms] x86_64
[ +120 ms] Artifact Instance of 'AndroidGenSnapshotArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'AndroidInternalBuildArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'IOSEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterWebSdk' is not required, skipping update.
[   +7 ms] Artifact Instance of 'WindowsEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'WindowsUwpEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'MacOSEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'LinuxEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'LinuxFuchsiaSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'MacOSFuchsiaSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterRunnerSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterRunnerDebugSymbols' is not required, skipping update.
[ +118 ms] executing: /Users/ken/Library/Android/sdk/platform-tools/adb devices -l
[  +22 ms] executing: sysctl hw.optional.arm64
[   +8 ms] Exit code 1 from: sysctl hw.optional.arm64
[        ] sysctl: unknown oid 'hw.optional.arm64'
[        ] executing: xcrun xcodebuild -version
[ +285 ms] Exit code 0 from: xcrun xcodebuild -version
[        ] Xcode 13.4
           Build version 13F17a
[   +3 ms] executing: xcrun xcdevice list --timeout 2
[   +4 ms] xcrun simctl list --json devices
[        ] executing: xcrun simctl list --json devices
[   +6 ms] executing: xcrun simctl list
[ +187 ms] Exit code 0 from: xcrun simctl list
[   +1 ms] == Device Types ==
           iPhone 4s (com.apple.CoreSimulator.SimDeviceType.iPhone-4s)
           iPhone 5 (com.apple.CoreSimulator.SimDeviceType.iPhone-5)
           iPhone 5s (com.apple.CoreSimulator.SimDeviceType.iPhone-5s)
           iPhone 6 Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-6-Plus)
           iPhone 6 (com.apple.CoreSimulator.SimDeviceType.iPhone-6)
           iPhone 6s (com.apple.CoreSimulator.SimDeviceType.iPhone-6s)
           iPhone 6s Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-6s-Plus)
           iPhone SE (1st generation) (com.apple.CoreSimulator.SimDeviceType.iPhone-SE)
           iPhone 7 (com.apple.CoreSimulator.SimDeviceType.iPhone-7)
           iPhone 7 Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-7-Plus)
           iPhone 8 (com.apple.CoreSimulator.SimDeviceType.iPhone-8)
           iPhone 8 Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-8-Plus)
           iPhone X (com.apple.CoreSimulator.SimDeviceType.iPhone-X)
           iPhone Xs (com.apple.CoreSimulator.SimDeviceType.iPhone-XS)
           iPhone Xs Max (com.apple.CoreSimulator.SimDeviceType.iPhone-XS-Max)
           iPhone Xʀ (com.apple.CoreSimulator.SimDeviceType.iPhone-XR)
           iPhone 11 (com.apple.CoreSimulator.SimDeviceType.iPhone-11)
           iPhone 11 Pro (com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro)
           iPhone 11 Pro Max (com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro-Max)
           iPhone SE (2nd generation) (com.apple.CoreSimulator.SimDeviceType.iPhone-SE--2nd-generation-)
           iPhone 12 mini (com.apple.CoreSimulator.SimDeviceType.iPhone-12-mini)
           iPhone 12 (com.apple.CoreSimulator.SimDeviceType.iPhone-12)
           iPhone 12 Pro (com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro)
           iPhone 12 Pro Max (com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro-Max)
           iPhone 13 Pro (com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro)
           iPhone 13 Pro Max (com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro-Max)
           iPhone 13 mini (com.apple.CoreSimulator.SimDeviceType.iPhone-13-mini)
           iPhone 13 (com.apple.CoreSimulator.SimDeviceType.iPhone-13)
           iPhone SE (3rd generation) (com.apple.CoreSimulator.SimDeviceType.iPhone-SE-3rd-generation)
           iPod touch (7th generation) (com.apple.CoreSimulator.SimDeviceType.iPod-touch--7th-generation-)
           iPad 2 (com.apple.CoreSimulator.SimDeviceType.iPad-2)
           iPad Retina (com.apple.CoreSimulator.SimDeviceType.iPad-Retina)
           iPad Air (com.apple.CoreSimulator.SimDeviceType.iPad-Air)
           iPad mini 2 (com.apple.CoreSimulator.SimDeviceType.iPad-mini-2)
           iPad mini 3 (com.apple.CoreSimulator.SimDeviceType.iPad-mini-3)
           iPad mini 4 (com.apple.CoreSimulator.SimDeviceType.iPad-mini-4)
           iPad Air 2 (com.apple.CoreSimulator.SimDeviceType.iPad-Air-2)
           iPad Pro (9.7-inch) (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--9-7-inch-)
           iPad Pro (12.9-inch) (1st generation) (com.apple.CoreSimulator.SimDeviceType.iPad-Pro)
           iPad (5th generation) (com.apple.CoreSimulator.SimDeviceType.iPad--5th-generation-)
           iPad Pro (12.9-inch) (2nd generation) (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--12-9-inch---2nd-generation-)
           iPad Pro (10.5-inch) (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--10-5-inch-)
           iPad (6th generation) (com.apple.CoreSimulator.SimDeviceType.iPad--6th-generation-)
           iPad (7th generation) (com.apple.CoreSimulator.SimDeviceType.iPad--7th-generation-)
           iPad Pro (11-inch) (1st generation) (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--11-inch-)
           iPad Pro (12.9-inch) (3rd generation) (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--12-9-inch---3rd-generation-)
           iPad Pro (11-inch) (2nd generation) (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--11-inch---2nd-generation-)
           iPad Pro (12.9-inch) (4th generation) (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--12-9-inch---4th-generation-)
           iPad mini (5th generation) (com.apple.CoreSimulator.SimDeviceType.iPad-mini--5th-generation-)
           iPad Air (3rd generation) (com.apple.CoreSimulator.SimDeviceType.iPad-Air--3rd-generation-)
           iPad (8th generation) (com.apple.CoreSimulator.SimDeviceType.iPad--8th-generation-)
           iPad (9th generation) (com.apple.CoreSimulator.SimDeviceType.iPad-9th-generation)
           iPad Air (4th generation) (com.apple.CoreSimulator.SimDeviceType.iPad-Air--4th-generation-)
           iPad Pro (11-inch) (3rd generation) (com.apple.CoreSimulator.SimDeviceType.iPad-Pro-11-inch-3rd-generation)
           iPad Pro (12.9-inch) (5th generation) (com.apple.CoreSimulator.SimDeviceType.iPad-Pro-12-9-inch-5th-generation)
           iPad Air (5th generation) (com.apple.CoreSimulator.SimDeviceType.iPad-Air-5th-generation)
           iPad mini (6th generation) (com.apple.CoreSimulator.SimDeviceType.iPad-mini-6th-generation)
           Apple TV (com.apple.CoreSimulator.SimDeviceType.Apple-TV-1080p)
           Apple TV 4K (com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-4K)
           Apple TV 4K (at 1080p) (com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-1080p)
           Apple TV 4K (2nd generation) (com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2nd-generation-4K)
           Apple TV 4K (at 1080p) (2nd generation) (com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2nd-generation-1080p)
           Apple Watch - 38mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-38mm)
           Apple Watch - 42mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-42mm)
           Apple Watch Series 2 - 38mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-2-38mm)
           Apple Watch Series 2 - 42mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-2-42mm)
           Apple Watch Series 3 - 38mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-3-38mm)
           Apple Watch Series 3 - 42mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-3-42mm)
           Apple Watch Series 4 - 40mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-4-40mm)
           Apple Watch Series 4 - 44mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-4-44mm)
           Apple Watch Series 5 - 40mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-5-40mm)
           Apple Watch Series 5 - 44mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-5-44mm)
           Apple Watch SE - 40mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-SE-40mm)
           Apple Watch SE - 44mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-SE-44mm)
           Apple Watch Series 6 - 40mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-6-40mm)
           Apple Watch Series 6 - 44mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-6-44mm)
           Apple Watch Series 7 - 41mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-7-41mm)
           Apple Watch Series 7 - 45mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-7-45mm)
           == Runtimes ==
           iOS 15.5 (15.5 - 19F70) - com.apple.CoreSimulator.SimRuntime.iOS-15-5
           tvOS 15.4 (15.4 - 19L439) - com.apple.CoreSimulator.SimRuntime.tvOS-15-4
           watchOS 8.5 (8.5 - 19T241) - com.apple.CoreSimulator.SimRuntime.watchOS-8-5
           == Devices ==
           -- iOS 15.5 --
               iPhone 8 (18811BFB-C258-49EC-AB73-6E9FFF4D75EC) (Shutdown) 
               iPhone 8 Plus (0173A5F1-4288-4C05-AF7F-04964DFB789E) (Shutdown) 
               iPhone 11 (70396614-24D5-4104-A736-08D322BB3FDF) (Shutdown) 
               iPhone 11 Pro (5F56FFED-31C2-4AAF-B960-D4499BEA12DC) (Shutdown) 
               iPhone 11 Pro Max (D865C90F-2860-4E0D-A900-5D744A64D116) (Shutdown) 
               iPhone 12 mini (3B059333-96F6-433E-87AB-1F1129B17204) (Shutdown) 
               iPhone 12 (052F17AD-D52D-4885-97F8-6CDD27C6640E) (Shutdown) 
               iPhone 12 Pro (A39824F9-D33A-458D-9331-1F3925B218B9) (Shutdown) 
               iPhone 12 Pro Max (DB4021F0-3F6D-49E9-B911-2BD44BA3074F) (Shutdown) 
               iPhone 13 Pro (E5026D1F-DC9E-426F-BA7B-3AA93451E4FC) (Shutdown) 
               iPhone 13 Pro Max (048108E4-D2A3-48FF-A4F5-7FF86434839F) (Shutdown) 
               iPhone 13 mini (80C8B9CB-8814-4FF5-9CF6-94F6F7077A34) (Shutdown) 
               iPhone 13 (3631D8FA-C8D7-4BF5-9C0B-D1CA0FCB767F) (Shutdown) 
               iPhone SE (3rd generation) (DE894E91-DCB8-4BE0-93B5-34B787114A91) (Shutdown) 
               iPod touch (7th generation) (A985A663-9AFD-4DD1-BBE9-981AA630F00D) (Shutdown) 
               iPad Pro (9.7-inch) (22EB516F-8480-4217-9935-2F007AA9F42C) (Shutdown) 
               iPad (9th generation) (5C739224-2EDE-4CE6-ADB5-54B5F8B11BEF) (Shutdown) 
               iPad Pro (11-inch) (3rd generation) (2D84767E-BC58-4AFD-AFFD-6A9D7670B16B) (Shutdown) 
               iPad Pro (12.9-inch) (5th generation) (8C7E6ED4-9F9B-4675-BEF4-736C7544375C) (Shutdown) 
               iPad Air (5th generation) (FA9FA89C-AC7B-41B4-8CBF-1583B52F1662) (Shutdown) 
               iPad mini (6th generation) (25F13879-BE70-4256-BE00-E5EDBD9B2D3E) (Shutdown) 
           -- tvOS 15.4 --
               Apple TV (07E03BEA-CA86-41A9-B410-61ADDAEB8647) (Shutdown) 
               Apple TV 4K (2nd generation) (ADC10806-83B1-4874-B27B-BD557B2589A5) (Shutdown) 
               Apple TV 4K (at 1080p) (2nd generation) (F160B929-761C-4736-B36B-F0172B2018A1) (Shutdown) 
           -- watchOS 8.5 --
               Apple Watch Series 5 - 40mm (64A75137-3482-4AB5-A821-FBC0AAA57C45) (Shutdown) 
               Apple Watch Series 5 - 44mm (24C02FB0-7E3B-4CC0-9BCB-7683D67F611A) (Shutdown) 
               Apple Watch Series 6 - 40mm (F86B0909-88A3-4088-ACD0-084A9C753974) (Shutdown) 
               Apple Watch Series 6 - 44mm (F525CACE-0538-4101-9BFF-EE9BBB57439E) (Shutdown) 
               Apple Watch Series 7 - 41mm (51B4BC91-1DF6-4316-A25D-4D98A1080B92) (Shutdown) 
               Apple Watch Series 7 - 45mm (890EB1B4-A249-4890-86BF-1CDF11DC3F4C) (Shutdown) 
           -- Unavailable: com.apple.CoreSimulator.SimRuntime.iOS-15-2 --
               iPhone 8 (3C9AE000-CCEF-4DE7-8BE4-0AC053511EE1) (Shutdown) (unavailable, runtime profile not found)
               iPhone 8 Plus (4E90F5C3-4D0A-4802-A3A9-AFA660ED4702) (Shutdown) (unavailable, runtime profile not found)
               iPhone 11 (4D8CD72D-6935-4594-AB91-5DFBCB69A388) (Shutdown) (unavailable, runtime profile not found)
               iPhone 11 Pro (69847AAD-F3DC-4D4C-8E1A-2BBD620D5DD6) (Shutdown) (unavailable, runtime profile not found)
               iPhone 11 Pro Max (5A954F8E-B939-4BCD-9F7F-C970E8602AE8) (Shutdown) (unavailable, runtime profile not found)
               iPhone SE (2nd generation) (1E7FEB58-2102-4792-ADE0-2275CCA8E9B1) (Shutdown) (unavailable, runtime profile not found)
               iPhone 12 mini (D50577CF-EB32-40B2-A7A8-CF646059781C) (Shutdown) (unavailable, runtime profile not found)
               iPhone 12 (7E9E0CC7-1A72-4148-876C-F13A01227304) (Shutdown) (unavailable, runtime profile not found)
               iPhone 12 Pro (DA3845B9-4BCA-4414-9B1D-436AD61F8819) (Shutdown) (unavailable, runtime profile not found)
               iPhone 12 Pro Max (49BFF121-F815-4573-A517-0905B53FF113) (Shutdown) (unavailable, runtime profile not found)
               iPhone 13 Pro (B15947C1-7D56-4DC6-B591-4A0CFAE8814F) (Shutdown) (unavailable, runtime profile not found)
               iPhone 13 Pro Max (801D6BE8-2F18-4337-A817-19A87902A579) (Shutdown) (unavailable, runtime profile not found)
               iPhone 13 mini (77F365B1-0E60-412F-80DF-DC0568BDB52A) (Shutdown) (unavailable, runtime profile not found)
               iPhone 13 (368C2A57-CC77-4BFA-81D9-62DD16F9354B) (Shutdown) (unavailable, runtime profile not found)
               iPod touch (7th generation) (C7C2B69A-59AE-4530-86A1-475A1116C71E) (Shutdown) (unavailable, runtime profile not found)
               iPad Pro (9.7-inch) (1E71062D-928A-4058-A90A-36608C4553AD) (Shutdown) (unavailable, runtime profile not found)
               iPad (9th generation) (94012AA4-0140-4EFE-ACE8-63BBAB147A0D) (Shutdown) (unavailable, runtime profile not found)
               iPad Air (4th generation) (5FA2692B-6D94-46FF-9FF9-8DD8BF1F0EF0) (Shutdown) (unavailable, runtime profile not found)
               iPad Pro (11-inch) (3rd generation) (CA638B36-C00D-45F5-B88C-DCBF8564FC55) (Shutdown) (unavailable, runtime profile not found)
               iPad Pro (12.9-inch) (5th generation) (29E60055-6766-4F29-9529-4B39FECDA921) (Shutdown) (unavailable, runtime profile not found)
               iPad mini (6th generation) (D47447BF-D325-49F0-8120-BFABB3158FD2) (Shutdown) (unavailable, runtime profile not found)
           -- Unavailable: com.apple.CoreSimulator.SimRuntime.tvOS-15-2 --
               Apple TV (F0D148A6-95E5-4C2B-AAD9-20B343F581F7) (Shutdown) (unavailable, runtime profile not found)
               Apple TV 4K (2nd generation) (9F4EC24E-D238-4FB8-A949-BE0B64852223) (Shutdown) (unavailable, runtime profile not found)
               Apple TV 4K (at 1080p) (2nd generation) (8E300EEC-2A09-4D34-941D-35E3043F28AC) (Shutdown) (unavailable, runtime profile not found)
           -- Unavailable: com.apple.CoreSimulator.SimRuntime.watchOS-8-3 --
               Apple Watch Series 5 - 40mm (9535A885-DB9F-4928-8225-4E43C09A72C3) (Shutdown) (unavailable, runtime profile not found)
               Apple Watch Series 5 - 44mm (96916268-CA7A-4B02-A34B-F735689703F8) (Shutdown) (unavailable, runtime profile not found)
               Apple Watch Series 6 - 40mm (64A76DC4-C517-4C5A-A3FD-A9DA39B05BA6) (Shutdown) (unavailable, runtime profile not found)
               Apple Watch Series 6 - 44mm (257BA6A9-9B49-4377-93D4-81DE64354F93) (Shutdown) (unavailable, runtime profile not found)
               Apple Watch Series 7 - 41mm (591F5F99-3035-4FDD-BE1F-F5C22BF8C6CB) (Shutdown) (unavailable, runtime profile not found)
               Apple Watch Series 7 - 45mm (7D056D33-57EA-47CB-9DC0-51867464EAF6) (Shutdown) (unavailable, runtime profile not found)
           == Device Pairs ==
           E3493809-5950-4040-8D3F-B4E3510FE138 (active, disconnected)
               Watch: Apple Watch Series 5 - 40mm (64A75137-3482-4AB5-A821-FBC0AAA57C45) (Shutdown)
               Phone: iPhone 12 Pro (A39824F9-D33A-458D-9331-1F3925B218B9) (Shutdown)
           62CC4BEE-A555-4CF1-9455-310BD9CDCFF5 (active, disconnected)
               Watch: Apple Watch Series 5 - 44mm (24C02FB0-7E3B-4CC0-9BCB-7683D67F611A) (Shutdown)
               Phone: iPhone 12 Pro Max (DB4021F0-3F6D-49E9-B911-2BD44BA3074F) (Shutdown)
           1FB9F4D6-A284-4F1C-9CEA-EF32B6AB8FDB (active, disconnected)
               Watch: Apple Watch Series 6 - 40mm (F86B0909-88A3-4088-ACD0-084A9C753974) (Shutdown)
               Phone: iPhone 13 Pro (E5026D1F-DC9E-426F-BA7B-3AA93451E4FC) (Shutdown)
           24FDEFA3-9801-4C0C-8CE2-2523B5872B99 (active, disconnected)
               Watch: Apple Watch Series 6 - 44mm (F525CACE-0538-4101-9BFF-EE9BBB57439E) (Shutdown)
               Phone: iPhone 13 Pro Max (048108E4-D2A3-48FF-A4F5-7FF86434839F) (Shutdown)
           6294322F-6302-41E4-AC52-78F33B9D0FE1 (active, disconnected)
               Watch: Apple Watch Series 7 - 41mm (51B4BC91-1DF6-4316-A25D-4D98A1080B92) (Shutdown)
               Phone: iPhone 13 mini (80C8B9CB-8814-4FF5-9CF6-94F6F7077A34) (Shutdown)
           4A1E91E1-185E-4FC1-BFDB-91B847FB36C0 (active, disconnected)
               Watch: Apple Watch Series 7 - 45mm (890EB1B4-A249-4890-86BF-1CDF11DC3F4C) (Shutdown)
               Phone: iPhone 13 (3631D8FA-C8D7-4BF5-9C0B-D1CA0FCB767F) (Shutdown)
           0E153606-A902-4BFF-862C-AEB6C47DC7C3 (unavailable)
               Watch: Apple Watch Series 5 - 40mm (9535A885-DB9F-4928-8225-4E43C09A72C3) (Shutdown)
               Phone: iPhone 12 Pro (DA3845B9-4BCA-4414-9B1D-436AD61F8819) (Shutdown)
           42B96B43-360C-4D26-86C6-ED51809564F4 (unavailable)
               Watch: Apple Watch Series 5 - 44mm (96916268-CA7A-4B02-A34B-F735689703F8) (Shutdown)
               Phone: iPhone 12 Pro Max (49BFF121-F815-4573-A517-0905B53FF113) (Shutdown)
           9A11A9EE-D68D-4F4C-AB6E-D183ED49806D (unavailable)
               Watch: Apple Watch Series 6 - 40mm (64A76DC4-C517-4C5A-A3FD-A9DA39B05BA6) (Shutdown)
               Phone: iPhone 13 Pro (B15947C1-7D56-4DC6-B591-4A0CFAE8814F) (Shutdown)
           C85D6AF7-412F-40B6-945E-7271FDE9C24F (unavailable)
               Watch: Apple Watch Series 6 - 44mm (257BA6A9-9B49-4377-93D4-81DE64354F93) (Shutdown)
               Phone: iPhone 13 Pro Max (801D6BE8-2F18-4337-A817-19A87902A579) (Shutdown)
           39AA247E-895E-4498-A55A-47A716EEB547 (unavailable)
               Watch: Apple Watch Series 7 - 41mm (591F5F99-3035-4FDD-BE1F-F5C22BF8C6CB) (Shutdown)
               Phone: iPhone 13 mini (77F365B1-0E60-412F-80DF-DC0568BDB52A) (Shutdown)
           2E005628-9805-412D-B163-092D0A79A0DF (unavailable)
               Watch: Apple Watch Series 7 - 45mm (7D056D33-57EA-47CB-9DC0-51867464EAF6) (Shutdown)
               Phone: iPhone 13 (368C2A57-CC77-4BFA-81D9-62DD16F9354B) (Shutdown)
[  +97 ms] List of devices attached
           LMQ610TA3526ef8        device usb:337641472X product:cv5a_lao_com model:LM_Q610_FGN_ device:cv5a transport_id:3
[ +173 ms] {
                      "devices" : {
                        "com.apple.CoreSimulator.SimRuntime.watchOS-8-5" : [
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/64A75137-3482-4AB5-A821-FBC0AAA57C45\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/64A75137-3482-4AB5-A821-FBC0AAA57C45",
                            "udid" : "64A75137-3482-4AB5-A821-FBC0AAA57C45",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-5-40mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 5 - 40mm"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/24C02FB0-7E3B-4CC0-9BCB-7683D67F611A\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/24C02FB0-7E3B-4CC0-9BCB-7683D67F611A",
                            "udid" : "24C02FB0-7E3B-4CC0-9BCB-7683D67F611A",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-5-44mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 5 - 44mm"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/F86B0909-88A3-4088-ACD0-084A9C753974\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/F86B0909-88A3-4088-ACD0-084A9C753974",
                            "udid" : "F86B0909-88A3-4088-ACD0-084A9C753974",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-6-40mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 6 - 40mm"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/F525CACE-0538-4101-9BFF-EE9BBB57439E\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/F525CACE-0538-4101-9BFF-EE9BBB57439E",
                            "udid" : "F525CACE-0538-4101-9BFF-EE9BBB57439E",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-6-44mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 6 - 44mm"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/51B4BC91-1DF6-4316-A25D-4D98A1080B92\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/51B4BC91-1DF6-4316-A25D-4D98A1080B92",
                            "udid" : "51B4BC91-1DF6-4316-A25D-4D98A1080B92",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-7-41mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 7 - 41mm"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/890EB1B4-A249-4890-86BF-1CDF11DC3F4C\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/890EB1B4-A249-4890-86BF-1CDF11DC3F4C",
                            "udid" : "890EB1B4-A249-4890-86BF-1CDF11DC3F4C",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-7-45mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 7 - 45mm"
                          }
                        ],
                        "com.apple.CoreSimulator.SimRuntime.tvOS-15-4" : [
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/07E03BEA-CA86-41A9-B410-61ADDAEB8647\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/07E03BEA-CA86-41A9-B410-61ADDAEB8647",
                            "udid" : "07E03BEA-CA86-41A9-B410-61ADDAEB8647",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-TV-1080p",
                            "state" : "Shutdown",
                            "name" : "Apple TV"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/ADC10806-83B1-4874-B27B-BD557B2589A5\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/ADC10806-83B1-4874-B27B-BD557B2589A5",
                            "udid" : "ADC10806-83B1-4874-B27B-BD557B2589A5",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2nd-generation-4K",
                            "state" : "Shutdown",
                            "name" : "Apple TV 4K (2nd generation)"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/F160B929-761C-4736-B36B-F0172B2018A1\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/F160B929-761C-4736-B36B-F0172B2018A1",
                            "udid" : "F160B929-761C-4736-B36B-F0172B2018A1",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2nd-generation-1080p",
                            "state" : "Shutdown",
                            "name" : "Apple TV 4K (at 1080p) (2nd generation)"
                          }
                        ],
                        "com.apple.CoreSimulator.SimRuntime.iOS-15-2" : [
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/3C9AE000-CCEF-4DE7-8BE4-0AC053511EE1\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/3C9AE000-CCEF-4DE7-8BE4-0AC053511EE1",
                            "udid" : "3C9AE000-CCEF-4DE7-8BE4-0AC053511EE1",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-8",
                            "state" : "Shutdown",
                            "name" : "iPhone 8"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/4E90F5C3-4D0A-4802-A3A9-AFA660ED4702\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/4E90F5C3-4D0A-4802-A3A9-AFA660ED4702",
                            "udid" : "4E90F5C3-4D0A-4802-A3A9-AFA660ED4702",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-8-Plus",
                            "state" : "Shutdown",
                            "name" : "iPhone 8 Plus"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/4D8CD72D-6935-4594-AB91-5DFBCB69A388\/data",
                            "dataPathSize" : 1036697600,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/4D8CD72D-6935-4594-AB91-5DFBCB69A388",
                            "udid" : "4D8CD72D-6935-4594-AB91-5DFBCB69A388",
                            "isAvailable" : false,
                            "logPathSize" : 352256,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-11",
                            "state" : "Shutdown",
                            "name" : "iPhone 11"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/69847AAD-F3DC-4D4C-8E1A-2BBD620D5DD6\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/69847AAD-F3DC-4D4C-8E1A-2BBD620D5DD6",
                            "udid" : "69847AAD-F3DC-4D4C-8E1A-2BBD620D5DD6",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro",
                            "state" : "Shutdown",
                            "name" : "iPhone 11 Pro"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/5A954F8E-B939-4BCD-9F7F-C970E8602AE8\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/5A954F8E-B939-4BCD-9F7F-C970E8602AE8",
                            "udid" : "5A954F8E-B939-4BCD-9F7F-C970E8602AE8",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro-Max",
                            "state" : "Shutdown",
                            "name" : "iPhone 11 Pro Max"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/1E7FEB58-2102-4792-ADE0-2275CCA8E9B1\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/1E7FEB58-2102-4792-ADE0-2275CCA8E9B1",
                            "udid" : "1E7FEB58-2102-4792-ADE0-2275CCA8E9B1",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-SE--2nd-generation-",
                            "state" : "Shutdown",
                            "name" : "iPhone SE (2nd generation)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/D50577CF-EB32-40B2-A7A8-CF646059781C\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/D50577CF-EB32-40B2-A7A8-CF646059781C",
                            "udid" : "D50577CF-EB32-40B2-A7A8-CF646059781C",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-12-mini",
                            "state" : "Shutdown",
                            "name" : "iPhone 12 mini"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/7E9E0CC7-1A72-4148-876C-F13A01227304\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/7E9E0CC7-1A72-4148-876C-F13A01227304",
                            "udid" : "7E9E0CC7-1A72-4148-876C-F13A01227304",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-12",
                            "state" : "Shutdown",
                            "name" : "iPhone 12"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/DA3845B9-4BCA-4414-9B1D-436AD61F8819\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/DA3845B9-4BCA-4414-9B1D-436AD61F8819",
                            "udid" : "DA3845B9-4BCA-4414-9B1D-436AD61F8819",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro",
                            "state" : "Shutdown",
                            "name" : "iPhone 12 Pro"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/49BFF121-F815-4573-A517-0905B53FF113\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/49BFF121-F815-4573-A517-0905B53FF113",
                            "udid" : "49BFF121-F815-4573-A517-0905B53FF113",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro-Max",
                            "state" : "Shutdown",
                            "name" : "iPhone 12 Pro Max"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/B15947C1-7D56-4DC6-B591-4A0CFAE8814F\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/B15947C1-7D56-4DC6-B591-4A0CFAE8814F",
                            "udid" : "B15947C1-7D56-4DC6-B591-4A0CFAE8814F",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro",
                            "state" : "Shutdown",
                            "name" : "iPhone 13 Pro"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/801D6BE8-2F18-4337-A817-19A87902A579\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/801D6BE8-2F18-4337-A817-19A87902A579",
                            "udid" : "801D6BE8-2F18-4337-A817-19A87902A579",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro-Max",
                            "state" : "Shutdown",
                            "name" : "iPhone 13 Pro Max"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/77F365B1-0E60-412F-80DF-DC0568BDB52A\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/77F365B1-0E60-412F-80DF-DC0568BDB52A",
                            "udid" : "77F365B1-0E60-412F-80DF-DC0568BDB52A",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-13-mini",
                            "state" : "Shutdown",
                            "name" : "iPhone 13 mini"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/368C2A57-CC77-4BFA-81D9-62DD16F9354B\/data",
                            "dataPathSize" : 1363148800,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/368C2A57-CC77-4BFA-81D9-62DD16F9354B",
                            "udid" : "368C2A57-CC77-4BFA-81D9-62DD16F9354B",
                            "isAvailable" : false,
                            "logPathSize" : 434176,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-13",
                            "state" : "Shutdown",
                            "name" : "iPhone 13"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/C7C2B69A-59AE-4530-86A1-475A1116C71E\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/C7C2B69A-59AE-4530-86A1-475A1116C71E",
                            "udid" : "C7C2B69A-59AE-4530-86A1-475A1116C71E",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPod-touch--7th-generation-",
                            "state" : "Shutdown",
                            "name" : "iPod touch (7th generation)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/1E71062D-928A-4058-A90A-36608C4553AD\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/1E71062D-928A-4058-A90A-36608C4553AD",
                            "udid" : "1E71062D-928A-4058-A90A-36608C4553AD",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPad-Pro--9-7-inch-",
                            "state" : "Shutdown",
                            "name" : "iPad Pro (9.7-inch)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/94012AA4-0140-4EFE-ACE8-63BBAB147A0D\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/94012AA4-0140-4EFE-ACE8-63BBAB147A0D",
                            "udid" : "94012AA4-0140-4EFE-ACE8-63BBAB147A0D",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPad-9th-generation",
                            "state" : "Shutdown",
                            "name" : "iPad (9th generation)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/5FA2692B-6D94-46FF-9FF9-8DD8BF1F0EF0\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/5FA2692B-6D94-46FF-9FF9-8DD8BF1F0EF0",
                            "udid" : "5FA2692B-6D94-46FF-9FF9-8DD8BF1F0EF0",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPad-Air--4th-generation-",
                            "state" : "Shutdown",
                            "name" : "iPad Air (4th generation)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/CA638B36-C00D-45F5-B88C-DCBF8564FC55\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/CA638B36-C00D-45F5-B88C-DCBF8564FC55",
                            "udid" : "CA638B36-C00D-45F5-B88C-DCBF8564FC55",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPad-Pro-11-inch-3rd-generation",
                            "state" : "Shutdown",
                            "name" : "iPad Pro (11-inch) (3rd generation)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/29E60055-6766-4F29-9529-4B39FECDA921\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/29E60055-6766-4F29-9529-4B39FECDA921",
                            "udid" : "29E60055-6766-4F29-9529-4B39FECDA921",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPad-Pro-12-9-inch-5th-generation",
                            "state" : "Shutdown",
                            "name" : "iPad Pro (12.9-inch) (5th generation)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/D47447BF-D325-49F0-8120-BFABB3158FD2\/data",
                            "dataPathSize" : 13312000,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/D47447BF-D325-49F0-8120-BFABB3158FD2",
                            "udid" : "D47447BF-D325-49F0-8120-BFABB3158FD2",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPad-mini-6th-generation",
                            "state" : "Shutdown",
                            "name" : "iPad mini (6th generation)"
                          }
                        ],
                        "com.apple.CoreSimulator.SimRuntime.iOS-15-5" : [
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/18811BFB-C258-49EC-AB73-6E9FFF4D75EC\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/18811BFB-C258-49EC-AB73-6E9FFF4D75EC",
                            "udid" : "18811BFB-C258-49EC-AB73-6E9FFF4D75EC",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-8",
                            "state" : "Shutdown",
                            "name" : "iPhone 8"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/0173A5F1-4288-4C05-AF7F-04964DFB789E\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/0173A5F1-4288-4C05-AF7F-04964DFB789E",
                            "udid" : "0173A5F1-4288-4C05-AF7F-04964DFB789E",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-8-Plus",
                            "state" : "Shutdown",
                            "name" : "iPhone 8 Plus"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/70396614-24D5-4104-A736-08D322BB3FDF\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/70396614-24D5-4104-A736-08D322BB3FDF",
                            "udid" : "70396614-24D5-4104-A736-08D322BB3FDF",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-11",
                            "state" : "Shutdown",
                            "name" : "iPhone 11"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/5F56FFED-31C2-4AAF-B960-D4499BEA12DC\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/5F56FFED-31C2-4AAF-B960-D4499BEA12DC",
                            "udid" : "5F56FFED-31C2-4AAF-B960-D4499BEA12DC",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro",
                            "state" : "Shutdown",
                            "name" : "iPhone 11 Pro"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/D865C90F-2860-4E0D-A900-5D744A64D116\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/D865C90F-2860-4E0D-A900-5D744A64D116",
                            "udid" : "D865C90F-2860-4E0D-A900-5D744A64D116",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro-Max",
                            "state" : "Shutdown",
                            "name" : "iPhone 11 Pro Max"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/3B059333-96F6-433E-87AB-1F1129B17204\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/3B059333-96F6-433E-87AB-1F1129B17204",
                            "udid" : "3B059333-96F6-433E-87AB-1F1129B17204",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-12-mini",
                            "state" : "Shutdown",
                            "name" : "iPhone 12 mini"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/052F17AD-D52D-4885-97F8-6CDD27C6640E\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/052F17AD-D52D-4885-97F8-6CDD27C6640E",
                            "udid" : "052F17AD-D52D-4885-97F8-6CDD27C6640E",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-12",
                            "state" : "Shutdown",
                            "name" : "iPhone 12"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/A39824F9-D33A-458D-9331-1F3925B218B9\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/A39824F9-D33A-458D-9331-1F3925B218B9",
                            "udid" : "A39824F9-D33A-458D-9331-1F3925B218B9",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro",
                            "state" : "Shutdown",
                            "name" : "iPhone 12 Pro"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/DB4021F0-3F6D-49E9-B911-2BD44BA3074F\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/DB4021F0-3F6D-49E9-B911-2BD44BA3074F",
                            "udid" : "DB4021F0-3F6D-49E9-B911-2BD44BA3074F",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro-Max",
                            "state" : "Shutdown",
                            "name" : "iPhone 12 Pro Max"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/E5026D1F-DC9E-426F-BA7B-3AA93451E4FC\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/E5026D1F-DC9E-426F-BA7B-3AA93451E4FC",
                            "udid" : "E5026D1F-DC9E-426F-BA7B-3AA93451E4FC",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro",
                            "state" : "Shutdown",
                            "name" : "iPhone 13 Pro"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/048108E4-D2A3-48FF-A4F5-7FF86434839F\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/048108E4-D2A3-48FF-A4F5-7FF86434839F",
                            "udid" : "048108E4-D2A3-48FF-A4F5-7FF86434839F",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro-Max",
                            "state" : "Shutdown",
                            "name" : "iPhone 13 Pro Max"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/80C8B9CB-8814-4FF5-9CF6-94F6F7077A34\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/80C8B9CB-8814-4FF5-9CF6-94F6F7077A34",
                            "udid" : "80C8B9CB-8814-4FF5-9CF6-94F6F7077A34",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-13-mini",
                            "state" : "Shutdown",
                            "name" : "iPhone 13 mini"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/3631D8FA-C8D7-4BF5-9C0B-D1CA0FCB767F\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/3631D8FA-C8D7-4BF5-9C0B-D1CA0FCB767F",
                            "udid" : "3631D8FA-C8D7-4BF5-9C0B-D1CA0FCB767F",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-13",
                            "state" : "Shutdown",
                            "name" : "iPhone 13"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/DE894E91-DCB8-4BE0-93B5-34B787114A91\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/DE894E91-DCB8-4BE0-93B5-34B787114A91",
                            "udid" : "DE894E91-DCB8-4BE0-93B5-34B787114A91",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-SE-3rd-generation",
                            "state" : "Shutdown",
                            "name" : "iPhone SE (3rd generation)"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/A985A663-9AFD-4DD1-BBE9-981AA630F00D\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/A985A663-9AFD-4DD1-BBE9-981AA630F00D",
                            "udid" : "A985A663-9AFD-4DD1-BBE9-981AA630F00D",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPod-touch--7th-generation-",
                            "state" : "Shutdown",
                            "name" : "iPod touch (7th generation)"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/22EB516F-8480-4217-9935-2F007AA9F42C\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/22EB516F-8480-4217-9935-2F007AA9F42C",
                            "udid" : "22EB516F-8480-4217-9935-2F007AA9F42C",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPad-Pro--9-7-inch-",
                            "state" : "Shutdown",
                            "name" : "iPad Pro (9.7-inch)"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/5C739224-2EDE-4CE6-ADB5-54B5F8B11BEF\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/5C739224-2EDE-4CE6-ADB5-54B5F8B11BEF",
                            "udid" : "5C739224-2EDE-4CE6-ADB5-54B5F8B11BEF",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPad-9th-generation",
                            "state" : "Shutdown",
                            "name" : "iPad (9th generation)"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/2D84767E-BC58-4AFD-AFFD-6A9D7670B16B\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/2D84767E-BC58-4AFD-AFFD-6A9D7670B16B",
                            "udid" : "2D84767E-BC58-4AFD-AFFD-6A9D7670B16B",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPad-Pro-11-inch-3rd-generation",
                            "state" : "Shutdown",
                            "name" : "iPad Pro (11-inch) (3rd generation)"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/8C7E6ED4-9F9B-4675-BEF4-736C7544375C\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/8C7E6ED4-9F9B-4675-BEF4-736C7544375C",
                            "udid" : "8C7E6ED4-9F9B-4675-BEF4-736C7544375C",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPad-Pro-12-9-inch-5th-generation",
                            "state" : "Shutdown",
                            "name" : "iPad Pro (12.9-inch) (5th generation)"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/FA9FA89C-AC7B-41B4-8CBF-1583B52F1662\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/FA9FA89C-AC7B-41B4-8CBF-1583B52F1662",
                            "udid" : "FA9FA89C-AC7B-41B4-8CBF-1583B52F1662",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPad-Air-5th-generation",
                            "state" : "Shutdown",
                            "name" : "iPad Air (5th generation)"
                          },
                          {
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/25F13879-BE70-4256-BE00-E5EDBD9B2D3E\/data",
                            "dataPathSize" : 13316096,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/25F13879-BE70-4256-BE00-E5EDBD9B2D3E",
                            "udid" : "25F13879-BE70-4256-BE00-E5EDBD9B2D3E",
                            "isAvailable" : true,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPad-mini-6th-generation",
                            "state" : "Shutdown",
                            "name" : "iPad mini (6th generation)"
                          }
                        ],
                        "com.apple.CoreSimulator.SimRuntime.tvOS-15-2" : [
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/F0D148A6-95E5-4C2B-AAD9-20B343F581F7\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/F0D148A6-95E5-4C2B-AAD9-20B343F581F7",
                            "udid" : "F0D148A6-95E5-4C2B-AAD9-20B343F581F7",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-TV-1080p",
                            "state" : "Shutdown",
                            "name" : "Apple TV"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/9F4EC24E-D238-4FB8-A949-BE0B64852223\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/9F4EC24E-D238-4FB8-A949-BE0B64852223",
                            "udid" : "9F4EC24E-D238-4FB8-A949-BE0B64852223",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2nd-generation-4K",
                            "state" : "Shutdown",
                            "name" : "Apple TV 4K (2nd generation)"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/8E300EEC-2A09-4D34-941D-35E3043F28AC\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/8E300EEC-2A09-4D34-941D-35E3043F28AC",
                            "udid" : "8E300EEC-2A09-4D34-941D-35E3043F28AC",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2nd-generation-1080p",
                            "state" : "Shutdown",
                            "name" : "Apple TV 4K (at 1080p) (2nd generation)"
                          }
                        ],
                        "com.apple.CoreSimulator.SimRuntime.watchOS-8-3" : [
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/9535A885-DB9F-4928-8225-4E43C09A72C3\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/9535A885-DB9F-4928-8225-4E43C09A72C3",
                            "udid" : "9535A885-DB9F-4928-8225-4E43C09A72C3",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-5-40mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 5 - 40mm"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/96916268-CA7A-4B02-A34B-F735689703F8\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/96916268-CA7A-4B02-A34B-F735689703F8",
                            "udid" : "96916268-CA7A-4B02-A34B-F735689703F8",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-5-44mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 5 - 44mm"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/64A76DC4-C517-4C5A-A3FD-A9DA39B05BA6\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/64A76DC4-C517-4C5A-A3FD-A9DA39B05BA6",
                            "udid" : "64A76DC4-C517-4C5A-A3FD-A9DA39B05BA6",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-6-40mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 6 - 40mm"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/257BA6A9-9B49-4377-93D4-81DE64354F93\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/257BA6A9-9B49-4377-93D4-81DE64354F93",
                            "udid" : "257BA6A9-9B49-4377-93D4-81DE64354F93",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-6-44mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 6 - 44mm"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/591F5F99-3035-4FDD-BE1F-F5C22BF8C6CB\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/591F5F99-3035-4FDD-BE1F-F5C22BF8C6CB",
                            "udid" : "591F5F99-3035-4FDD-BE1F-F5C22BF8C6CB",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-7-41mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 7 - 41mm"
                          },
                          {
                            "availabilityError" : "runtime profile not found",
                            "dataPath" : "\/Users\/ken\/Library\/Developer\/CoreSimulator\/Devices\/7D056D33-57EA-47CB-9DC0-51867464EAF6\/data",
                            "dataPathSize" : 0,
                            "logPath" : "\/Users\/ken\/Library\/Logs\/CoreSimulator\/7D056D33-57EA-47CB-9DC0-51867464EAF6",
                            "udid" : "7D056D33-57EA-47CB-9DC0-51867464EAF6",
                            "isAvailable" : false,
                            "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-7-45mm",
                            "state" : "Shutdown",
                            "name" : "Apple Watch Series 7 - 45mm"
                          }
                        ]
                      }
                    }
q[+2974 ms] [
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone13,1",
                        "identifier" : "3B059333-96F6-433E-87AB-1F1129B17204",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-12-mini-1",
                        "modelName" : "iPhone 12 mini",
                        "name" : "iPhone 12 mini"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone12,5",
                        "identifier" : "D865C90F-2860-4E0D-A900-5D744A64D116",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-11-pro-max-1",
                        "modelName" : "iPhone 11 Pro Max",
                        "name" : "iPhone 11 Pro Max"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone13,4",
                          "identifier" : "DB4021F0-3F6D-49E9-B911-2BD44BA3074F",
                          "architecture" : "x86_64",
                          "modelUTI" : "com.apple.iphone-12-pro-max-1",
                          "modelName" : "iPhone 12 Pro Max",
                          "name" : "iPhone 12 Pro Max"
                        },
                        "modelCode" : "Watch5,4",
                        "identifier" : "24C02FB0-7E3B-4CC0-9BCB-7683D67F611A",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.watch-series5-1",
                        "modelName" : "Apple Watch Series 5 - 44mm",
                        "name" : "Apple Watch Series 5 - 44mm"
                      },
                      {
                        "simulator" : false,
                        "operatingSystemVersion" : "12.4 (21F79)",
                        "interface" : "usb",
                        "available" : true,
                        "platform" : "com.apple.platform.macosx",
                        "modelCode" : "MacBookPro12,1",
                        "identifier" : "95C58049-A66F-5CA1-BABD-6925E2ECE851",
                        "architecture" : "x86_64h",
                        "modelUTI" : "com.apple.macbookpro-13-retina-display",
                        "modelName" : "MacBook Pro",
                        "name" : "My Mac"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone14,2",
                          "identifier" : "E5026D1F-DC9E-426F-BA7B-3AA93451E4FC",
                          "architecture" : "x86_64",
                          "modelUTI" : "com.apple.iphone-13-pro-1",
                          "modelName" : "iPhone 13 Pro",
                          "name" : "iPhone 13 Pro"
                        },
                        "modelCode" : "Watch6,1",
                        "identifier" : "F86B0909-88A3-4088-ACD0-084A9C753974",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.watch-series6-1",
                        "modelName" : "Apple Watch Series 6 - 40mm",
                        "name" : "Apple Watch Series 6 - 40mm"
                      },
                      {
                        "simulator" : false,
                        "operatingSystemVersion" : "15.4.1 (19E258)",
                        "interface" : "usb",
                        "available" : true,
                        "platform" : "com.apple.platform.iphoneos",
                        "modelCode" : "iPhone12,1",
                        "identifier" : "00008030-0004551014E8802E",
                        "architecture" : "arm64e",
                        "modelUTI" : "com.apple.iphone-11-2",
                        "modelName" : "iPhone 11",
                        "name" : "iPhone (2)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad13,17",
                        "identifier" : "FA9FA89C-AC7B-41B4-8CBF-1583B52F1662",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.ipad-air5-1",
                        "modelName" : "iPad Air (5th generation)",
                        "name" : "iPad Air (5th generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone10,5",
                        "identifier" : "0173A5F1-4288-4C05-AF7F-04964DFB789E",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-8-plus-2",
                        "modelName" : "iPhone 8 Plus",
                        "name" : "iPhone 8 Plus"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone12,3",
                        "identifier" : "5F56FFED-31C2-4AAF-B960-D4499BEA12DC",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-11-pro-1",
                        "modelName" : "iPhone 11 Pro",
                        "name" : "iPhone 11 Pro"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad13,5",
                        "identifier" : "2D84767E-BC58-4AFD-AFFD-6A9D7670B16B",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.ipad-pro-11-3rd-1",
                        "modelName" : "iPad Pro (11-inch) (3rd generation)",
                        "name" : "iPad Pro (11-inch) (3rd generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone14,6",
                        "identifier" : "DE894E91-DCB8-4BE0-93B5-34B787114A91",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-se3-1",
                        "modelName" : "iPhone SE (3rd generation)",
                        "name" : "iPhone SE (3rd generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone14,4",
                          "identifier" : "80C8B9CB-8814-4FF5-9CF6-94F6F7077A34",
                          "architecture" : "x86_64",
                          "modelUTI" : "com.apple.iphone-13-mini-1",
                          "modelName" : "iPhone 13 mini",
                          "name" : "iPhone 13 mini"
                        },
                        "modelCode" : "Watch6,6",
                        "identifier" : "51B4BC91-1DF6-4316-A25D-4D98A1080B92",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.watch-series7-1",
                        "modelName" : "Apple Watch Series 7 - 41mm",
                        "name" : "Apple Watch Series 7 - 41mm"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.4 (19L439)",
                        "available" : true,
                        "platform" : "com.apple.platform.appletvsimulator",
                        "modelCode" : "AppleTV11,1",
                        "identifier" : "ADC10806-83B1-4874-B27B-BD557B2589A5",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.apple-tv-4k-2nd",
                        "modelName" : "Apple TV 4K (2nd generation)",
                        "name" : "Apple TV 4K (2nd generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone14,3",
                        "identifier" : "048108E4-D2A3-48FF-A4F5-7FF86434839F",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-13-pro-max-1",
                        "modelName" : "iPhone 13 Pro Max",
                        "name" : "iPhone 13 Pro Max"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone13,3",
                        "identifier" : "A39824F9-D33A-458D-9331-1F3925B218B9",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-12-pro-1",
                        "modelName" : "iPhone 12 Pro",
                        "name" : "iPhone 12 Pro"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPod9,1",
                        "identifier" : "A985A663-9AFD-4DD1-BBE9-981AA630F00D",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.ipod-touch-7-2",
                        "modelName" : "iPod touch (7th generation)",
                        "name" : "iPod touch (7th generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.4 (19L439)",
                        "available" : true,
                        "platform" : "com.apple.platform.appletvsimulator",
                        "modelCode" : "AppleTV5,3",
                        "identifier" : "07E03BEA-CA86-41A9-B410-61ADDAEB8647",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.apple-tv-4",
                        "modelName" : "Apple TV",
                        "name" : "Apple TV"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad12,2",
                        "identifier" : "5C739224-2EDE-4CE6-ADB5-54B5F8B11BEF",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.ipad-9-wwan-1",
                        "modelName" : "iPad (9th generation)",
                        "name" : "iPad (9th generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone14,5",
                        "identifier" : "3631D8FA-C8D7-4BF5-9C0B-D1CA0FCB767F",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-13-1",
                        "modelName" : "iPhone 13",
                        "name" : "iPhone 13"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone10,4",
                        "identifier" : "18811BFB-C258-49EC-AB73-6E9FFF4D75EC",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-8-2",
                        "modelName" : "iPhone 8",
                        "name" : "iPhone 8"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone14,4",
                        "identifier" : "80C8B9CB-8814-4FF5-9CF6-94F6F7077A34",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-13-mini-1",
                        "modelName" : "iPhone 13 mini",
                        "name" : "iPhone 13 mini"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad6,4",
                        "identifier" : "22EB516F-8480-4217-9935-2F007AA9F42C",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.ipad-pro-9point7-a1674-b9b7ba",
                        "modelName" : "iPad Pro (9.7-inch)",
                        "name" : "iPad Pro (9.7-inch)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone14,2",
                        "identifier" : "E5026D1F-DC9E-426F-BA7B-3AA93451E4FC",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-13-pro-1",
                        "modelName" : "iPhone 13 Pro",
                        "name" : "iPhone 13 Pro"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad14,1",
                        "identifier" : "25F13879-BE70-4256-BE00-E5EDBD9B2D3E",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.ipad-mini6-1",
                        "modelName" : "iPad mini (6th generation)",
                        "name" : "iPad mini (6th generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone13,4",
                        "identifier" : "DB4021F0-3F6D-49E9-B911-2BD44BA3074F",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-12-pro-max-1",
                        "modelName" : "iPhone 12 Pro Max",
                        "name" : "iPhone 12 Pro Max"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone12,1",
                        "identifier" : "70396614-24D5-4104-A736-08D322BB3FDF",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-11-1",
                        "modelName" : "iPhone 11",
                        "name" : "iPhone 11"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone13,3",
                          "identifier" : "A39824F9-D33A-458D-9331-1F3925B218B9",
                          "architecture" : "x86_64",
                          "modelUTI" : "com.apple.iphone-12-pro-1",
                          "modelName" : "iPhone 12 Pro",
                          "name" : "iPhone 12 Pro"
                        },
                        "modelCode" : "Watch5,3",
                        "identifier" : "64A75137-3482-4AB5-A821-FBC0AAA57C45",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.watch-series5-1",
                        "modelName" : "Apple Watch Series 5 - 40mm",
                        "name" : "Apple Watch Series 5 - 40mm"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone14,5",
                          "identifier" : "3631D8FA-C8D7-4BF5-9C0B-D1CA0FCB767F",
                          "architecture" : "x86_64",
                          "modelUTI" : "com.apple.iphone-13-1",
                          "modelName" : "iPhone 13",
                          "name" : "iPhone 13"
                        },
                        "modelCode" : "Watch6,9",
                        "identifier" : "890EB1B4-A249-4890-86BF-1CDF11DC3F4C",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.watch-series7-1",
                        "modelName" : "Apple Watch Series 7 - 45mm",
                        "name" : "Apple Watch Series 7 - 45mm"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone14,3",
                          "identifier" : "048108E4-D2A3-48FF-A4F5-7FF86434839F",
                          "architecture" : "x86_64",
                          "modelUTI" : "com.apple.iphone-13-pro-max-1",
                          "modelName" : "iPhone 13 Pro Max",
                          "name" : "iPhone 13 Pro Max"
                        },
                        "modelCode" : "Watch6,2",
                        "identifier" : "F525CACE-0538-4101-9BFF-EE9BBB57439E",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.watch-series6-1",
                        "modelName" : "Apple Watch Series 6 - 44mm",
                        "name" : "Apple Watch Series 6 - 44mm"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.4 (19L439)",
                        "available" : true,
                        "platform" : "com.apple.platform.appletvsimulator",
                        "modelCode" : "AppleTV11,1",
                        "identifier" : "F160B929-761C-4736-B36B-F0172B2018A1",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.apple-tv-4k-2nd",
                        "modelName" : "Apple TV 4K (at 1080p) (2nd generation)",
                        "name" : "Apple TV 4K (at 1080p) (2nd generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad13,10",
                        "identifier" : "8C7E6ED4-9F9B-4675-BEF4-736C7544375C",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.ipad-pro-12point9-5th-1",
                        "modelName" : "iPad Pro (12.9-inch) (5th generation)",
                        "name" : "iPad Pro (12.9-inch) (5th generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone13,2",
                        "identifier" : "052F17AD-D52D-4885-97F8-6CDD27C6640E",
                        "architecture" : "x86_64",
                        "modelUTI" : "com.apple.iphone-12-1",
                        "modelName" : "iPhone 12",
                        "name" : "iPhone 12"
                      }
                    ]

                    2022-05-26 04:46:25.498 xcdevice[10370:76063] Requested but did not find extension point with identifier Xcode.IDEKit.ExtensionSentinelHostApplications for
                    extension Xcode.DebuggerFoundation.AppExtensionHosts.watchOS of plug-in com.apple.dt.IDEWatchSupportCore
                    2022-05-26 04:46:25.498 xcdevice[10370:76063] Requested but did not find extension point with identifier Xcode.IDEKit.ExtensionPointIdentifierToBundleIdentifier
                    for extension Xcode.DebuggerFoundation.AppExtensionToBundleIdentifierMap.watchOS of plug-in com.apple.dt.IDEWatchSupportCore
[  +28 ms] /Users/ken/Library/Android/sdk/platform-tools/adb -s LMQ610TA3526ef8 shell getprop
[ +121 ms] Artifact Instance of 'AndroidInternalBuildArtifacts' is not required, skipping update.
[  +14 ms] Artifact Instance of 'WindowsEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'WindowsUwpEngineArtifacts' is not required, skipping update.
[   +9 ms] Artifact Instance of 'LinuxEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'LinuxFuchsiaSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'MacOSFuchsiaSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterRunnerSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterRunnerDebugSymbols' is not required, skipping update.
[  +54 ms] Changing current working directory to: /Users/ken/StudioProjects/lessimp
[ +122 ms] Multiple devices found:
[   +4 ms] ro.hardware = cv5a
[        ] ro.build.characteristics = default
[   +9 ms] LM Q610 FGN (mobile) • LMQ610TA3526ef8           • android-arm • Android 9 (API 28)
[   +1 ms] iPhone (2) (mobile)  • 00008030-0004551014E8802E • ios         • iOS 15.4.1 19E258
[   +1 ms] [1]: LM Q610 FGN (LMQ610TA3526ef8)
[        ] [2]: iPhone (2) (00008030-0004551014E8802E)
[   +3 ms] Please choose one (To quit, press "q/Q")
[        ] : 
[  +11 ms] q
[  +36 ms] "flutter run" took 4,363ms.
[  +80 ms] 
           #0      throwToolExit (package:flutter_tools/src/base/common.dart:10:3)
           #1      DeviceManager._chooseOneOfAvailableDevices (package:flutter_tools/src/device.dart:314:7)
           <asynchronous suspension>
           #2      DeviceManager.findTargetDevices (package:flutter_tools/src/device.dart:302:37)
           <asynchronous suspension>
           #3      FlutterCommand.findAllTargetDevices (package:flutter_tools/src/runner/flutter_command.dart:1378:28)
           <asynchronous suspension>
           #4      RunCommand.validateCommand (package:flutter_tools/src/commands/run.dart:482:15)
           <asynchronous suspension>
           #5      FlutterCommand.verifyThenRunCommand (package:flutter_tools/src/runner/flutter_command.dart:1298:5)
           <asynchronous suspension>
           #6      FlutterCommand.run.<anonymous closure> (package:flutter_tools/src/runner/flutter_command.dart:1183:27)
           <asynchronous suspension>
           #7      AppContext.run.<anonymous closure> (package:flutter_tools/src/base/context.dart:150:19)
           <asynchronous suspension>
           #8      CommandRunner.runCommand (package:args/command_runner.dart:209:13)
           <asynchronous suspension>
           #9      FlutterCommandRunner.runCommand.<anonymous closure> (package:flutter_tools/src/runner/flutter_command_runner.dart:281:9)
           <asynchronous suspension>
           #10     AppContext.run.<anonymous closure> (package:flutter_tools/src/base/context.dart:150:19)
           <asynchronous suspension>
           #11     FlutterCommandRunner.runCommand (package:flutter_tools/src/runner/flutter_command_runner.dart:229:5)
           <asynchronous suspension>
           #12     run.<anonymous closure>.<anonymous closure> (package:flutter_tools/runner.dart:62:9)
           <asynchronous suspension>
           #13     AppContext.run.<anonymous closure> (package:flutter_tools/src/base/context.dart:150:19)
           <asynchronous suspension>
           #14     main (package:flutter_tools/executable.dart:94:3)
           <asynchronous suspension>
           
           
[ +269 ms] ensureAnalyticsSent: 255ms
[   +2 ms] Running shutdown hooks
[        ] Shutdown hooks complete
[   +1 ms] exiting with code 1
