if(TARGET MQT::QMapNA)
  file(GLOB_RECURSE NA_TEST_SOURCES *.cpp)
  package_add_test(mqt-qmap-na-test MQT::QMapNA ${NA_TEST_SOURCES})
endif()
