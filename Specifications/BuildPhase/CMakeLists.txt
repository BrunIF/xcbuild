#
# Copyright (c) 2015-present, Facebook, Inc.
# All rights reserved.
#
# This source code is licensed under the BSD-style license found in the
# LICENSE file in the root directory of this source tree.
#

install(FILES
        com.apple.buildphase.applescript.xcspec
        com.apple.buildphase.copy-files.xcspec
        com.apple.buildphase.frameworks.xcspec
        com.apple.buildphase.headers.xcspec
        com.apple.buildphase.java-archive.xcspec
        com.apple.buildphase.resources.xcspec
        com.apple.buildphase.rez.xcspec
        com.apple.buildphase.shell-script.xcspec
        com.apple.buildphase.sources.xcspec
        DESTINATION Library/Xcode/Specifications)
