# SPDX-License-Identifier: GPL-3.0-only
# MuseScore-CLA-applies
#
# MuseScore
# Music Composition & Notation
#
# Copyright (C) 2021 MuseScore BVBA and others
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License version 3 as
# published by the Free Software Foundation.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <https://www.gnu.org/licenses/>.

declare_module(muse_network)
set(MODULE_ALIAS muse::network)

set(MODULE_SRC
    ${CMAKE_CURRENT_LIST_DIR}/networkstubmodule.cpp
    ${CMAKE_CURRENT_LIST_DIR}/networkstubmodule.h
    ${CMAKE_CURRENT_LIST_DIR}/networkmanagercreatorstub.cpp
    ${CMAKE_CURRENT_LIST_DIR}/networkmanagercreatorstub.h
    ${CMAKE_CURRENT_LIST_DIR}/networkmanagerstub.cpp
    ${CMAKE_CURRENT_LIST_DIR}/networkmanagerstub.h
    ${CMAKE_CURRENT_LIST_DIR}/networkconfigurationstub.cpp
    ${CMAKE_CURRENT_LIST_DIR}/networkconfigurationstub.h
    )

set(MODULE_IS_STUB ON)
setup_module()
