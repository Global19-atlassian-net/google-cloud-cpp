# Copyright 2018 Google LLC
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

package(default_visibility = ["//visibility:public"])

licenses(["notice"])  # Apache 2.0

exports_files([
    "LICENSE",
])

cc_library(
    name = "bigtable_client",
    deps = [
        "//google/cloud/bigtable:bigtable_client",
    ],
)

cc_library(
    name = "pubsub_client",
    deps = [
        "//google/cloud/pubsub:pubsub_client",
    ],
)

cc_library(
    name = "spanner_client",
    deps = [
        "//google/cloud/spanner:spanner_client",
    ],
)

cc_library(
    name = "storage_client",
    deps = [
        "//google/cloud/storage:storage_client",
    ],
)
