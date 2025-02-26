#==============================================================
#
#  Abs:  Makefile to build library
#
#  Name: Makefile
#
#  Auth: 10-Nov-2010, K. Luchini     (LUCHINI)
#  Rev:  dd-mmm-yyyy, First Lastname (USERNAME)
#
#--------------------------------------------------------------
#  Mod:
#       10-Nov-2010, K. Luchini      (LUCHINI):
#         copied from event to a separate module
#         Record support written by Bob Dalesio and maintained
#         by Marty Kraimer. Stephanie allison renamed the
#         original device support recSub.c to longSubRecord.c
#         added fields M to Z, and changed double to unsigned long.
#
#=============================================================
#
TOP=..
include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE
#========================================
#
# build a library
#
# USR_CFLAGS += 
DBDINC     += longSubRecord
DBD        += longSubRecord.dbd

# Link everything into a library:
LIBRARY_IOC = longSubRecord

# Source files
longSubRecord_SRCS += longSubRecord.c
SRCLIBS += $(EPICS_BASE_IOC_LIBS)

#=======================================
include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE
#
# End of file



