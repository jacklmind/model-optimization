licenses(["notice"])

py_binary(
    name = "mnist_cnn",
    srcs = [
        "mnist_cnn.py",
    ],
    python_version = "PY3",
    deps = [
        # absl:app dep1,
        # numpy dep1,
        # tensorflow dep1,
        "//tensorflow_model_optimization/python/core/quantization/keras:quantize",
        "//tensorflow_model_optimization/python/core/quantization/keras/collaborative_optimizations/prune_preserve:default_8bit_prune_preserve_quantize_scheme",
        "//tensorflow_model_optimization/python/core/sparsity/keras",
    ],
)
