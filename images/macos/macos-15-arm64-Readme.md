| Announcements |
|-|
| [[macOS] The macOS 12 Actions runner image will begin deprecation on 10/7/24 and will be fully unsupported by 12/3/24 for GitHub and ADO](https://github.com/actions/runner-images/issues/10721) |
| [[macOS] Support policy changes; Xcode 14 and 16 will be removed from macOS 14 on October 28](https://github.com/actions/runner-images/issues/10703) |
| [macOS 15 (Sequoia) is now available as a public beta in GitHub Actions](https://github.com/actions/runner-images/issues/10686) |
| [[Macos 13 and 14] Android NDK versions <=25 will be removed from images on October 07,2024](https://github.com/actions/runner-images/issues/10614) |
| [[Macos 13 and 14] Go version 1.20.0 will be removed on October 07,2024.](https://github.com/actions/runner-images/issues/10612) |
***
# macOS 15
- OS Version: macOS 15.0 (24A335)
- Kernel Version: Darwin 24.0.0
- Image Version: 20241007.159

## Installed Software

### Language and Runtime
- .NET Core SDK: 8.0.101, 8.0.204, 8.0.303, 8.0.402
- Bash 3.2.57(1)-release
- Clang/LLVM 16.0.0
- Clang/LLVM (Homebrew) 18.1.8 - available on `$(brew --prefix llvm@18)/bin/clang`
- GCC 12 (Homebrew GCC 12.4.0) - available by `gcc-12` alias
- GCC 13 (Homebrew GCC 13.3.0) - available by `gcc-13` alias
- GCC 14 (Homebrew GCC 14.2.0) - available by `gcc-14` alias
- GNU Fortran 12 (Homebrew GCC 12.4.0) - available by `gfortran-12` alias
- GNU Fortran 13 (Homebrew GCC 13.3.0) - available by `gfortran-13` alias
- GNU Fortran 14 (Homebrew GCC 14.2.0) - available by `gfortran-14` alias
- Kotlin 2.0.20-release-360
- Node.js 22.9.0
- Perl 5.38.2
- Python3 3.12.7
- Ruby 3.3.5

### Package Management
- Bundler 2.5.21
- Carthage 0.40.0
- CocoaPods 1.15.2
- Homebrew 4.4.0
- NPM 10.8.3
- Pip3 24.2 (python 3.12)
- Pipx 1.7.1
- RubyGems 3.5.21
- Yarn 1.22.22

### Project Management
- Apache Ant 1.10.15
- Apache Maven 3.9.9
- Gradle 8.10.2

### Utilities
- 7-Zip 17.05
- aria2 1.37.0
- azcopy 10.26.0
- bazel 7.3.2
- bazelisk 1.22.0
- bsdtar 3.5.3 - available by 'tar' alias
- Curl 8.7.1
- Git 2.46.2
- Git LFS 3.5.1
- GitHub CLI 2.58.0
- GNU Tar 1.35 - available by 'gtar' alias
- GNU Wget 1.24.5
- gpg (GnuPG) 2.4.5
- jq 1.7.1
- OpenSSL 1.1.1w  11 Sep 2023
- Packer 1.11.2
- pkg-config 0.29.2
- yq 4.44.3
- zstd 1.5.6

### Tools
- AWS CLI 2.18.0
- AWS SAM CLI 1.125.0
- AWS Session Manager CLI 1.2.650.0
- Azure CLI 2.64.0
- Azure CLI (azure-devops) 1.0.1
- Bicep CLI 0.30.23
- Cmake 3.30.4
- CodeQL Action Bundle 2.19.0
- Fastlane 2.224.0
- SwiftFormat 0.54.5
- Xcbeautify 2.11.0
- Xcode Command Line Tools 16.0.0.0.1.1724870825
- Xcodes 1.5.0

### Linters

### Browsers
- Safari 18.0 (20619.1.26.31.6)
- SafariDriver 18.0 (20619.1.26.31.6)
- Google Chrome 129.0.6668.90
- Google Chrome for Testing 129.0.6668.89
- ChromeDriver 129.0.6668.89
- Selenium server 4.25.0

#### Environment variables
| Name            | Value                                   |
| --------------- | --------------------------------------- |
| CHROMEWEBDRIVER | /usr/local/share/chromedriver-mac-arm64 |
| EDGEWEBDRIVER   |                                         |
| GECKOWEBDRIVER  |                                         |

### Java
| Version              | Environment Variable |
| -------------------- | -------------------- |
| 11.0.24+8            | JAVA_HOME_11_arm64   |
| 17.0.12+7            | JAVA_HOME_17_arm64   |
| 21.0.4+7.0 (default) | JAVA_HOME_21_arm64   |

### Cached Tools

#### Python
- 3.11.9
- 3.12.7

#### Node.js
- 18.20.4
- 20.17.0

#### Go
- 1.21.13
- 1.22.8
- 1.23.2

### Rust Tools
- Cargo 1.81.0
- Rust 1.81.0
- Rustdoc 1.81.0
- Rustup 1.27.1

#### Packages
- Clippy 0.1.81
- Rustfmt 1.7.1-stable

### PowerShell Tools
- PowerShell 7.4.5

#### PowerShell Modules
- Az: 12.3.0
- Pester: 5.6.1
- PSScriptAnalyzer: 1.22.0

### Xcode
| Version        | Build    | Path                                |
| -------------- | -------- | ----------------------------------- |
| 16.1 (beta)    | 16B5014f | /Applications/Xcode_16.1_beta_2.app |
| 16.0 (default) | 16A242d  | /Applications/Xcode_16.app          |

#### Installed SDKs
| SDK                      | SDK Name             | Xcode Version |
| ------------------------ | -------------------- | ------------- |
| macOS 15.0               | macosx15.0           | 16.0          |
| macOS 15.1               | macosx15.1           | 16.1          |
| iOS 18.0                 | iphoneos18.0         | 16.0          |
| iOS 18.1                 | iphoneos18.1         | 16.1          |
| Simulator - iOS 18.0     | iphonesimulator18.0  | 16.0          |
| Simulator - iOS 18.1     | iphonesimulator18.1  | 16.1          |
| tvOS 18.0                | appletvos18.0        | 16.0          |
| tvOS 18.1                | appletvos18.1        | 16.1          |
| Simulator - tvOS 18.0    | appletvsimulator18.0 | 16.0          |
| Simulator - tvOS 18.1    | appletvsimulator18.1 | 16.1          |
| watchOS 11.0             | watchos11.0          | 16.0          |
| watchOS 11.1             | watchos11.1          | 16.1          |
| Simulator - watchOS 11.0 | watchsimulator11.0   | 16.0          |
| Simulator - watchOS 11.1 | watchsimulator11.1   | 16.1          |
| visionOS 2.0             | xros2.0              | 16.0          |
| Simulator - visionOS 2.0 | xrsimulator2.0       | 16.0          |
| Simulator - visionOS 2.1 | xrsimulator2.1       | 16.1          |
| visionOS 2.1             | xros2.1              | 16.1          |
| DriverKit 24.0           | driverkit24.0        | 16.0          |
| DriverKit 24.1           | driverkit24.1        | 16.1          |

#### Installed Simulators
| OS           | Simulators                                                                                                                                                                                                                                                  |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| iOS 18.0     | iPhone 16<br>iPhone 16 Plus<br>iPhone 16 Pro<br>iPhone 16 Pro Max<br>iPhone SE (3rd generation)<br>iPad (10th generation)<br>iPad Air 11-inch (M2)<br>iPad Air 13-inch (M2)<br>iPad mini (6th generation)<br>iPad Pro 11-inch (M4)<br>iPad Pro 13-inch (M4) |
| iOS 18.1     | iPhone 16<br>iPhone 16 Plus<br>iPhone 16 Pro<br>iPhone 16 Pro Max<br>iPhone SE (3rd generation)<br>iPad (10th generation)<br>iPad Air 11-inch (M2)<br>iPad Air 13-inch (M2)<br>iPad mini (6th generation)<br>iPad Pro 11-inch (M4)<br>iPad Pro 13-inch (M4) |
| tvOS 18.0    | Apple TV<br>Apple TV 4K (3rd generation)<br>Apple TV 4K (3rd generation) (at 1080p)                                                                                                                                                                         |
| tvOS 18.1    | Apple TV<br>Apple TV 4K (3rd generation)<br>Apple TV 4K (3rd generation) (at 1080p)                                                                                                                                                                         |
| watchOS 11.0 | Apple Watch SE (40mm) (2nd generation)<br>Apple Watch SE (44mm) (2nd generation)<br>Apple Watch Series 10 (42mm)<br>Apple Watch Series 10 (46mm)<br>Apple Watch Ultra 2 (49mm)                                                                              |
| watchOS 11.1 | Apple Watch SE (40mm) (2nd generation)<br>Apple Watch SE (44mm) (2nd generation)<br>Apple Watch Series 10 (42mm)<br>Apple Watch Series 10 (46mm)<br>Apple Watch Ultra 2 (49mm)                                                                              |
| visionOS 2.0 | Apple Vision Pro                                                                                                                                                                                                                                            |
| visionOS 2.1 | Apple Vision Pro                                                                                                                                                                                                                                            |

### Android
| Package Name               | Version                                                                                                                                                                                 |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Android Emulator           | 35.2.10                                                                                                                                                                                 |
| Android SDK Platforms      | android-35 (rev 1)<br>android-34-ext8 (rev 1)<br>android-34-ext12 (rev 1)<br>android-34-ext11 (rev 1)<br>android-34-ext10 (rev 1)<br>android-33-ext5 (rev 1)<br>android-33-ext4 (rev 1) |
| Android SDK Platform-Tools | 35.0.2                                                                                                                                                                                  |
| Android Support Repository | 47.0.0                                                                                                                                                                                  |
| CMake                      | 3.22.1                                                                                                                                                                                  |
| Google Play services       | 49                                                                                                                                                                                      |
| Google Repository          | 58                                                                                                                                                                                      |
| NDK                        | 26.3.11579264<br>27.1.12297006 (default)                                                                                                                                                |

#### Environment variables
| Name                    | Value                                               |
| ----------------------- | --------------------------------------------------- |
| ANDROID_HOME            | /Users/runner/Library/Android/sdk                   |
| ANDROID_NDK             | /Users/runner/Library/Android/sdk/ndk/27.1.12297006 |
| ANDROID_NDK_HOME        | /Users/runner/Library/Android/sdk/ndk/27.1.12297006 |
| ANDROID_NDK_LATEST_HOME | /Users/runner/Library/Android/sdk/ndk/27.1.12297006 |
| ANDROID_NDK_ROOT        | /Users/runner/Library/Android/sdk/ndk/27.1.12297006 |
| ANDROID_SDK_ROOT        | /Users/runner/Library/Android/sdk                   |
