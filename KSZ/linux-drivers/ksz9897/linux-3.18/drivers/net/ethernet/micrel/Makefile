#
# Makefile for the Microchip/Micrel network device drivers.
#

obj-$(CONFIG_I2C_KSZ9897) += i2c-ksz9897.o
obj-$(CONFIG_SPI_KSZ9897) += spi-ksz9897.o

SRC := $(shell pwd)

all:
	$(MAKE) -C $(KERNEL_SRC) M=$(SRC) modules
modules_install:
	$(MAKE) -C $(KERNEL_SRC) M=$(SRC) modules_install


