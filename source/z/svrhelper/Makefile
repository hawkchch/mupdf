clang -L../../build/release/curl -L../../thirdparty/openssl -lcurl -lcrypto -lssl -I../../thirdparty/curl/include -o httptest curlTest.c

clang -g -L../../../build/debug/ -L../../../thirdparty/openssl/macos -lmupdfthird -lcurl -lcrypto -lssl -lmupdf -I../../thirdparty/curl/include -I../../../include/  -o httptest ntko_http_test.c ./src/net_helper.c ./src/ntko_helper.c


clang++ -g -stdlib=libc++ -std=c++11 -L../../../build/debug/ -L../../../thirdparty/openssl/macos -lmupdfthird -lmupdf -I../../thirdparty/curl/include -I../../../include/  -o esptest ./ntko_esp.cpp ./espTest.cpp ./keygen.c