scala_library(
    sources = ["*.scala"],
    compiler_option_sets = ["fatal_warnings"],
    strict_deps = True,
    tags = ["bazel-compatible"],
    dependencies = [
        "cortex-core/thrift/src/main/thrift:thrift-scala",
        "cortex-tweet-annotate/service/src/main/thrift:thrift-scala",
        "finagle/finagle-memcached/src/main/scala",
        "mediaservices/commons/src/main/thrift:thrift-scala",
        "servo/repo",
        "servo/util/src/main/scala",
        "src/thrift/com/twitter/ml/api:data-scala",
        "src/thrift/com/twitter/ml/prediction_service:prediction_service-scala",
        "timelines/src/main/scala/com/twitter/timelines/model/types",
        "timelines/src/main/scala/com/twitter/timelines/util",
        "timelines/src/main/scala/com/twitter/timelines/util/stats",
        "util/util-core:util-core-util",
        "util/util-logging/src/main/scala",
        "util/util-stats/src/main/scala",
    ],
)
