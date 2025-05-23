# $OpenBSD: Makefile,v 1.19 2024/06/02 15:40:42 deraadt Exp $

LIB=	LLVMX86CodeGen
NOPROFILE=

CPPFLAGS+=	-I${.OBJDIR}/../include/llvm/X86 -I${LLVM_SRCS}/lib/Target/X86

SRCS+=	X86AsmPrinter.cpp \
	X86AvoidTrailingCall.cpp \
	X86CallFrameOptimization.cpp \
	X86CallingConv.cpp \
	X86CallLowering.cpp \
	X86CmovConversion.cpp \
	X86DomainReassignment.cpp \
	X86DiscriminateMemOps.cpp \
	X86LowerTileCopy.cpp \
	X86LowerAMXType.cpp \
	X86PreAMXConfig.cpp \
	X86LowerAMXIntrinsics.cpp \
	X86TileConfig.cpp \
	X86FastPreTileConfig.cpp \
	X86FastTileConfig.cpp \
	X86PreTileConfig.cpp \
	X86ExpandPseudo.cpp \
	X86FastISel.cpp \
	X86FixupBWInsts.cpp \
	X86FixupGadgets.cpp \
	X86RetClean.cpp \
	X86FixupLEAs.cpp \
	X86AvoidStoreForwardingBlocks.cpp \
	X86DynAllocaExpander.cpp \
	X86FixupSetCC.cpp \
	X86FlagsCopyLowering.cpp \
	X86FloatingPoint.cpp \
	X86FrameLowering.cpp \
	X86InstructionSelector.cpp \
	X86ISelDAGToDAG.cpp \
	X86ISelLowering.cpp \
	X86IndirectBranchTracking.cpp \
	X86IndirectThunks.cpp \
	X86InterleavedAccess.cpp \
	X86InsertPrefetch.cpp \
	X86InstCombineIntrinsic.cpp \
	X86InstrFMA3Info.cpp \
	X86InstrFoldTables.cpp \
	X86InstrInfo.cpp \
	X86EvexToVex.cpp \
	X86KCFI.cpp \
	X86LegalizerInfo.cpp \
	X86LoadValueInjectionLoadHardening.cpp \
	X86LoadValueInjectionRetHardening.cpp \
	X86MCInstLower.cpp \
	X86MachineFunctionInfo.cpp \
	X86MacroFusion.cpp \
	X86OptimizeLEAs.cpp \
	X86PadShortFunction.cpp \
	X86PartialReduction.cpp \
	X86RegisterBankInfo.cpp \
	X86RegisterInfo.cpp \
	X86ReturnProtectorLowering.cpp \
	X86ReturnThunks.cpp \
	X86SelectionDAGInfo.cpp \
	X86ShuffleDecodeConstantPool.cpp \
	X86SpeculativeLoadHardening.cpp \
	X86SpeculativeExecutionSideEffectSuppression.cpp \
	X86Subtarget.cpp \
	X86TargetMachine.cpp \
	X86TargetObjectFile.cpp \
	X86TargetTransformInfo.cpp \
	X86VZeroUpper.cpp \
	X86WinEHState.cpp \
	X86InsertWait.cpp

.PATH:	${.CURDIR}/../../../llvm/llvm/lib/Target/X86
