# * =======================
# *
# * Author: Matthew Moccaro
# * File:   Makefile
# * Type:   Makefile
# * 
# * Creation Date: 1/2/19
# *
# * Description: Makefile to
# * create the Network_Programming
# * example project.
# * 
# * ======================

#Parameters-------------------
CC=g++
ARGS=-Wall -std=c++11
SOURCE_PATH=../source/
BIN_PATH=../binaries/
OBJ_PATH=../objects/
INCLUDE_DIR=../source/
DEFINES=-D LINUX
INCLUDES=

#DEFAULTS
default: $(BIN_PATH)Network_Programming.exe

#Network Programming
$(BIN_PATH)Network_Programming.exe: $(SOURCE_PATH)Network_Programming.cpp
				  
	@echo ""
	@echo "Creating Main Executable..."
	@echo ""
	$(CC) $(ARGS) $(DEFINES) $(INCLUDES) $(SOURCE_PATH)Network_Programming.cpp $(OBJS) -o $(BIN_PATH)Network_Programming.exe
	@echo ""


#Clean and Refresh=================================================

#Clean
clean:
	rm $(BIN_PATH)* $(OBJ_PATH)*

#Refresh
refresh:
	rm $(BIN_PATH)* $(OBJ_PATH)*
	make

.PHONY: clean refresh

#End of File
