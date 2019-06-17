---
title: Dialogs RTL
description: Use native dialog UI elements, Content will be RTL direction, and the dialog created without title area. This plugin is based on (https://github.com/apache/cordova-plugin-dialogs)
---
<!--
# license: Licensed to the Apache Software Foundation (ASF) under one
#         or more contributor license agreements.  See the NOTICE file
#         distributed with this work for additional information
#         regarding copyright ownership.  The ASF licenses this file
#         to you under the Apache License, Version 2.0 (the
#         "License"); you may not use this file except in compliance
#         with the License.  You may obtain a copy of the License at
#
#           http://www.apache.org/licenses/LICENSE-2.0
#
#         Unless required by applicable law or agreed to in writing,
#         software distributed under the License is distributed on an
#         "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
#         KIND, either express or implied.  See the License for the
#         specific language governing permissions and limitations
#         under the License.
-->

# cordova-plugin-dialogs

This plugin provides access to some native dialog UI elements
via a global `navigator.notification` object.

Although the object is attached to the global scoped `navigator`, it is not available until after the `deviceready` event.

    document.addEventListener("deviceready", onDeviceReady, false);
    function onDeviceReady() {
        console.log(navigator.notification);
    }

## Installation

    cordova plugin add https://github.com/ahmedelrefaiy/Cordova-RTL-Dialog

## Plugin Features

- Start reading the plugin features from the [original plugin](https://github.com/apache/cordova-plugin-dialogs#methods) as it is the same.
- For `Title` parameter leave it with empty character like this ' '.
