Hue Lights Project - INTERNET OF THINGS

Agile Project Management - School Project

Includes a login authentication screen for users.

Used Web Toolkit API to create a web application that can manipulate lights within a household.
User can toggle lights and groups, change brightness, saturation, colour, create groups and schedules, and have saved sessions.
Additional features include rave lights, christmas lights, and glowing lights.

Sends POST, PUT, and GET requests to the server in order to manipulate lights.

Includes DOXYGEN type comments, and UML diagrams.




Members Include: Kenneth Galang, Jason Chung, Sama Rahimian, Nick Friesen



Compile:
g++ *.cpp -o main.out -std=c++11 -lwthttp -lwt -lboost_random -lboost_regex -lboost_signals -lboost_system -lboost_thread -lboost_filesystem -lboost_program_options -lboost_date_time

./main.out --docroot /usr/local/share/Wt --http-address localhost --http-port 8080
