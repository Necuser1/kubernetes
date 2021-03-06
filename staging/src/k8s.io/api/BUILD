load("@io_bazel_rules_go//go:def.bzl", "go_test")

go_test(
    name = "go_default_test",
    srcs = ["roundtrip_test.go"],
    data = glob(["testdata/**"]),
    deps = [
        "//staging/src/k8s.io/api/admission/v1:go_default_library",
        "//staging/src/k8s.io/api/admission/v1beta1:go_default_library",
        "//staging/src/k8s.io/api/admissionregistration/v1:go_default_library",
        "//staging/src/k8s.io/api/admissionregistration/v1beta1:go_default_library",
        "//staging/src/k8s.io/api/apps/v1:go_default_library",
        "//staging/src/k8s.io/api/apps/v1beta1:go_default_library",
        "//staging/src/k8s.io/api/apps/v1beta2:go_default_library",
        "//staging/src/k8s.io/api/authentication/v1:go_default_library",
        "//staging/src/k8s.io/api/authentication/v1beta1:go_default_library",
        "//staging/src/k8s.io/api/authorization/v1:go_default_library",
        "//staging/src/k8s.io/api/authorization/v1beta1:go_default_library",
        "//staging/src/k8s.io/api/autoscaling/v1:go_default_library",
        "//staging/src/k8s.io/api/autoscaling/v2beta1:go_default_library",
        "//staging/src/k8s.io/api/autoscaling/v2beta2:go_default_library",
        "//staging/src/k8s.io/api/batch/v1:go_default_library",
        "//staging/src/k8s.io/api/batch/v1beta1:go_default_library",
        "//staging/src/k8s.io/api/batch/v2alpha1:go_default_library",
        "//staging/src/k8s.io/api/certificates/v1beta1:go_default_library",
        "//staging/src/k8s.io/api/coordination/v1:go_default_library",
        "//staging/src/k8s.io/api/coordination/v1beta1:go_default_library",
        "//staging/src/k8s.io/api/core/v1:go_default_library",
        "//staging/src/k8s.io/api/events/v1beta1:go_default_library",
        "//staging/src/k8s.io/api/extensions/v1beta1:go_default_library",
        "//staging/src/k8s.io/api/imagepolicy/v1alpha1:go_default_library",
        "//staging/src/k8s.io/api/networking/v1:go_default_library",
        "//staging/src/k8s.io/api/networking/v1beta1:go_default_library",
        "//staging/src/k8s.io/api/node/v1alpha1:go_default_library",
        "//staging/src/k8s.io/api/node/v1beta1:go_default_library",
        "//staging/src/k8s.io/api/policy/v1beta1:go_default_library",
        "//staging/src/k8s.io/api/rbac/v1:go_default_library",
        "//staging/src/k8s.io/api/rbac/v1alpha1:go_default_library",
        "//staging/src/k8s.io/api/rbac/v1beta1:go_default_library",
        "//staging/src/k8s.io/api/scheduling/v1:go_default_library",
        "//staging/src/k8s.io/api/scheduling/v1alpha1:go_default_library",
        "//staging/src/k8s.io/api/scheduling/v1beta1:go_default_library",
        "//staging/src/k8s.io/api/settings/v1alpha1:go_default_library",
        "//staging/src/k8s.io/api/storage/v1:go_default_library",
        "//staging/src/k8s.io/api/storage/v1alpha1:go_default_library",
        "//staging/src/k8s.io/api/storage/v1beta1:go_default_library",
        "//staging/src/k8s.io/apimachinery/pkg/api/apitesting/fuzzer:go_default_library",
        "//staging/src/k8s.io/apimachinery/pkg/api/apitesting/roundtrip:go_default_library",
        "//staging/src/k8s.io/apimachinery/pkg/apis/meta/fuzzer:go_default_library",
        "//staging/src/k8s.io/apimachinery/pkg/runtime:go_default_library",
        "//staging/src/k8s.io/apimachinery/pkg/runtime/serializer:go_default_library",
        "//vendor/github.com/stretchr/testify/require:go_default_library",
    ],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [
        ":package-srcs",
        "//staging/src/k8s.io/api/admission/v1:all-srcs",
        "//staging/src/k8s.io/api/admission/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/admissionregistration/v1:all-srcs",
        "//staging/src/k8s.io/api/admissionregistration/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/apps/v1:all-srcs",
        "//staging/src/k8s.io/api/apps/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/apps/v1beta2:all-srcs",
        "//staging/src/k8s.io/api/auditregistration/v1alpha1:all-srcs",
        "//staging/src/k8s.io/api/authentication/v1:all-srcs",
        "//staging/src/k8s.io/api/authentication/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/authorization/v1:all-srcs",
        "//staging/src/k8s.io/api/authorization/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/autoscaling/v1:all-srcs",
        "//staging/src/k8s.io/api/autoscaling/v2beta1:all-srcs",
        "//staging/src/k8s.io/api/autoscaling/v2beta2:all-srcs",
        "//staging/src/k8s.io/api/batch/v1:all-srcs",
        "//staging/src/k8s.io/api/batch/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/batch/v2alpha1:all-srcs",
        "//staging/src/k8s.io/api/certificates/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/coordination/v1:all-srcs",
        "//staging/src/k8s.io/api/coordination/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/core/v1:all-srcs",
        "//staging/src/k8s.io/api/discovery/v1alpha1:all-srcs",
        "//staging/src/k8s.io/api/discovery/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/events/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/extensions/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/flowcontrol/v1alpha1:all-srcs",
        "//staging/src/k8s.io/api/imagepolicy/v1alpha1:all-srcs",
        "//staging/src/k8s.io/api/networking/v1:all-srcs",
        "//staging/src/k8s.io/api/networking/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/node/v1alpha1:all-srcs",
        "//staging/src/k8s.io/api/node/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/policy/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/rbac/v1:all-srcs",
        "//staging/src/k8s.io/api/rbac/v1alpha1:all-srcs",
        "//staging/src/k8s.io/api/rbac/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/scheduling/v1:all-srcs",
        "//staging/src/k8s.io/api/scheduling/v1alpha1:all-srcs",
        "//staging/src/k8s.io/api/scheduling/v1beta1:all-srcs",
        "//staging/src/k8s.io/api/settings/v1alpha1:all-srcs",
        "//staging/src/k8s.io/api/storage/v1:all-srcs",
        "//staging/src/k8s.io/api/storage/v1alpha1:all-srcs",
        "//staging/src/k8s.io/api/storage/v1beta1:all-srcs",
    ],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
