This patch made to compile FFmpeg with NNENC support

Run configure FFmpeg as shown below:
 ./configure --libdir=/usr/lib64 --enable-cuda-nvcc --enable-cuvid --enable-nvdec --enable-nvenc --enable-nonfree --enable-libnpp --extra-cflags=-I/usr/local/cuda/include --extra-ldflags=-L/usr/local/cuda/lib64 --nvccflags='--include-path=/usr/local/cuda/include' --nvcc=/usr/local/cuda/bin/nvcc --enable-libnpp-static
