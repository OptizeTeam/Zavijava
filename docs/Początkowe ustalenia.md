# Modele i atrybuty
* Token
	* token (wymagane)
* User
	* name (wymagane)
	* password (wymagane)
* Client
	* name (wymagane)
* Project
 	* name (wymagane)
* Task
	* name (wymagane)
	* status (wymagane)
	* order
	* startDate
	* endDate
* Tag
	* name (wymagane)

# Relacje
* User (jeden) - Token (wiele) (wymagane dla Tokena)
* User (wiele) - Client (wiele)
* User (wiele) - Project (wiele)
* User (wiele) - Task (wiele)
* Client (jeden) - Project (wiele)
* Project (jeden) - Task (wiele)
* Task (jeden) - Task (wiele)
* Task (wiele) - Tag (wiele)

# Routingi
* Logowanie
* Wylogowywanie
* User CRUDL
* Client CRUDL
* Project CRUDL
* Task CRUDL
* Tag CRUDL

# Kolejność realizacji
1. Token, User, Logowanie, Wylogowywanie
2. Task (bez orderu)
3. Tag
4. Project
5. Client
6. Task order
