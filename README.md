# Number-Guessing-Game
### [certificate] - [freeCodeCamp] - [relational database]

![image](https://github.com/user-attachments/assets/3aaadd0b-2615-4077-a90d-ebcbb80b3c54)

# Submission
![image](https://github.com/user-attachments/assets/8dd16112-bf01-4416-8211-bc68e89b796c)

# Instructions
- To complete this project, you need to write a script that generates a random number between 1 and 1000 for users to guess. Create a `number_guess database` to hold the information suggested in the user stories. Connect to the interactive psql shell with `psql --username=freecodecamp --dbname=postgres` to create the database. In your script, you can create a PSQL variable for querying the database like this: `PSQL="psql --username=freecodecamp --dbname=<database_name> -t --no-align -c"`.

- Your script should only ask for input from the user to get the username and to take guesses. Your script should output exactly what is described in the user storied below, and nothing extra. The tests will add users to your database when the script has that ability, feel free to delete those. Some script related user stories may not pass until the script is completely working. Don't forget to commit your work frequently.

- If you leave your virtual machine, your database may not be saved. You can make a dump of it by entering `pg_dump -cC --inserts -U freecodecamp number_guess > number_guess.sql` in a bash terminal (not the psql one). It will save the commands to rebuild your database in `number_guess.sql`. The file will be located where the command was entered. If it's anything inside the project folder, the file will be saved in the VM. You can rebuild the database by entering `psql -U postgres < number_guess.sql` in a terminal where the .sql file is.

- If you are saving your progress on [freeCodeCamp.org](https://www.freecodecamp.org/), after getting all the tests to pass, follow the instructions above to save a dump of your database. Save the `number_guess.sql` file, as well as the final version of your `number_guess.sh` file, in a public repository and submit the URL to it on [freeCodeCamp.org](https://www.freecodecamp.org/).
