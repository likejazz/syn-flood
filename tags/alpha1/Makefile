CXXFLAGS =	-O2 -g -Wall -fmessage-length=0

OBJS =		syn-flood.o

LIBS =

TARGET =	syn-flood

$(TARGET):	$(OBJS)
	$(CXX) -o $(TARGET) $(OBJS) $(LIBS)

all:	$(TARGET)

clean:
	rm -f $(OBJS) $(TARGET)
