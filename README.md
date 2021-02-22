# The project is a CRUD that can write into database a species, managers and animals that are in the zoo.
*** The database should have three tables that are connected between each other. **

| Species |     |                       
| :---: | :---: | 
| id | int(11)| 
| name | varcahr(64)|  

| Managers| |                            
| :---: | :---: | 
| id | int(11)| 
| name| varcahr(64)| 
| surname| varcahr(64)|  
| species_id | int(11)| 
***The connection between tables*** | **managers.specie_id *------> species.id***

| Animals| |                            
| :---: | :---: | 
| id | int(11)| 
| name| varcahr(255)| 
| specie_id| int(11)|   
| birth_year| tinyint(4)|   
| animal_book| text|   
| manager_id | int(11)| 
***The connection between tables*** | **animals.manager_id *------> managers.id*** |
| |**animals.spiece_id *------> species.id***|



**The project has several specifications:**
- add, deleate and modify data from database. 
- managers have a field (drop down) from which it is possible to select species
- animals have a field (drop down) from which it is possible to select managers and spiecies
- validation of fileds
- notes field for truckscreated with redactor
- protection agains SQL 


### project was made with Symfony framework
