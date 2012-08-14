#
# Makefile for the Cypress touchkey driver
#
ifeq ($(CONFIG_TARGET_LOCALE_NA),y)
obj-$(CONFIG_KEYBOARD_CYPRESS_TOUCH) += cypress-touchkey-spr.o issp_driver_routines-spr.o issp_main-spr.o issp_routines.o
else
obj-$(CONFIG_KEYBOARD_CYPRESS_TOUCH) += cypress-touchkey.o issp_driver_routines.o issp_main.o issp_routines.o
endif