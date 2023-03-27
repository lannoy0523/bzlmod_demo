load("@rules_java//java:defs.bzl", "java_binary", "java_library", "java_runtime", "java_test")

package(default_visibility = ["//visibility:public"])

java_binary(
    name = "bazel_maven_test",
    srcs = glob([
        "src/main/java/**/*.java",
    ]),
    resources = glob([
        "src/main/resources/**",
    ]),
    main_class = "com.example.test",
    deps = [
        "@maven//:com_example_maven",
    ],
)
