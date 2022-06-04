# lessimp_logs
Logs for view when needed

Run flutter build apk --release
  
💪 Building with sound null safety 💪
Running Gradle task 'assembleRelease'...                        
/opt/hostedtoolcache/flutter/3.0.1-stable/x64/.pub-cache/hosted/pub.dartlang.org/mobile_scanner-1.1.2/lib/src/mobile_scanner.dart:50:20: Warning: Operand of null-aware operation '?.' has type 'WidgetsBinding' which excludes null.
 - 'WidgetsBinding' is from 'package:flutter/src/widgets/binding.dart' ('/opt/hostedtoolcache/flutter/3.0.1-stable/x64/packages/flutter/lib/src/widgets/binding.dart').
    WidgetsBinding.instance?.addObserver(this);
                   ^
/opt/hostedtoolcache/flutter/3.0.1-stable/x64/.pub-cache/hosted/pub.dartlang.org/mobile_scanner-1.1.2/lib/src/mobile_scanner.dart:134:20: Warning: Operand of null-aware operation '?.' has type 'WidgetsBinding' which excludes null.
 - 'WidgetsBinding' is from 'package:flutter/src/widgets/binding.dart' ('/opt/hostedtoolcache/flutter/3.0.1-stable/x64/packages/flutter/lib/src/widgets/binding.dart').
    WidgetsBinding.instance?.removeObserver(this);
                   ^
/opt/hostedtoolcache/flutter/3.0.1-stable/x64/.pub-cache/hosted/pub.dartlang.org/card_swiper-2.0.3/lib/src/custom_layout.dart:36:20: Warning: Operand of null-aware operation '!' has type 'WidgetsBinding' which excludes null.
 - 'WidgetsBinding' is from 'package:flutter/src/widgets/binding.dart' ('/opt/hostedtoolcache/flutter/3.0.1-stable/x64/packages/flutter/lib/src/widgets/binding.dart').
    WidgetsBinding.instance!.addPostFrameCallback(_getSize);
                   ^
/opt/hostedtoolcache/flutter/3.0.1-stable/x64/.pub-cache/hosted/pub.dartlang.org/card_swiper-2.0.3/lib/src/transformer_page_view/transformer_page_view.dart:540:22: Warning: Operand of null-aware operation '!' has type 'WidgetsBinding' which excludes null.
 - 'WidgetsBinding' is from 'package:flutter/src/widgets/binding.dart' ('/opt/hostedtoolcache/flutter/3.0.1-stable/x64/packages/flutter/lib/src/widgets/binding.dart').
      WidgetsBinding.instance!.addPostFrameCallback(_onGetSize);
                     ^
/opt/hostedtoolcache/flutter/3.0.1-stable/x64/.pub-cache/hosted/pub.dartlang.org/card_swiper-2.0.3/lib/src/transformer_page_view/transformer_page_view.dart:554:22: Warning: Operand of null-aware operation '!' has type 'WidgetsBinding' which excludes null.
 - 'WidgetsBinding' is from 'package:flutter/src/widgets/binding.dart' ('/opt/hostedtoolcache/flutter/3.0.1-stable/x64/packages/flutter/lib/src/widgets/binding.dart').
      WidgetsBinding.instance!.addPostFrameCallback(_onGetSize);
                     ^
Note: /opt/hostedtoolcache/flutter/3.0.1-stable/x64/.pub-cache/hosted/pub.dartlang.org/firebase_crashlytics-2.8.1/android/src/main/java/io/flutter/plugins/firebase/crashlytics/FlutterFirebaseCrashlyticsPlugin.java uses or overrides a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Note: /opt/hostedtoolcache/flutter/3.0.1-stable/x64/.pub-cache/hosted/pub.dartlang.org/location-4.4.0/android/src/main/java/com/lyokone/location/FlutterLocation.java uses or overrides a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
WARNING: [Processor] Library '/home/runner/.gradle/caches/modules-2/files-2.1/org.robolectric/shadows-framework/4.3/150103d5732c432906f6130b734e7452855dd67b/shadows-framework-4.3.jar' contains references to both AndroidX and old support library. This seems like the library is partially migrated. Jetifier will try to rewrite the library anyway.
 Example of androidX reference: 'androidx/test/runner/lifecycle/Stage'
 Example of support library reference: 'android/support/annotation/NonNull'
FAILURE: Build failed with an exception.
* What went wrong:
Execution failed for task ':app:lintVitalRelease'.
> Could not resolve all artifacts for configuration ':image_picker_android:debugUnitTestRuntimeClasspath'.
   > Failed to transform bcprov-jdk15on-1.68.jar (org.bouncycastle:bcprov-jdk15on:1.68) to match attributes {artifactType=processed-jar, org.gradle.category=library, org.gradle.libraryelements=jar, org.gradle.status=release, org.gradle.usage=java-runtime}.
      > Execution failed for JetifyTransform: /home/runner/.gradle/caches/modules-2/files-2.1/org.bouncycastle/bcprov-jdk15on/1.68/46a080368d38b428d237a59458f9bc915222894d/bcprov-jdk15on-1.68.jar.
         > Failed to transform '/home/runner/.gradle/caches/modules-2/files-2.1/org.bouncycastle/bcprov-jdk15on/1.68/46a080368d38b428d237a59458f9bc915222894d/bcprov-jdk15on-1.68.jar' using Jetifier. Reason: IllegalArgumentException, message: Unsupported class file major version 59. (Run with --stacktrace for more details.)
           Suggestions:
            - Check out existing issues at https://issuetracker.google.com/issues?q=componentid:460323&s=modified_time:desc, it's possible that this issue has already been filed there.
            - If this issue has not been filed, please report it at https://issuetracker.google.com/issues/new?component=460323 (run with --stacktrace and provide a stack trace if possible).
* Try:
> Run with --stacktrace option to get the stack trace.
> Run with --info or --debug option to get more log output.
> Run with --scan to get full insights.
* Get more help at https://help.gradle.org
BUILD FAILED in 4m 52s
Running Gradle task 'assembleRelease'...                          293.2s
Gradle task assembleRelease failed with exit code 1
Error: Process completed with exit code 1.
