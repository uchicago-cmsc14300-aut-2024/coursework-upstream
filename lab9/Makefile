.PHONY: clean

seq: lab9.h lab9.c grayseq.c
	clang -Wall -o grayseq lab9.c grayseq.c -pthread

par: lab9.h lab9.c graypar.c
	clang -Wall -o graypar lab9.c graypar.c -pthread

clean:
	rm -rf a.out grayseq graypar

