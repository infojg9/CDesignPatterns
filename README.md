# MIT/BSD Redistributable License
# Author: https://github.com/infojg9
# CDesignPatterns



==========================


Build script output:

/opt/clion-2017.1.3/bin/cmake/bin/cmake --build /home/user/ClionProjects/CDesignPatterns/cmake-build-debug --target CDesignPatterns -- -j 2
Scanning dependencies of target CDesignPatterns
[ 25%] Building CXX object CMakeFiles/CDesignPatterns.dir/main.cpp.o
Using built-in specs.
COLLECT_GCC=/usr/bin/c++
Target: x86_64-linux-gnu
Configured with: ../src/configure -v --with-pkgversion='Ubuntu 5.4.1-2ubuntu1~16.04' --with-bugurl=file:///usr/share/doc/gcc-5/README.Bugs --enable-languages=c,ada,c++,java,go,d,fortran,objc,obj-c++ --prefix=/usr --program-suffix=-5 --enable-shared --enable-linker-build-id --libexecdir=/usr/lib --without-included-gettext --enable-threads=posix --libdir=/usr/lib --enable-nls --with-sysroot=/ --enable-clocale=gnu --enable-libstdcxx-debug --enable-libstdcxx-time=yes --with-default-libstdcxx-abi=new --enable-gnu-unique-object --disable-vtable-verify --enable-libmpx --enable-plugin --with-system-zlib --disable-browser-plugin --enable-java-awt=gtk --enable-gtk-cairo --with-java-home=/usr/lib/jvm/java-1.5.0-gcj-5-amd64/jre --enable-java-home --with-jvm-root-dir=/usr/lib/jvm/java-1.5.0-gcj-5-amd64 --with-jvm-jar-dir=/usr/lib/jvm-exports/java-1.5.0-gcj-5-amd64 --with-arch-directory=amd64 --with-ecj-jar=/usr/share/java/eclipse-ecj.jar --enable-objc-gc --enable-multiarch --disable-werror --with-arch-32=i686 --with-abi=m64 --with-multilib-list=m32,m64,mx32 --enable-multilib --with-tune=generic --enable-checking=release --build=x86_64-linux-gnu --host=x86_64-linux-gnu --target=x86_64-linux-gnu
Thread model: posix
gcc version 5.4.1 20160904 (Ubuntu 5.4.1-2ubuntu1~16.04) 
COLLECT_GCC_OPTIONS='-v' '-pipe' '-D' 'GENERIC_DELEGATE_ON' '-Wall' '-Wextra' '-Wchkp' '-Wdouble-promotion' '-Wformat=1' '-Werror' '-Wpedantic' '-O0' '-g3' '-ggdb3' '-ftest-coverage' '-fprofile-arcs' '-pthread' '-g' '-std=gnu++14' '-o' 'CMakeFiles/CDesignPatterns.dir/main.cpp.o' '-c' '-shared-libgcc' '-mtune=generic' '-march=x86-64'
 /usr/lib/gcc/x86_64-linux-gnu/5/cc1plus -quiet -v -imultiarch x86_64-linux-gnu -dD -D_GNU_SOURCE -D_REENTRANT -D GENERIC_DELEGATE_ON /home/user/ClionProjects/CDesignPatterns/main.cpp -quiet -dumpbase main.cpp -mtune=generic -march=x86-64 -auxbase-strip CMakeFiles/CDesignPatterns.dir/main.cpp.o -g3 -ggdb3 -g -O0 -Wall -Wextra -Wchkp -Wdouble-promotion -Wformat=1 -Werror -Wpedantic -std=gnu++14 -version -ftest-coverage -fprofile-arcs -fstack-protector-strong -Wformat-security -o - |
 as -v --64 -o CMakeFiles/CDesignPatterns.dir/main.cpp.o
GNU assembler version 2.26.1 (x86_64-linux-gnu) using BFD version (GNU Binutils for Ubuntu) 2.26.1
GNU C++14 (Ubuntu 5.4.1-2ubuntu1~16.04) version 5.4.1 20160904 (x86_64-linux-gnu)
	compiled by GNU C version 5.4.1 20160904, GMP version 6.1.0, MPFR version 3.1.4, MPC version 1.0.3
GGC heuristics: --param ggc-min-expand=100 --param ggc-min-heapsize=131072
ignoring duplicate directory "/usr/include/x86_64-linux-gnu/c++/5"
ignoring nonexistent directory "/usr/local/include/x86_64-linux-gnu"
ignoring nonexistent directory "/usr/lib/gcc/x86_64-linux-gnu/5/../../../../x86_64-linux-gnu/include"
#include "..." search starts here:
#include <...> search starts here:
 /usr/include/c++/5
 /usr/include/x86_64-linux-gnu/c++/5
 /usr/include/c++/5/backward
 /usr/lib/gcc/x86_64-linux-gnu/5/include
 /usr/local/include
 /usr/lib/gcc/x86_64-linux-gnu/5/include-fixed
 /usr/include/x86_64-linux-gnu
 /usr/include
End of search list.
GNU C++14 (Ubuntu 5.4.1-2ubuntu1~16.04) version 5.4.1 20160904 (x86_64-linux-gnu)
	compiled by GNU C version 5.4.1 20160904, GMP version 6.1.0, MPFR version 3.1.4, MPC version 1.0.3
GGC heuristics: --param ggc-min-expand=100 --param ggc-min-heapsize=131072
Compiler executable checksum: bd2b99af5e5a15cbe8347f870009dafe
COMPILER_PATH=/usr/lib/gcc/x86_64-linux-gnu/5/:/usr/lib/gcc/x86_64-linux-gnu/5/:/usr/lib/gcc/x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/5/:/usr/lib/gcc/x86_64-linux-gnu/
LIBRARY_PATH=/usr/lib/gcc/x86_64-linux-gnu/5/:/usr/lib/gcc/x86_64-linux-gnu/5/../../../x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/5/../../../../lib/:/lib/x86_64-linux-gnu/:/lib/../lib/:/usr/lib/x86_64-linux-gnu/:/usr/lib/../lib/:/usr/lib/gcc/x86_64-linux-gnu/5/../../../:/lib/:/usr/lib/
COLLECT_GCC_OPTIONS='-v' '-pipe' '-D' 'GENERIC_DELEGATE_ON' '-Wall' '-Wextra' '-Wchkp' '-Wdouble-promotion' '-Wformat=1' '-Werror' '-Wpedantic' '-O0' '-g3' '-ggdb3' '-ftest-coverage' '-fprofile-arcs' '-pthread' '-g' '-std=gnu++14' '-o' 'CMakeFiles/CDesignPatterns.dir/main.cpp.o' '-c' '-shared-libgcc' '-mtune=generic' '-march=x86-64'
[ 50%] Linking CXX executable CDesignPatterns
Using built-in specs.
COLLECT_GCC=/usr/bin/c++
COLLECT_LTO_WRAPPER=/usr/lib/gcc/x86_64-linux-gnu/5/lto-wrapper
Target: x86_64-linux-gnu
Configured with: ../src/configure -v --with-pkgversion='Ubuntu 5.4.1-2ubuntu1~16.04' --with-bugurl=file:///usr/share/doc/gcc-5/README.Bugs --enable-languages=c,ada,c++,java,go,d,fortran,objc,obj-c++ --prefix=/usr --program-suffix=-5 --enable-shared --enable-linker-build-id --libexecdir=/usr/lib --without-included-gettext --enable-threads=posix --libdir=/usr/lib --enable-nls --with-sysroot=/ --enable-clocale=gnu --enable-libstdcxx-debug --enable-libstdcxx-time=yes --with-default-libstdcxx-abi=new --enable-gnu-unique-object --disable-vtable-verify --enable-libmpx --enable-plugin --with-system-zlib --disable-browser-plugin --enable-java-awt=gtk --enable-gtk-cairo --with-java-home=/usr/lib/jvm/java-1.5.0-gcj-5-amd64/jre --enable-java-home --with-jvm-root-dir=/usr/lib/jvm/java-1.5.0-gcj-5-amd64 --with-jvm-jar-dir=/usr/lib/jvm-exports/java-1.5.0-gcj-5-amd64 --with-arch-directory=amd64 --with-ecj-jar=/usr/share/java/eclipse-ecj.jar --enable-objc-gc --enable-multiarch --disable-werror --with-arch-32=i686 --with-abi=m64 --with-multilib-list=m32,m64,mx32 --enable-multilib --with-tune=generic --enable-checking=release --build=x86_64-linux-gnu --host=x86_64-linux-gnu --target=x86_64-linux-gnu
Thread model: posix
gcc version 5.4.1 20160904 (Ubuntu 5.4.1-2ubuntu1~16.04) 
COMPILER_PATH=/usr/lib/gcc/x86_64-linux-gnu/5/:/usr/lib/gcc/x86_64-linux-gnu/5/:/usr/lib/gcc/x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/5/:/usr/lib/gcc/x86_64-linux-gnu/
LIBRARY_PATH=/usr/lib/gcc/x86_64-linux-gnu/5/:/usr/lib/gcc/x86_64-linux-gnu/5/../../../x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/5/../../../../lib/:/lib/x86_64-linux-gnu/:/lib/../lib/:/usr/lib/x86_64-linux-gnu/:/usr/lib/../lib/:/usr/lib/gcc/x86_64-linux-gnu/5/../../../:/lib/:/usr/lib/
COLLECT_GCC_OPTIONS='-v' '-pipe' '-D' 'GENERIC_DELEGATE_ON' '-Wall' '-Wextra' '-Wchkp' '-Wdouble-promotion' '-Wformat=1' '-Werror' '-Wpedantic' '-O0' '-g3' '-ggdb3' '-ftest-coverage' '-fprofile-arcs' '-pthread' '-g' '-o' 'CDesignPatterns' '-shared-libgcc' '-mtune=generic' '-march=x86-64'
 /usr/lib/gcc/x86_64-linux-gnu/5/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/5/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/5/lto-wrapper -plugin-opt=-fresolution=/tmp/cchvRH34.res -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lpthread -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lgcc --sysroot=/ --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -z relro -o CDesignPatterns /usr/lib/gcc/x86_64-linux-gnu/5/../../../x86_64-linux-gnu/crt1.o /usr/lib/gcc/x86_64-linux-gnu/5/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/5/crtbegin.o -L/usr/lib/gcc/x86_64-linux-gnu/5 -L/usr/lib/gcc/x86_64-linux-gnu/5/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/5/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/5/../../.. CMakeFiles/CDesignPatterns.dir/CPointerToImplementation.cpp.o CMakeFiles/CDesignPatterns.dir/CSingleton.cpp.o CMakeFiles/CDesignPatterns.dir/main.cpp.o -lstdc++ -lm -lgcov -lgcc_s -lgcc -lpthread -lc -lgcc_s -lgcc /usr/lib/gcc/x86_64-linux-gnu/5/crtend.o /usr/lib/gcc/x86_64-linux-gnu/5/../../../x86_64-linux-gnu/crtn.o
[100%] Built target CDesignPatterns



=========

Execution output:


/home/user/CDesignPatterns/cmake-build-debug/CDesignPatterns
main ThreadId: ThreadId: 140431100217088140431125894976 executing at priority , Priority: 0, Policy: 020
ThreadId: 140431100217088 executing at priority 20
Called by Thread Id: 140431100217088

t1 ThreadId: 140431108609792, Priority: 0, Policy: 0
t2 ThreadId: 140431100217088, Priority: 0, Policy: 0
Called by Thread Id: 140431108609792
*********Hello, World!
PimpleTestObject1: consumed : 0.000359058 secs

Process finished with exit code 0
