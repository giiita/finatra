scala_library(
    sources = globs("*.scala"),
    compiler_option_sets = {"fatal_warnings"},
    provides = scala_artifact(
        org = "com.twitter",
        name = "finatra-http-fileupload",
        repo = artifactory,
    ),
    strict_deps = "True",
    dependencies = [
        "3rdparty/jvm/commons-fileupload",
        "finagle/finagle-base-http/src/main/scala",
    ],
    exports = [
        "3rdparty/jvm/commons-fileupload",
        "finagle/finagle-base-http/src/main/scala",
    ],
)
