# Отчет по третьей лабораторной работе 
1. Создал три виртуальные машины. 
2. На все три поставил Debian 
3. В настройках VirtualBox для каждой машины проставил такие настройки сети, но для каждой виртуальной машины поставил свой MAC адрес

![{C7EA56B3-31F5-4BD3-96D7-0FE70AA39069}](https://github.com/user-attachments/assets/77ea60c4-3555-468a-9358-d4c0e16aea06)
4. Далее запустил три машины 
![{5C5A302D-A35E-4F4D-958D-E990B4CF6B0C}](https://github.com/user-attachments/assets/a5592bc7-7e61-46e1-b403-d56aaff17b30)
5. Так как я использовал Debian, прописал себя в sudo
![{C4F60970-E1E0-4DB9-B8EC-C1AA194C794F}](https://github.com/user-attachments/assets/40acd061-e32f-48b6-9f47-611f983470fd)
6. С помощью ip a узнаю ip-адреса каждой виртуальной машины
Адрес Машины А: 192.168.0.100
Адрес Машины Б: 192.168.0.102
Адрес Машины В: 192.168.0.104
![{E3F9C701-C67B-4BDD-B0CB-EC900EB9AD77}](https://github.com/user-attachments/assets/4da0f9c8-fb75-46b7-9af4-a6ab01e9357d)
7. Далее проверяю есть ли подключение к интернету с помощью ping 8.8.8.8
![{16FC66EC-CCC4-404D-8A7C-2193D73CB740}](https://github.com/user-attachments/assets/f8bd200a-c2fc-40f1-9040-9a4f68db9347)
8.Далее запрещаю доступ из Б в В с помощью пакета iptables, который установил с помощью sudo apt install iptables
![{E3F9C701-C67B-4BDD-B0CB-EC900EB9AD77}](https://github.com/user-attachments/assets/8cdae037-842c-48b5-a7f7-58b973c23246)
9. Проверяю подключение между машинами 
![{BA82C3F6-172F-45ED-8D8D-11D7C3660571}](https://github.com/user-attachments/assets/0033d885-0822-459b-be70-ac5371907a76)
![{08A93331-5F92-42AF-8F24-71DE4647D3E2}](https://github.com/user-attachments/assets/4f7654bd-1fa7-4bf1-8d18-e80875720662)
Как видно из скриншотов доступа из Б в В нет. 

