SampleFortran: SampleFortran.o
	gfortran -o SampleFortran SampleFortran.o
SampleFortran.o: SampleFortran.f90
	gfortran -c -g -ffree-line-length-none SampleFortran.f90
clean:
	rm -f SampleFortran.o SampleFortran.exe