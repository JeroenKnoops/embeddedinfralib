ccola_component(stream_test gmock_test)

    ccola_sources(
        StreamMock.hpp
        TestBoundedDequeInputStream.cpp
        TestByteInputStream.cpp
        TestByteOutputStream.cpp
        TestLimitedInputStream.cpp
        TestLimitedOutputStream.cpp
        TestOutputStreamSwitch.cpp
        TestStdStringInputStream.cpp
        TestStdStringOutputStream.cpp
        TestStringInputStream.cpp
        TestStringOutputStream.cpp
    )

    ccola_dependencies(
        stream
        util_test_helper
    )

ccola_end_component()
