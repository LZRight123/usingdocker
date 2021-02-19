

var:
	echo $($@) \
	&& echo $($<) \
	&& echo $($^)

target1:
	echo "hello wolrd" \
	&& echo "two" \
	&& echo "3" \
	&& touch test.txt


main:
	echo "hello main" \
	&& touch main.txt

all:target1 main
	

cleanTest:
	rm test.txt

cleanMain:
	rm main.txt

clean: cleanTest cleanMain

