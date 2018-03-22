
CPPFLAGS = -std=c++11 -lev -lhiredis -lredox_static -lpthread 

all:
	g++ basic.cpp -o basic ${CPPFLAGS}
	g++ basic_threaded.cpp -o basic_threaded ${CPPFLAGS}
	g++ binary_data.cpp -o binary_data ${CPPFLAGS}
	g++ binary_data_publish.cpp -o binary_data_publish ${CPPFLAGS}
	g++ data_types.cpp -o data_types ${CPPFLAGS}
	g++ jitter_test.cpp -o jitter_test ${CPPFLAGS}
	g++ lpush_benchmark.cpp -o lpush_benchmark ${CPPFLAGS}
	g++ multi_client.cpp -o multi_client ${CPPFLAGS}
	g++ pub_sub.cpp -o pub_sub ${CPPFLAGS}
	g++ speed_test_async.cpp -o speed_test_async ${CPPFLAGS}
	g++ speed_test_async_multi.cpp -o speed_test_async_multi ${CPPFLAGS}
	g++ speed_test_pubsub.cpp -o speed_test_pubsub ${CPPFLAGS}
	g++ speed_test_sync.cpp -o speed_test_sync ${CPPFLAGS}

clean:
	rm -rf basic basic_threaded binary_data binary_data_publish data_types jitter_test lpush_benchmark multi_client pub_sub speed_test_async speed_test_async_multi speed_test_pubsub speed_test_sync
