licenses(["notice"])  # Apache 2

android_library(
    name = "envoy_engine_lib",
    srcs = [
        "AndroidEngineImpl.java",
        "AndroidJniLibrary.java",
        "AndroidNetworkMonitor.java",
    ],
    custom_package = "io.envoyproxy.envoymobile.engine",
    manifest = "AndroidEngineManifest.xml",
    visibility = ["//visibility:public"],
    deps = [
        "//library/java/src/io/envoyproxy/envoymobile/engine:envoy_base_engine_lib",
        "//library/java/src/io/envoyproxy/envoymobile/engine/types:envoy_c_types_lib",
    ],
)

java_library(
    name = "envoy_base_engine_lib",
    srcs = [
        "EnvoyConfiguration.java",
        "EnvoyEngine.java",
        "EnvoyEngineImpl.java",
        "EnvoyHTTPStream.java",
        "JniLibrary.java",
        "JvmCallbackContext.java",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "//library/java/src/io/envoyproxy/envoymobile/engine/types:envoy_c_types_lib",
    ],
)
