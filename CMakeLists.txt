cmake_minimum_required(VERSION 3.27)
project(Banking_System_With_AVL_Tree C)

set(CMAKE_C_STANDARD 11)

include_directories(Model)
include_directories(View)

add_executable(Banking_System_With_AVL_Tree
        Model/AVL_STRUCTURE.h
        Model/DataBase.h
        Model/Decryption.h
        Model/Encryption.h
        Model/Transition.h
        View/Home.h
        View/login.h
        View/privilege.h
        ChinLandBankingSystem.c
        View/Registration.h)
