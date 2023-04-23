Simple ESP/Wallhacks for CSGO in C++

1. You have to go in to the "build" folder and run the exe file
 -- If you can not see boxes around the enemys do this:
--------------------------------------------------------------------
1. Delete your "build" folder and open the .sln file with visual studio preview with the game dev extension
- To set your offsets go into the main.cpp file and at line 15-23. Update the offsets to your offsets -> 0xDEA964 | You get it of the use of hazedumper
2. On the top you select "Release" and "x86"
3. Do a rightclick on the right upper side on "external_esp_tutorial" and go to "Properties"
- Configuration Properties -- General -- Configuration Type -- select the exe Application
- Configuration Properties -- General -- C++ Language -- select  C++ 20
- Configuration Properties -- Advanced -- Configuration Type -- select the exe Application
4. On the top of the property page you have to select "All Configurations" and Plattform "Win32" and **SAVE**
5. Go in to the main.cpp file and look at the #include -- you only have to paste your path of the files into line 10 to 13 like i did it
6. Klick on "Build" on the top and then "Build Solution"
Last Step: Go to your directory and open the exe file

(Working on 23.04.2023)
