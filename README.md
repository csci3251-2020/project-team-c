# CSCI 3251 PROJECT MILESTONE 3

### Introduction
- **Task 1 (Starting issue)**  
Creating a new issue for each of them and write down some instructions on how to do the task.

- **Task 2 (Project board)**  
Setting up automation. Organization owners and members can configure workflows on an organization-wide project board. Frequently check the **Issue** and **Pull requests** tabs to make sure with our project board, and reminde people to tag their pull requests.

- **Task 3 (Set up readme.md)**  
Setting up 3 headings: **Introduction**, **Code** and **Contributors** and write a short summary that my team will do according to the taks.

- **Task 4 (Show your team to the internet)**  
Updating this web page: `https://csci3251-2020.github.io/project-team-c/`. Go to **`readme.md`** and use a loop in the folder `_stu` to go through all files under **Contributors**. You should show image, user, name and content. For the details, you can go to `issues`.

- **Task 5 (Keep checking)**  
Very simple task. Just keep checking as a leader. Keep the community going.

- **Task 6 (Write C code)**  
 In **`code.c`**, write a piece of very simple C code whatever you like. 

- **Task 7 (Get a status badge)**  
Updating this web page: `https://csci3251-2020.github.io/project-team-c/`. Edit **`readme.md`**, and include the code from `code.c`. You can find the code in Task 6. And also you should insert the resultant image by using markdown under the code. For the details,  you can go to `issues`.

- **Task 8 (Promote our repo)**  
Clicking our team's page here `https://csci3251-2020.github.io/project-team-c/`. Edit and include the repo last updated time using `site.time` under the web page. Going to the public repo of **`csci3251-2020.github.io`** and edit the file, add a link of our team. Finally, send a request for review from @chuckjee.

**That's all about the project!!!**  



### Code  



### Contributors  

<table>
  <tbody>
    {% for contributor in site.stu %}
      <tr>
        <td><img src="{{ contributor.image }}" width="50" height="50" /></td>
        <td>
          <a href="https://github.com/{{ contributor.user }}">@{{ contributor.user }}</a> ({{ contributor.name }})<br>
          {{ contributor.content | markdownify }}
        </td>
      </tr>
    {% endfor %}
  </tbody>
</table>
 
