# mFSTRIM
A real, non-root fstrim utility for Android

# How does it work?
Android has a built-in [mechanism](https://cs.android.com/android/platform/superproject/+/master:frameworks/base/services/core/java/com/android/server/pm/PackageManagerService.java;l=9636?q=fstrim_mandatory_interval&ss=android%2Fplatform%2Fsuperproject) of forcing an fstrim if it has been unable to within a certain interval. We can actually tune this interval to be anything we desire.
