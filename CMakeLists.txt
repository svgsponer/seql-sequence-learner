project("SEQL")

add_executable(seql_learn seql_learn.cpp)
add_executable(seql_mkmodel seql_mkmodel.cpp)
add_executable(seql_classify seql_classify.cpp
                             str2node_string_symbol.cpp)
add_executable(seql_classify_tune_threshold_min_error seql_classify_tune_threshold_min_errors.cpp
                                                      str2node_string_symbol.cpp)
