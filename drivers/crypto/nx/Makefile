obj-$(CONFIG_CRYPTO_DEV_NX_ENCRYPT) += nx-crypto.o
nx-crypto-objs := nx.o \
		  nx-aes-cbc.o \
		  nx-aes-ecb.o \
		  nx-aes-gcm.o \
		  nx-aes-ccm.o \
		  nx-aes-ctr.o \
		  nx-aes-xcbc.o \
		  nx-sha256.o \
		  nx-sha512.o

nx-crypto-$(CONFIG_DEBUG_FS) += nx_debugfs.o
obj-$(CONFIG_CRYPTO_DEV_NX_COMPRESS_PSERIES) += nx-compress-pseries.o nx-compress.o
obj-$(CONFIG_CRYPTO_DEV_NX_COMPRESS_POWERNV) += nx-compress-powernv.o nx-compress.o
nx-compress-objs := nx-842.o
nx-compress-pseries-objs := nx-842-pseries.o
nx-compress-powernv-objs := nx-842-powernv.o
