load("@build_bazel_rules_swift//swift:swift.bzl", "swift_library")

swift_library(
    name = "TelegramAnimatedStickerNode",
    module_name = "TelegramAnimatedStickerNode",
    srcs = glob([
        "Sources/**/*.swift",
    ]),
    deps = [
    	"//submodules/Postbox:Postbox",
        "//submodules/TelegramCore:TelegramCore",
        "//submodules/StickerResources:StickerResources",
        "//submodules/MediaResources:MediaResources",
        "//submodules/LocalMediaResources:LocalMediaResources",
        "//submodules/Tuples:Tuples",
        "//submodules/AnimatedStickerNode:AnimatedStickerNode",
        "//submodules/rlottie:RLottieBinding",
        "//submodules/YuvConversion:YuvConversion",
        "//submodules/GZip:GZip",
    ],
    visibility = [
        "//visibility:public",
    ],
)
