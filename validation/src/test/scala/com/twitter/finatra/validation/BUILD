scala_library(
    sources = globs(
        "*.scala",
    ),
    compiler_option_sets = {"fatal_warnings"},
    provides = scala_artifact(
        org = "com.twitter",
        name = "finatra-validation-tests",
        repo = artifactory,
    ),
    strict_deps = True,
    dependencies = [
        "//:scalap",
        "3rdparty/jvm/org/json4s:json4s-core",
        "finatra/inject/inject-core/src/test/scala:test-deps",
        "finatra/inject/inject-slf4j/src/main/scala",
        "finatra/inject/inject-utils/src/main/scala",
        "finatra/validation/src/main/scala/com/twitter/finatra/validation",
    ],
    exports = [
        "finatra/inject/inject-core/src/test/scala:test-deps",
        "finatra/validation/src/main/scala/com/twitter/finatra/validation",
    ],
)
