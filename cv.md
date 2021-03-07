**Name:** Egor Kuzmichev<br>
**Email address:** kuzmichev_2497@mail.ru<br>
**Objective:** systematization and consolidation of available frontend development skills, gaining new knowledges<br>
**Education:**<br>
 &nbsp;&nbsp;**Bachelory:** Emperor Alexander I St. Peterburg State Transport University, 2016-2020<br>
 &nbsp;&nbsp;**Mastery:** Peter the Great St.Petersburg Polytechnic University, 2020 - p.t.<br>
**Skills:**<br>
  &nbsp;&nbsp;**Programming languages:** <br>
    &nbsp;&nbsp;&nbsp;&nbsp;***Studied:*** C/C++, Java, Matlab<br>
    &nbsp;&nbsp;&nbsp;&nbsp;***Had a little practice:*** Javascript, Typescipt<br>
  &nbsp;&nbsp;**Frameworks:** Angular<br>
  &nbsp;&nbsp;**Development tools:** Visual Studio, VS Code, Intellij Idea<br>
**Code Example:**<br>
```javascript
        function shifter(s){
          let res = [];
          let shortSymbols = ['H', 'I', 'N', 'O', 'S', 'X', 'Z', 'W' , 'M'];
          if (s=="")
            return 0;
          let arr = s.split(' ');
          for(let i = 0;i<arr.length; i++)
            for(let j = 0; j <= arr[i].length;j++){
              if(j==arr[i].length)
                if(res.indexOf(arr[i])==-1)
                  res.push(arr[i]);
              if(shortSymbols.indexOf(arr[i][j])==-1)
                break;
            }
          return res.length;
        }
```
**Projects:** Development of a system for monitoring and controlling the parameters of a diesel locomotive (Typescript/Angular)<br>
**English Level:** A2+ by EPAM Training Center's test
