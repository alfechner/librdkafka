add_executable(rdkafka_example rdkafka_example.c)
target_link_libraries(rdkafka_example PUBLIC rdkafka)

add_executable(rdkafka_consumer_example rdkafka_consumer_example.c)
target_link_libraries(rdkafka_consumer_example PUBLIC rdkafka)

add_executable(rdkafka_performance rdkafka_performance.c)
target_link_libraries(rdkafka_performance PUBLIC rdkafka)

add_executable(rdkafka_example_cpp rdkafka_example.cpp)
target_link_libraries(rdkafka_example_cpp PUBLIC rdkafka++)

add_executable(kafkatest_verifiable_client kafkatest_verifiable_client.cpp)
target_link_libraries(kafkatest_verifiable_client PUBLIC rdkafka++)

add_executable(rdkafka_consumer_example_cpp rdkafka_consumer_example.cpp)
target_link_libraries(rdkafka_consumer_example_cpp PUBLIC rdkafka++)
