Built by ant tool first
And then import to the project

F:\tools\dev\android\sdkwork\HelloWorld>ant release
Buildfile: F:\tools\dev\android\sdkwork\HelloWorld\build.xml

-set-mode-check:

-set-release-mode:

-release-obfuscation-check:
     [echo] proguard.config is ${proguard.config}

-pre-build:

-check-env:
 [checkenv] Android SDK Tools Revision 25.2.2
 [checkenv] Installed at F:\tools\dev\android\SDK\android-sdk

-setup:
     [echo] Project Name: HelloWorld
  [gettype] Project Type: Application

-build-setup:
[getbuildtools] Using latest Build Tools: 24.0.2
     [echo] Resolving Build Target for HelloWorld...
[gettarget] Project Target:   Android 5.0.1
[gettarget] API level:        21
[gettarget] WARNING: No minSdkVersion value set. Application will install on all Android versions.
     [echo] ----------
     [echo] Creating output directories if needed...
    [mkdir] Created dir: F:\tools\dev\android\sdkwork\HelloWorld\bin\res
    [mkdir] Created dir: F:\tools\dev\android\sdkwork\HelloWorld\bin\rsObj
    [mkdir] Created dir: F:\tools\dev\android\sdkwork\HelloWorld\bin\rsLibs
    [mkdir] Created dir: F:\tools\dev\android\sdkwork\HelloWorld\gen
    [mkdir] Created dir: F:\tools\dev\android\sdkwork\HelloWorld\bin\classes
    [mkdir] Created dir: F:\tools\dev\android\sdkwork\HelloWorld\bin\dexedLibs
     [echo] ----------
     [echo] Resolving Dependencies for HelloWorld...
[dependency] Library dependencies:
[dependency] No Libraries
[dependency]
[dependency] ------------------
     [echo] ----------
     [echo] Building Libraries with 'release'...
   [subant] No sub-builds to iterate on

-code-gen:
[mergemanifest] Merging AndroidManifest files into one.
[mergemanifest] Manifest merger disabled. Using project manifest only.
     [echo] Handling aidl files...
     [aidl] No AIDL files to compile.
     [echo] ----------
     [echo] Handling RenderScript files...
     [echo] ----------
     [echo] Handling Resources...
     [aapt] Generating resource IDs...
     [echo] ----------
     [echo] Handling BuildConfig class...
[buildconfig] Generating BuildConfig class.

-pre-compile:

-compile:
    [javac] Compiling 3 source files to F:\tools\dev\android\sdkwork\HelloWorld\bin\classes
    [javac] warning: [options] source value 1.5 is obsolete and will be removed in a future release
    [javac] warning: [options] target value 1.5 is obsolete and will be removed in a future release
    [javac] warning: [options] To suppress warnings about obsolete options, use -Xlint:-options.
    [javac] 3 warnings

-post-compile:

-obfuscate:

-dex:
      [dex] input: F:\tools\dev\android\sdkwork\HelloWorld\bin\classes
      [dex] Converting compiled files and external libraries into F:\tools\dev\android\sdkwork\HelloWorld\bin\classes.dex...

-crunch:
   [crunch] Crunching PNG Files in source dir: F:\tools\dev\android\sdkwork\HelloWorld\res
   [crunch] To destination dir: F:\tools\dev\android\sdkwork\HelloWorld\bin\res
   [crunch] Processing image to cache: F:\tools\dev\android\sdkwork\HelloWorld\res\drawable-hdpi\ic_launcher.png => F:\tools\dev\android\sdkwork\HelloWorld\bin\res\drawable-hdpi\ic_launcher.png
   [crunch]   (processed image to cache entry F:\tools\dev\android\sdkwork\HelloWorld\bin\res\drawable-hdpi\ic_launcher.png: 43% size of source)
   [crunch] Processing image to cache: F:\tools\dev\android\sdkwork\HelloWorld\res\drawable-ldpi\ic_launcher.png => F:\tools\dev\android\sdkwork\HelloWorld\bin\res\drawable-ldpi\ic_launcher.png
   [crunch]   (processed image to cache entry F:\tools\dev\android\sdkwork\HelloWorld\bin\res\drawable-ldpi\ic_launcher.png: 0% size of source)
   [crunch] Processing image to cache: F:\tools\dev\android\sdkwork\HelloWorld\res\drawable-mdpi\ic_launcher.png => F:\tools\dev\android\sdkwork\HelloWorld\bin\res\drawable-mdpi\ic_launcher.png
   [crunch]   (processed image to cache entry F:\tools\dev\android\sdkwork\HelloWorld\bin\res\drawable-mdpi\ic_launcher.png: 78% size of source)
   [crunch] Processing image to cache: F:\tools\dev\android\sdkwork\HelloWorld\res\drawable-xhdpi\ic_launcher.png => F:\tools\dev\android\sdkwork\HelloWorld\bin\res\drawable-xhdpi\ic_launcher.png
   [crunch]   (processed image to cache entry F:\tools\dev\android\sdkwork\HelloWorld\bin\res\drawable-xhdpi\ic_launcher.png: 56% size of source)
   [crunch] Crunched 4 PNG files to update cache

-package-resources:
     [aapt] Creating full resource package...

-package:
[apkbuilder] Current build type is different than previous build: forced apkbuilder run.
[apkbuilder] Creating HelloWorld-release-unsigned.apk for release...

-post-package:

-release-prompt-for-password:

-release-nosign:
     [echo] No key.store and key.alias properties found in build.properties.
     [echo] Please sign F:\tools\dev\android\sdkwork\HelloWorld\bin\HelloWorld-release-unsigned.apk manually
     [echo] and run zipalign from the Android SDK tools.
[propertyfile] Creating new property file: F:\tools\dev\android\sdkwork\HelloWorld\bin\build.prop
[propertyfile] Updating property file: F:\tools\dev\android\sdkwork\HelloWorld\bin\build.prop
[propertyfile] Updating property file: F:\tools\dev\android\sdkwork\HelloWorld\bin\build.prop
[propertyfile] Updating property file: F:\tools\dev\android\sdkwork\HelloWorld\bin\build.prop

-release-sign:

-post-build:

release:

BUILD SUCCESSFUL
Total time: 4 seconds