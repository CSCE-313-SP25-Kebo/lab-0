# Compiler
CXX = g++

# Compiler flags
CXXFLAGS = -std=c++17 -g

# Source files
SRC = lab-0.cpp bank.cpp

# Executable name
EXEC = lab-0

# Rule to build the executable (no intermediate .o files)
$(EXEC): $(SRC)
	$(CXX) $(CXXFLAGS) $(SRC) -o $(EXEC)

# Clean up the executable
clean:
	rm -f $(EXEC)
