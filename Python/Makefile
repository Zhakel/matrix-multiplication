#ALGORITHM = ijkMultiplication
#ALGORITHM = ikjMultiplication
#ALGORITHM = library-numpy
#ALGORITHM = library-scipy
ALGORITHM = psyco-ikj-multiplication

TESTSET = 2000

test:
	time -f "%U" ./$(ALGORITHM).py -i ../Testing/$(TESTSET).in > result.txt
	diff ../Testing/$(TESTSET).out result.txt
