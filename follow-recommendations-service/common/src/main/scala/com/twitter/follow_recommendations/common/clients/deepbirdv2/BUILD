scala_library(
    sources = ["*.scala"],
    compiler_option_sets = ["fatal_warnings"],
    platform = "java8",
    tags = ["bazel-compatible"],
    dependencies = [
        "3rdparty/jvm/com/google/inject:guice",
        "3rdparty/jvm/com/google/inject/extensions:guice-assistedinject",
        "3rdparty/jvm/net/codingwell:scala-guice",
        "3rdparty/jvm/org/slf4j:slf4j-api",
        "cortex-deepbird/prediction/src/main/scala/com/twitter/cortex/deepbird/prediction",
        "cortex-deepbird/thrift/src/main/thrift:thrift-java",
        "finatra-internal/mtls-thriftmux/src/main/scala",
        "finatra/inject/inject-core/src/main/scala",
        "finatra/inject/inject-thrift-client/src/main/scala",
        "follow-recommendations-service/common/src/main/scala/com/twitter/follow_recommendations/common/clients/common",
        "src/scala/com/twitter/ml/api/util",
        "util/util-core:scala",
    ],
)
