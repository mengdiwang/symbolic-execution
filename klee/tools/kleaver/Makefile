#===-- tools/kleaver/Makefile ------------------------------*- Makefile -*--===#
#
#                     The KLEE Symbolic Virtual Machine
#
# This file is distributed under the University of Illinois Open Source
# License. See LICENSE.TXT for details.
#
#===------------------------------------------------------------------------===#

LEVEL=../..
TOOLNAME = kleaver
# FIXME: Ideally we wouldn't have any LLVM dependencies here, which
# means kicking out klee's Support.
USEDLIBS = kleaverSolver.a kleaverExpr.a kleeSupport.a kleeBasic.a
LINK_COMPONENTS = support

include $(LEVEL)/Makefile.common

LIBS += -lstp
