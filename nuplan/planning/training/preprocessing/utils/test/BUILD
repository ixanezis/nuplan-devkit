load("@rules_python//python:defs.bzl", "py_test")

package(default_visibility = ["//visibility:public"])

py_test(
    name = "test_agent_processing",
    size = "small",
    srcs = ["test_agent_processing.py"],
    deps = [
        "//nuplan/common/actor_state:ego_state",
        "//nuplan/common/actor_state:state_representation",
        "//nuplan/database/utils/boxes:box3d",
        "//nuplan/planning/training/preprocessing/utils:agents_preprocessing",
    ],
)

py_test(
    name = "test_torch_math",
    size = "small",
    srcs = ["test_torch_math.py"],
    deps = [
        "//nuplan/planning/training/preprocessing/utils:torch_math",
    ],
)

py_test(
    name = "test_torch_geometry",
    size = "small",
    srcs = ["test_torch_geometry.py"],
    deps = [
        "//nuplan/planning/training/preprocessing/utils:torch_geometry",
    ],
)

py_test(
    name = "test_vector_preprocessing",
    size = "small",
    srcs = ["test_vector_preprocessing.py"],
    deps = [
        "//nuplan/common/maps:maps_datatypes",
        "//nuplan/planning/training/preprocessing/feature_builders:vector_builder_utils",
        "//nuplan/planning/training/preprocessing/utils:vector_preprocessing",
    ],
)
