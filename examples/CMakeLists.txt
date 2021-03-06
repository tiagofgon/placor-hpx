
# module
add_library(module SHARED module.cpp)
target_compile_features(module PUBLIC cxx_std_17)
set_target_properties(module PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(module PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(module PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(module PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    module
    PRIVATE
        libcor
	    HPX::hpx
)

# basicOperations
add_library(basicOperations SHARED basicOperations.cpp)
target_compile_features(basicOperations PUBLIC cxx_std_17)
set_target_properties(basicOperations PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(basicOperations PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(basicOperations PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(basicOperations PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    basicOperations
    PRIVATE
        libcor
	    HPX::hpx
)

# callableModule
add_library(callableModule SHARED callableModule.cpp)
target_compile_features(callableModule PUBLIC cxx_std_17)
set_target_properties(callableModule PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(callableModule PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(callableModule PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(callableModule PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    callableModule
    PRIVATE
        libcor
	    HPX::hpx
)


# parallel
add_library(parallel SHARED parallel.cpp)
target_compile_features(parallel PUBLIC cxx_std_17)
set_target_properties(parallel PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(parallel PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(parallel PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(parallel PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    parallel
    PRIVATE
        libcor
	    HPX::hpx
)


# send_an_object_2 - HPX
add_library(send_an_object_2 SHARED send_an_object_2.cpp)
target_compile_features(send_an_object_2 PUBLIC cxx_std_17)
set_target_properties(send_an_object_2 PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(send_an_object_2 PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(send_an_object_2 PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(send_an_object_2 PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    send_an_object_2
    PRIVATE
        libcor
        HPX::hpx
)

# send_an_object_1 - HPX
add_library(send_an_object_1 SHARED send_an_object_1.cpp)
target_compile_features(send_an_object_1 PUBLIC cxx_std_17)
set_target_properties(send_an_object_1 PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(send_an_object_1 PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(send_an_object_1 PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(send_an_object_1 PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    send_an_object_1
    PRIVATE
        libcor
        HPX::hpx
)

# parallel3 - HPX
add_library(message_broadcast SHARED message_broadcast.cpp)
target_compile_features(message_broadcast PUBLIC cxx_std_17)
set_target_properties(message_broadcast PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(message_broadcast PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(message_broadcast PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(message_broadcast PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    message_broadcast
    PRIVATE
        libcor
        HPX::hpx
)

# spawn
add_library(spawn SHARED spawn.cpp)
target_compile_features(spawn PUBLIC cxx_std_17)
set_target_properties(spawn PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(spawn PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(spawn PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(spawn PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    spawn
    PRIVATE
        libcor
	    HPX::hpx
)

# inter_closure
add_library(inter_closure SHARED inter_closure.cpp)
target_compile_features(inter_closure PUBLIC cxx_std_17)
set_target_properties(inter_closure PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(inter_closure PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(inter_closure PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(inter_closure PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    inter_closure
    PRIVATE
        libcor
	    HPX::hpx
)


# server_rpc
add_library(server_rpc SHARED server_rpc.cpp)
target_compile_features(server_rpc PUBLIC cxx_std_17)
set_target_properties(server_rpc PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(server_rpc PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(server_rpc PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(server_rpc PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    server_rpc
    PRIVATE
        libcor
	    HPX::hpx
)

# client_rpc
add_library(client_rpc SHARED client_rpc.cpp)
target_compile_features(client_rpc PUBLIC cxx_std_17)
set_target_properties(client_rpc PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(client_rpc PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(client_rpc PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(client_rpc PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    client_rpc
    PRIVATE
        libcor
	    HPX::hpx
)

# teste_pool
add_library(teste_pool SHARED teste_pool.cpp)
target_compile_features(teste_pool PUBLIC cxx_std_17)
set_target_properties(teste_pool PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(teste_pool PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(teste_pool PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(teste_pool PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    teste_pool
    PRIVATE
        libcor
	    HPX::hpx
)

# create_remote
add_library(create_remote SHARED create_remote.cpp)
target_compile_features(create_remote PUBLIC cxx_std_17)
set_target_properties(create_remote PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(create_remote PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(create_remote PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(create_remote PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    create_remote
    PRIVATE
        libcor
	    HPX::hpx
)

# data_example_1
add_library(data_example_1 SHARED data_example_1.cpp)
target_compile_features(data_example_1 PUBLIC cxx_std_17)
set_target_properties(data_example_1 PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(data_example_1 PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(data_example_1 PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(data_example_1 PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    data_example_1
    PRIVATE
        libcor
	    HPX::hpx
)

# data_example_2
add_library(data_example_2 SHARED data_example_2.cpp)
target_compile_features(data_example_2 PUBLIC cxx_std_17)
set_target_properties(data_example_2 PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(data_example_2 PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(data_example_2 PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(data_example_2 PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    data_example_2
    PRIVATE
        libcor
	    HPX::hpx
)

# queue_program
add_library(queue_program SHARED queue_program.cpp)
target_compile_features(queue_program PUBLIC cxx_std_17)
set_target_properties(queue_program PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(queue_program PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(queue_program PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(queue_program PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    queue_program
    PRIVATE
        libcor
	    HPX::hpx
)

# stencil2d
add_library(stencil2d SHARED stencil2d.cpp)
target_compile_features(stencil2d PUBLIC cxx_std_17)
set_target_properties(stencil2d PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(stencil2d PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(stencil2d PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(stencil2d PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    stencil2d
    PRIVATE
        libcor
	    HPX::hpx
)

# multichannel_example
add_library(multichannel_example SHARED multichannel_example.cpp)
target_compile_features(multichannel_example PUBLIC cxx_std_17)
set_target_properties(multichannel_example PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(multichannel_example PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(multichannel_example PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(multichannel_example PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    multichannel_example
    PRIVATE
        libcor
        HPX::hpx
        # HPX::iostreams
)

# unichannel_example
add_library(unichannel_example SHARED unichannel_example.cpp)
target_compile_features(unichannel_example PUBLIC cxx_std_17)
set_target_properties(unichannel_example PROPERTIES CXX_EXTENSIONS OFF)
set_target_properties(unichannel_example PROPERTIES POSITION_INDEPENDENT_CODE ON)
set_target_properties(unichannel_example PROPERTIES COMPILE_FLAGS -O2)
set_target_properties(unichannel_example PROPERTIES PREFIX "lib" SUFFIX ".so")
target_link_libraries(
    unichannel_example
    PRIVATE
        libcor
        HPX::hpx
        # HPX::iostreams
)

install(
    TARGETS
        module
        basicOperations
        callableModule
        parallel
        send_an_object_1
        send_an_object_2
        message_broadcast
        spawn
        inter_closure
        teste_pool
        create_remote
        server_rpc
        client_rpc
        data_example_1
        data_example_2
        queue_program
        stencil2d
        multichannel_example
        unichannel_example
    LIBRARY
        DESTINATION examples
)
    