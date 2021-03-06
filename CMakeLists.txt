cmake_minimum_required(VERSION 3.12)
project(htk)

set(CMAKE_CXX_STANDARD 14)

include_directories(./HTKLib)

add_executable(HTK
        HLMLib/LCMap.c
        HLMLib/LCMap.h
        HLMLib/LGBase.c
        HLMLib/LGBase.h
        HLMLib/LModel.c
        HLMLib/LModel.h
        HLMLib/LPCalc.c
        HLMLib/LPCalc.h
        HLMLib/LPMerge.c
        HLMLib/LPMerge.h
        HLMLib/LUtil.c
        HLMLib/LUtil.h
        HLMLib/LWMap.c
        HLMLib/LWMap.h
        HLMTools/Cluster.c
        HLMTools/HLMCopy.c
        HLMTools/LAdapt.c
        HLMTools/LBuild.c
        HLMTools/LFoF.c
        HLMTools/LGCopy.c
        HLMTools/LGList.c
        HLMTools/LGPrep.c
        HLMTools/LLink.c
        HLMTools/LMerge.c
        HLMTools/LNewMap.c
        HLMTools/LNorm.c
        HLMTools/LPlex.c
        HLMTools/LSubset.c
        HTKLib/esig_asc.c
        HTKLib/esig_edr.c
        HTKLib/esig_nat.c
        HTKLib/esignal.c
        HTKLib/esignal.h
        HTKLib/HAdapt.c
        HTKLib/HAdapt.h
        HTKLib/HArc.c
        HTKLib/HArc.h
        HTKLib/HAudio.c
        HTKLib/HAudio.h
        HTKLib/HDict.c
        HTKLib/HDict.h
        HTKLib/HExactMPE.c
        HTKLib/HExactMPE.h
        HTKLib/HFB.c
        HTKLib/HFB.h
        HTKLib/HFBLat.c
        HTKLib/HFBLat.h
        HTKLib/HGraf.c
        HTKLib/HGraf.h
        HTKLib/HGraf.null.c
        HTKLib/HGraf_WIN32.c
        HTKLib/HLabel.c
        HTKLib/HLabel.h
        HTKLib/HLat.c
        HTKLib/HLat.h
        HTKLib/HLM.c
        HTKLib/HLM.h
        HTKLib/HMap.c
        HTKLib/HMap.h
        HTKLib/HMath.c
        HTKLib/HMath.h
        HTKLib/HMem.c
        HTKLib/HMem.h
        HTKLib/HModel.c
        HTKLib/HModel.h
        HTKLib/HNet.c
        HTKLib/HNet.h
        HTKLib/HParm.c
        HTKLib/HParm.h
        HTKLib/HRec.c
        HTKLib/HRec.h
        HTKLib/HShell.c
        HTKLib/HShell.h
        HTKLib/HSigP.c
        HTKLib/HSigP.h
        HTKLib/HTrain.c
        HTKLib/HTrain.h
        HTKLib/HUtil.c
        HTKLib/HUtil.h
        HTKLib/HVQ.c
        HTKLib/HVQ.h
        HTKLib/HWave.c
        HTKLib/HWave.h
        HTKLib/strarr.c
        HTKLib/strarr.h
        HTKLVRec/config.h
        HTKLVRec/HDecode.c
        HTKLVRec/HDecode.mod.c
        HTKLVRec/HLVLM.c
        HTKLVRec/HLVLM.h
        HTKLVRec/HLVModel.c
        HTKLVRec/HLVModel.h
        HTKLVRec/HLVNet.c
        HTKLVRec/HLVNet.h
        HTKLVRec/HLVRec-GC.c
        HTKLVRec/HLVRec-LM.c
        HTKLVRec/HLVRec-misc.c
        HTKLVRec/HLVRec-outP.c
        HTKLVRec/HLVRec-propagate.c
        HTKLVRec/HLVRec-traceback.c
        HTKLVRec/HLVRec.c
        HTKLVRec/HLVRec.h
        HTKLVRec/Makefile.icc
        HTKTools/HBuild.c
        HTKTools/HCompV.c
        HTKTools/HCopy.c
        HTKTools/HDMan.c
        HTKTools/HERest.c
        HTKTools/HHEd.c
        HTKTools/HInit.c
        HTKTools/HLEd.c
        HTKTools/HList.c
        HTKTools/HLRescore.c
        HTKTools/HLStats.c
        HTKTools/HMMIRest.c
        HTKTools/HParse.c
        HTKTools/HQuant.c
        HTKTools/HRest.c
        HTKTools/HResults.c
        HTKTools/HSGen.c
        HTKTools/HSLab.c
        HTKTools/HSmooth.c
        HTKTools/HVite.c)
