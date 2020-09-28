CXX=g++
CXXFLAGS=-g -ggdb -O2 -Wall

TARGET=winzigi
OBJS=winzigi.o

all: $(TARGET)

clean:
	rm -rf $(TARGET)	$(OBJS)

install:
	cp $(TARGET)	/usr/local/bin

winzigi.o:

$(TARGET):	$(OBJS)
			$(CXX) -o $(TARGET) $(OBJS)

.cpp.o:
	$(CXX)	$(CXXFLAGS) -c -o $@ $<

