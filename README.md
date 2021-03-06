# openWeatherCli

###You need any c++ compiler with c++11 support and boost lib.
>g++ -std=c++11 main.cc -o openWeatherCli -lboost_system

###Installing boost:

  Debian/Ubuntu:
  > sudo apt-get install libboost-all-dev

  Fedora:
  > sudo dnf install boost-devel
  
  Windows:
  
  >* Download latest boost release [here.](http://sourceforge.net/projects/boost/files/boost/1.59.0/)
  
  >* From Visual Studio's File menu, select New > Project…

  >* In the left-hand pane of the resulting New Project dialog, select Visual C++ > Win32.

  >*  In the right-hand pane, select Win32 Console Application (VS8.0) or Win32 Console Project (VS7.1).

  >*  Right-click example in the Solution Explorer pane and select Properties from the resulting pop-up menu

  >*  In Configuration Properties > C/C++ > General > Additional Include Directories, enter the path to the Boost root directory, for example "C:\Program Files\boost\boost_1_55_0"

  >* In Configuration Properties > C/C++ > Precompiled Headers, change Use Precompiled Header (/Yu) to Not Using Precompiled Headers.

  [More on boost.org](http://www.boost.org/doc/libs/1_55_0/more/getting_started/windows.html)

