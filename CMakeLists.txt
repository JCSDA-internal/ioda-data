# (C) Copyright 2017-2022 UCAR.
#
# This software is licensed under the terms of the Apache Licence Version 2.0
# which can be obtained at http://www.apache.org/licenses/LICENSE-2.0.

################################################################################
# IODA Test Files
################################################################################

cmake_minimum_required( VERSION 3.3.2 FATAL_ERROR )

project( ioda-data VERSION 2.7.0 DESCRIPTION "IODA Test Files" )

ecbuild_install_project( NAME ${PROJECT_NAME} )
ecbuild_print_summary()
