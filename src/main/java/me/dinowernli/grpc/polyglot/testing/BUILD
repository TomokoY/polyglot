package(default_visibility = ["//visibility:public"])

java_library(
  name = "testing",
  srcs = glob(['*.java']),
  testonly = 1,
  deps = [
    "//src/main/java/me/dinowernli/grpc/polyglot/io",
    "//src/main/proto/testing:test_service_proto_grpc",
    "//third_party/grpc",
    "//third_party/guava",
    "//third_party/logging:logging-api",
    "//third_party/netty",
    "//third_party/protobuf",
  ],
  data = glob(["test-certificates/*"]),
)
