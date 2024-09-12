# Inlining optimization
KBUILD_CFLAGS  += -mllvm -inline-instr-cost=1

ccflags-y += -O3

obj-$(CONFIG_LZ4_COMPRESS) += lz4_compress.o
obj-$(CONFIG_LZ4HC_COMPRESS) += lz4hc_compress.o
obj-$(CONFIG_LZ4_DECOMPRESS) += lz4_decompress.o
