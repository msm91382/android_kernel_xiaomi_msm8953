ifdef CONFIG_X86
ccflags-y += -DIPA_EMULATION_COMPILE=1
else
ccflags-y += -DIPA_EMULATION_COMPILE=0
endif

obj-$(CONFIG_IPA_UT) += ipa_ut_mod.o
ipa_ut_mod-y := ipa_ut_framework.o ipa_test_example.o ipa_test_mhi.o ipa_test_dma.o ipa_test_hw_stats.o ipa_pm_ut.o
