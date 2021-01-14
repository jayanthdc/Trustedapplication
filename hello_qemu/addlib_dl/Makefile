CFG_TEE_TA_LOG_LEVEL ?= 4

# The UUID for the Trusted Application
SHLIBNAME = libadd_dl
SHLIBUUID = e00508c9-4144-4be4-bcf2-616014c3e8e8

-include $(TA_DEV_KIT_DIR)/mk/ta_dev_kit.mk

ifeq ($(wildcard $(TA_DEV_KIT_DIR)/mk/ta_dev_kit.mk), )
clean:
	@echo 'Note: $$(TA_DEV_KIT_DIR)/mk/ta_dev_kit.mk not found, cannot clean TA'
	@echo 'Note: TA_DEV_KIT_DIR=$(TA_DEV_KIT_DIR)'
endif
