load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "map_manager",
    srcs = ["map_manager.cc"],
    hdrs = ["map_manager.h"],
    deps = [
        "//cyber",
        "//modules/common/math",
        "//modules/map/hdmap",
        "//modules/map/proto:map_proto",
        "//modules/perception/base:base_type",
        "//modules/perception/lib/config_manager",
        "//modules/perception/lidar/common:lidar_frame",
        "//modules/perception/map/hdmap:hdmap_input",
        "//modules/perception/proto:map_manager_config_proto",
    ],
)

#cc_test(
#    name = "map_manager_test",
#    srcs = ["map_manager_test.cc"],
#    deps = [
#        ":map_manager",
#        "@com_google_googletest//:gtest_main",
#    ],
#)

cpplint()
