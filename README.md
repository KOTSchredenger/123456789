// sozdanie igri i personaja.cpp : Этот файл содержит функцию "main". Здесь начинается и заканчивается выполнение программы.
//

#include <iostream>
#include <Windows.h>



int main() {
		
SetConsoleCP(1251);
SetConsoleOutputCP(1251);

std::string pc_name, hometown;
std::string npc_name = "HERO";
int distance;
int days;

std::string intro = "Игра в стиле фэнтазий";

std::string question_1 = "Придумайте имя персонажа";
std::string question_2 = "Выберите пол героя";
std::string question_3 = "Выберите рост и вес героя";
std::string question_4 = "Герой создан";

std::cout << intro << std::endl;
std::cout << npc_name << ": - " << question_1 << "	";
std::cin >> pc_name;
std::cout << npc_name << ": - " << "Приветствую тебя герой"
<< pc_name << "!" << std::endl;
std::cout << npc_name << ": - " << question_2 << std::endl;
std::cin >> hometown;
std::cout << npc_name << ": - " << question_3 << std::endl;
std::cin >> distance;
std::cout << npc_name << ": - " << question_4 << std::endl;
std::cin >> days;
}
