INCLUDE_DIRECTORIES(${SERVER_INCLUDE_DIRS})

ADD_EXECUTABLE(UDPServer Server.cpp)
ADD_EXECUTABLE(UDPClient client.cpp)
TARGET_LINK_LIBRARIES(UDPServer ${SERVER_LIBRARIES})
TARGET_LINK_LIBRARIES(UDPClient ${SERVER_LIBRARIES})
