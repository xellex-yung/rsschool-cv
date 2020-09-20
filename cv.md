# Alexey Seryogin

## Contacts
* Mobile Number: 8 (918) 189 79 55  
* Email: xellex.yung@yandex.ru

## Summary
Hello, my name is Alexey or Xellex, as you prefer. 
And I just get a mental kick out of coding something. 
I have always been interested in the world of digital technologies, so my path began at University. 
Where I created programs for solving various routine tasks using C# and MS SQL. 
After completing my education I managed to work as a programmer in a Bank, 
where my responsibility was to download data from databases for various reports and solve simple data validation tasks.
I want to diversify my knowledge and gain experience in front-end software development. 
I have an analytical mind, am friendly, and enjoy working in a team.

## Skills
###### Back-end
* C# (desktop or console applications)
* MS SQL (DDL and queries of varying complexity)
###### Front-end
* HTML5
* CSS3 
* JS (basic)
###### Tools
* Visual Studio
* SSMS
* VS Code
* GIMP

## Code example C#:
        #region IsValidEmail
        /// <summary>
        /// Паттерн регулярного выражения электронной почты
        /// </summary>
        static string patternEmail = 
                                        @"^([0-9a-zA-Z]" + 
                                        @"([\+\-_\.][0-9a-zA-Z]+)*" + 
                                        @")+" + 
                                        @"@(([0-9a-zA-Z][-\w]*[0-9a-zA-Z]*\.)+[a-zA-Z0-9]{2,17})$";
        /// <summary>
        /// Валидация электронной почты 
        /// </summary>
        /// <param name="email">Электронная почта</param>
        /// <returns>Email валидный?</returns>
        public static bool IsValidEmail(string email)
        {
            return Regex.IsMatch(email, patternEmail);
        }
        #endregion
  
## Experience
**07.2016 - 10.2016**
* programmer in the Bank (https://kk.bank/)
