# Power App 
First app Formulas 


Menuitems=
Table(
    {Id:1,
    Name:"Home",
    Icon:Menuicons.Home,
    screen:App.ActiveScreen
    },
        {Id:2,
    Name:"Tasks",
    Icon:Menuicons.Task,
    screen:App.ActiveScreen
    },
        {Id:3,
    Name:"Search",
    Icon:Menuicons.Search,
    screen:App.ActiveScreen
    },
        {Id:4,
    Name:"History",
    Icon:Menuicons.History,
    screen:App.ActiveScreen
    },
        {Id:5,
    Name:"Contact Us",
    Icon:Menuicons.Contactus,
    screen:App.ActiveScreen
    },
        {Id:6,
    Name:"About us",
    Icon: Menuicons.Aboutus,
    screen:App.ActiveScreen
    },
        {Id:1,
    Name:"Home",
    Icon:"",
    screen:App.ActiveScreen
    }
);


Menuicons = 
{
    Home: "<svg xmlns='http://www.w3.org/2000/svg' width='512' height='512' viewBox='0 0 512 512'><path fill='currentColor' d='M261.56 101.28a8 8 0 0 0-11.06 0L66.4 277.15a8 8 0 0 0-2.47 5.79L63.9 448a32 32 0 0 0 32 32H192a16 16 0 0 0 16-16V328a8 8 0 0 1 8-8h80a8 8 0 0 1 8 8v136a16 16 0 0 0 16 16h96.06a32 32 0 0 0 32-32V282.94a8 8 0 0 0-2.47-5.79Z'/><path fill='currentColor' d='m490.91 244.15l-74.8-71.56V64a16 16 0 0 0-16-16h-48a16 16 0 0 0-16 16v32l-57.92-55.38C272.77 35.14 264.71 32 256 32c-8.68 0-16.72 3.14-22.14 8.63l-212.7 203.5c-6.22 6-7 15.87-1.34 22.37A16 16 0 0 0 43 267.56L250.5 69.28a8 8 0 0 1 11.06 0l207.52 198.28a16 16 0 0 0 22.59-.44c6.14-6.36 5.63-16.86-.76-22.97'/></svg>",
    Task: "<svg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24'><path fill='currentColor' d='M17.75 2.001a2.25 2.25 0 0 1 2.245 2.096L20 4.25v10.128q-.181.12-.341.28l-3.409 3.408l-.908-.91a2.24 2.24 0 0 0-1.5-.657h2.408a.75.75 0 1 0 0-1.5h-5.004a.75.75 0 0 0 0 1.5h2.413a2.25 2.25 0 0 0-1.5 3.839l1.659 1.66H6.25a2.25 2.25 0 0 1-2.245-2.096L4 19.75V4.251a2.25 2.25 0 0 1 2.096-2.245l.154-.005zM9 7.751a1 1 0 1 0-2 0a1 1 0 0 0 2 0M11.246 7a.75.75 0 0 0 0 1.5h5.004a.75.75 0 1 0 0-1.5zm-.75 4.75c0 .414.336.75.75.75h5.004a.75.75 0 1 0 0-1.5h-5.004a.75.75 0 0 0-.75.75M9 11.75a1 1 0 1 0-2 0a1 1 0 0 0 2 0m0 3.998a1 1 0 1 0-2 0a1 1 0 0 0 2 0m7.25 4.441l4.47-4.47a.75.75 0 1 1 1.06 1.061l-5 5l-.051.047a.75.75 0 0 1-1.01-.047l-2.5-2.501a.75.75 0 0 1 1.062-1.06z'/></svg>",
    Search:"<svg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24'><path fill='currentColor' d='m19.6 21l-6.3-6.3q-.75.6-1.725.95T9.5 16q-2.725 0-4.612-1.888T3 9.5t1.888-4.612T9.5 3t4.613 1.888T16 9.5q0 1.1-.35 2.075T14.7 13.3l6.3 6.3zM9.5 14q1.875 0 3.188-1.312T14 9.5t-1.312-3.187T9.5 5T6.313 6.313T5 9.5t1.313 3.188T9.5 14'/></svg>",
    History:"<svg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24'><path fill='currentColor' d='M13 3a9 9 0 0 0-9 9H1l3.89 3.89l.07.14L9 12H6c0-3.87 3.13-7 7-7s7 3.13 7 7s-3.13 7-7 7c-1.93 0-3.68-.79-4.94-2.06l-1.42 1.42A8.95 8.95 0 0 0 13 21a9 9 0 0 0 0-18m-1 5v5l4.25 2.52l.77-1.28l-3.52-2.09V8z'/></svg>",
    Contactus:"<svg xmlns='http://www.w3.org/2000/svg' width='2048' height='2048' viewBox='0 0 2048 2048'><path fill='currentColor' d='M1330 1203q136 47 245 131t186 196t118 243t41 275h-128q0-164-58-304t-162-244t-243-161t-305-59q-107 0-206 27t-184 76t-155 119t-119 155t-77 185t-27 206H128q0-144 42-275t119-242t186-194t245-133q-78-42-140-102T475 969t-67-157t-24-172q0-133 50-249t137-204T774 50t250-50q133 0 249 50t204 137t137 203t50 250q0 88-23 171t-67 156t-105 133t-139 103M512 640q0 106 40 199t110 162t163 110t199 41t199-40t162-110t110-163t41-199t-40-199t-110-162t-163-110t-199-41t-199 40t-162 110t-110 163t-41 199'/></svg>",
    Aboutus:"<svg xmlns='http://www.w3.org/2000/svg' width='2048' height='2048' viewBox='0 0 2048 2048'><path fill='currentColor' d='M1330 1203q136 47 245 131t186 196t118 243t41 275h-128q0-164-58-304t-162-244t-243-161t-305-59q-107 0-206 27t-184 76t-155 119t-119 155t-77 185t-27 206H128q0-144 42-275t119-242t186-194t245-133q-78-42-140-102T475 969t-67-157t-24-172q0-133 50-249t137-204T774 50t250-50q133 0 249 50t204 137t137 203t50 250q0 88-23 171t-67 156t-105 133t-139 103M512 640q0 106 40 199t110 162t163 110t199 41t199-40t162-110t110-163t41-199t-40-199t-110-162t-163-110t-199-41t-199 40t-162 110t-110 163t-41 199'/></svg>"
};

Mytheme = 
{
    Darkcolour: "#3f768c",
    Lightcolour: "#dfecfs"
};  
 Currentuser = Office365Users.UserProfileV2(User().Email);

 companyname = "Comapany Name";


 Comapnay Logo = '537447158';
