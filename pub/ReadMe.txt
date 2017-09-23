工程编译使用时要定义KERNELHELPER_BUILDING
会自动添加以下这些库
#if !defined(KERNELHELPER_BUILDING)

#pragma comment (lib, "GDI32.LIB")
#pragma comment (lib, "USER32.LIB")
#pragma comment (lib, "ADVAPI32.LIB")
#pragma comment (lib, "WS2_32.lib")
#pragma comment (lib, "MSWSOCK.lib")
#pragma comment (lib, "wldap32.lib")
#pragma comment (lib, "crypt32.lib")
#pragma comment (lib, "normaliz.lib")
#pragma comment (lib, "libeay32.lib")
#pragma comment (lib, "ssleay32.lib")
#pragma comment (lib, "zlibstatic.lib")
#pragma comment (lib, "winsqlite.lib")
#pragma comment (lib, "libssh2.lib")
#pragma comment (lib, "libcares.lib")
#pragma comment (lib, "libcurl.lib")
#pragma comment (lib, "lib_json.lib")
#pragma comment (lib, "kernelhelper.lib")

#endif
