load("@rules_python//python:defs.bzl", "py_binary")
load("@my_deps//:requirements.bzl", "requirement")
 
py_binary(
  name = "main",
  srcs = ["main.py"],
  deps = [requirement("Flask"),"//calculator:calculator"]
) 



# py_binary(
#   name = "main",
#   srcs = ["main.py"],
# )