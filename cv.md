# Roman Rohozhnikov
## Contacts
* Location: Ukraine
* Phone: +380991405803
* Email: pb-rra@hotmail.com
* GitHub: CryTechno
## About Me
**_I am 21 years old, dedicated worker with excellent time management and computer skills.
I want to use my abilities to successfully fill a vacancy in your company. My friends
I am often praised as a hardworking person and you can count on me to help yours
company to achieve its goals. I use my free time for hobbies and self-development of abilities.
I work diligently, the speed of work depends on what I am working with, I am already good at something
familiar, or with a completely new one_**
## Skills 
* HTML/CSS (SASS|SCSS)
* JavaScript(Native)
* GIT
## Code Example
```
    function checkedLocalStorage(id){
        if(localStorage.getItem('todo')){
            let arr = JSON.parse(localStorage.getItem('todo'));
            arr.forEach(e=>{
                if(e.id == id){
                    if(e.checked){
                        e.checked = false;
                    }
                    else{
                        e.checked = true;
                    }
                }
            });
            localStorage.setItem('todo', JSON.stringify(arr));
            todo = arr;
        }
    }
```
## Work experience
**Completed a pet project like "to do" with local storage**
## Education
* University: National Technical University of Ukraine “Igor Sikorsky Kyiv Polytechnic Institute”
* Courses:
    + Udemy course HTML|CSS 2022 - 100%
    + Udemy course JS Native - 100%
    + Udemy course React - 10%
## Languages
* Ukrainian - native speaker
* Russian - native speaker
* English A2 (B1 in proccess...)
