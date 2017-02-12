## Talisker: Architecture-independent resources

## Copyright 2017 Mo McRoberts.
##
##  Licensed under the Apache License, Version 2.0 (the "License");
##  you may not use this file except in compliance with the License.
##  You may obtain a copy of the License at
##
##      http://www.apache.org/licenses/LICENSE-2.0
##
##  Unless required by applicable law or agreed to in writing, software
##  distributed under the License is distributed on an "AS IS" BASIS,
##  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
##  See the License for the specific language governing permissions and
##  limitations under the License.

AC_INIT([Talisker],[develop])

AC_CONFIG_AUX_DIR([BuildScripts])
AC_CONFIG_MACRO_DIR([M4])

TAL_CHECK_DOMAINS

AM_INIT_AUTOMAKE([foreign])
AM_MAINTAINER_MODE

TAL_CONFIG_SUBDIR([Fonts])
TAL_CONFIG_SUBDIR([ColorSchemes])
TAL_CONFIG_SUBDIR([DesktopPictures])
TAL_CONFIG_SUBDIR([UserPictures])
TAL_CONFIG_SUBDIR([UserTemplate])
TAL_CONFIG_SUBDIR([Sounds])
TAL_CONFIG_SUBDIR([Stationery])
TAL_CONFIG_SUBDIR([Icons])

AC_CONFIG_FILES([
Makefile
])

AC_OUTPUT
