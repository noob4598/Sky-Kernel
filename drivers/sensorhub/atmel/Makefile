#
# Makefile for the sensor drivers.
#

# Each configuration option enables a list of files.
obj-$(CONFIG_SENSORS_SSP)		+= ssp_dev.o ssp_spi.o ssp_data.o ssp_sysfs.o\
						ssp_input.o ssp_firmware.o ssp_debug.o
obj-$(CONFIG_SENSORS_SYSFS)		+= sensors_core.o
obj-$(CONFIG_IIO)			+= ssp_iio_ring.o ssp_iio_trigger.o
obj-$(CONFIG_SENSORS_SSP_SENSORHUB)	+= ssp_sensorhub.o ssp_misc.o

obj-$(CONFIG_SENSORS_SSP_FACTORY)	+= factory/

obj-$(CONFIG_SENSORS_MAX86900) += max86900.o
obj-$(CONFIG_SENSORS_MAX86902) += max86902.o
obj-$(CONFIG_SENSORS_ADPD142)  += adpd142.o
obj-$(CONFIG_SENSORS_MAX_NOTCHFILTER)	+= max_notchfilter/
obj-$(CONFIG_SENSORS_SX9306)   +=sx9306.o
