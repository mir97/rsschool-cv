## Nikita Mironov
### Contacts for communication:
-  miron0v.nikita@yandex.ru
-  +375-29-1257961
-  
### Little about me
I consider one of my strong qualities to be quick assimilation of material, communication, responsiveness and organizational skills. I came to this project to gain experience working in a team under the guidance of a mentor. I want to change my main field of activity and start working in my specialty.

### Technical skills:
-  C#, C++, Java, Python, HTML5, CSS3, Javascript, Git.
-  MySQL, SQL, Oracle. 
-  Have an experience with JQuery, React JS, MATLAB, SolidWorks, ASP.Net Core 2.0.

### Code examples	
```@Override
        public async Task<IActionResult> Login(LoginViewModel model)
        {
            if (ModelState.IsValid)
            {
                var result =
                    await _signInManager.PasswordSignInAsync(model.Email, model.Password, model.RememberMe, false);
                if (result.Succeeded)
                {
                    // проверяем, принадлежит ли URL приложению
                    if (!string.IsNullOrEmpty(model.ReturnUrl) && Url.IsLocalUrl(model.ReturnUrl))
                    {
                        return Redirect(model.ReturnUrl);
                    }
                    else
                    {
                        return RedirectToAction("Index", "Home");
                    }
                }
                else
                {
                    ModelState.AddModelError("", "Неправильный логин и (или) пароль");
                }
            }
            return View(model);
        }
```

### Experience:
#### Client server web app implemented ASP.NET Core MVC С#. 
##### Project goals: Creating a cross-platform web application for automating the work of the university administration. 
##### The major: 
-  User Authentication System. 
-  Link emails between users. 
-  Graphical interface (HTML,JS) for working with the MySQL. 
-  Database Analysis and calculation of academic performance of faculties by several parameters 
-  Access ranking system
-  Admin panel.
##### Technologies used: C#, JS ,HTML ,JQuery, MySQL.
*https://github.com/mir97/Rectotar
        
### Education:
-  GOMEL STATE TECHNICAL UNIVERSITY NAMED AFTER P. O. SUKHOI Gomel/Belarus 01.09.2015 – 30.06.2019 BS (ENGINEERING PROGRAMMER)
-  RS-School JS/FE 2021Q1 online 08.02.2021 – present

### English level:
Different tests give me a rating A2. I think realy my English is between A1 and A2. I continue to study.

