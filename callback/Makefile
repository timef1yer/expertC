CC=clang 
CFLAGS=
LIBS=

project=callback

all: ${project} test

test: 
	@echo "Test ${project}:"
	./${project}

${project}: ${project}.c
	${CC} ${CFLAGS} ${LIBS} -o ${project} ${project}.c

.PHONY:clean

clean:
	rm -rf ${project}
