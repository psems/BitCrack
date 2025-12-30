CPPSRC:=$(wildcard *.cpp)

all:
	${CXX} -o addrgen.exe ${CPPSRC} ${INCLUDE} -I${CUDA_INCLUDE} ${CXXFLAGS} ${LIBS} -laddressutil -lsecp256k1 -lcryptoutil -lsecp256k1 -lutil -lcmdparse -lbcrypt
	mkdir -p $(BINDIR)
	cp addrgen.exe $(BINDIR)/addrgen.exe


clean:
	rm -rf addrgen.bin
