#include <stdio>
printf("Bienvenue dans le programe de configuration PC-1223 DMX \n");
printf("A quel numero LIDLINK desirez vous commencer \n");
//keboard input
//0 n'est pas valide, veuillex entrer nombre entre 1 et 254
//255 est le max
printf("La procedure configure presentement le Luminaire XXX");
printf("Apppuyez sur \"S\" pour debutter");
//test si luminaire connecte, fetch current lidlink address
//set dev adress to X, broadcast to ALL
//4c 49 44 00 00 4e 03 02 00 03 ff 4c 55 4d
//set DMX Adress to X, braodcast to all
//4c 49 44 00 00 4e 11 02 00 XX ff 4c 55 4d
//Set Overide 1, Braodcast to all
//4c 49 44 00 14 59 04 02 00 00 ff 4c 55 4d
//Set DMX enabale, brodcast to all
//4c 49 44 00 14 59 10 02 00 01 ff 4c 55 4d
//Send Command Identify, Broadcast to X only
//4c 49 44 00 14 4ee 0e 02 00 00 ff 4c 55 4d
printf("le Luminaire est maintenant configure"); 
printf("La procedure configure presentement le Luminaire XXX");
printf("Apppuyez sur \"S\" pour debutter");
