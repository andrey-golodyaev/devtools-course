all:
	mkdir -p ./build
	$(CXX) -o ./build/complexcalc ./library/src/complexcalc.cpp ./samples/ComplexCalculator.cpp ./library/src/complexcalc_application.cpp -I./include 

test: all
	./build/complexcalc