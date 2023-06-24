load("@app1_npm//app1:jest/package_json.bzl", jest_bin = "bin")
load("@app1_npm//:defs.bzl", "npm_link_all_packages")

npm_link_all_packages()

jest_bin.jest_binary(
    name = "help",
    args = ["--help"],
    chdir = package_name(),
)