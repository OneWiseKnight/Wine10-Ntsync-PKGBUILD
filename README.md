# CachyWine10 Fork with NTsync Staging

### Disclaimer
I am not a programmer, I did not code a single thing, and the only thing I did do was get the patches from the CachyOS Wine Repo and edit a PKGBUILD file.

### What is this?
Cachy Wine version to incorporate NTsync Staging rather than the normal Staging that Cachy provides. All patches, mods, are done by [CachyOS Repo](https://github.com/CachyOS/wine-cachyos) and the only thing I did was change the build order.

### Patches Removed to build this version
**Staging-Ntsync Patch Removals**

Subject: [PATCH 208/244] ntdll: Enable esync and fsync by default.
Subject: [PATCH 117/244] shell32: Add more Tango icons to the IE toolbar
Subject: [PATCH 116/244] shell32: Add toolbar bitmaps compatible with IE6.

Subject: [PATCH 201/244] xactengine3_7/tests: Add Global settings test
Subject: [PATCH 202/244] xactengine3_7: Implement IXACT3Engine
Subject: [PATCH 203/244] xactengine3_7: Implement IXACT3Engine PrepareInMemoryWave
Subject: [PATCH 204/244] xactengine: Implement IXACT3Cue SetOutputVoiceMatrix
Subject: [PATCH 242/244] server, ntdll: Add a do_ntsync helper.
Subject: [PATCH 244/244] wine: Consolidate and clean up startup messaging.

Subject: [PATCH 052/244] fonts: Add Liberation Serif as an Times New Roman
Subject: [PATCH 051/244] fonts: Add Liberation Sans as an Arial replacement.

Other font patches removed because I don't have a single clue at patching things and the normal patching method doesn't do fonts right??

### Special Thanks
- Cachyos Repo and [loathingKernel](https://github.com/loathingKernel) for their soul poured into the Cachy Wine/Proton Project
- the PKGBUILD and two Patches taken from loathingKernel github repo
