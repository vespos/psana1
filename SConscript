#--------------------------------------------------------------------------
# File and Version Information:
#  $Id$
#
# Description:
#  SConscript file for package psana
#------------------------------------------------------------------------

# Do not delete following line, it must be present in 
# SConscript file for any SIT project
Import('*')

#
# For the standard SIT packages which build libraries, applications,
# and Python modules it is usually sufficient to call
# standardSConscript() function which defines rules for all
# above targets. Many standard packages do not need any special options, 
# but those which need can modify standardSConscript() behavior using
# a number of arguments, here is a complete list:
#
# LIBS - list of additional libraries needed by this package
# BINS - dictionary of executables and their corresponding source files
# TESTS - dictionary of test applications and their corresponding source files
# SCRIPTS - list of scripts in app/ directory
# UTESTS - names of the unit tests to run, if not given then all tests are unit tests
# PYEXTMOD - name of the Python extension module, package name used by default
#
#
LIBS="dl"
DOCGEN = {'psana-doxy': 'psana psana/doc/mainpage.dox-main',
          'doxy-all': 'psana'}
CCFLAGS="-std=c++98 -fabi-version=2"
standardSConscript(**locals())
