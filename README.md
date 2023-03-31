<div align="center">
<h2><img src="https://slackmojis.com/emojis/5584-deployparrot/download" width="30"/> Hi I am
<br>
░░▀ █▀▀▀ █▀▀▄ █▀▀█ █▀▀ ░▀░ █▀▀█<br>
░░█ █░▀█ █░░█ █▄▄█ █░░ ▀█▀ █░░█<br>
█▄█ ▀▀▀▀ ▀░░▀ ▀░░▀ ▀▀▀ ▀▀▀ ▀▀▀▀</h2>


[![Linkedin: jgnacio](https://img.shields.io/badge/-jgnacio-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/jgnacio-p-singh/)](https://www.linkedin.com/in/jgnaciogomez/)
![GitHub followers](https://img.shields.io/github/followers/jgnacio?label=Follow&style=social)
![](https://komarev.com/ghpvc/?username=jgnacio&style=for-the-badge&color=red)
</div>

<div align="center">
 
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Lua](https://img.shields.io/badge/Lua-0078d7.svg?style=for-the-badge&logo=Lua&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Opengl](https://img.shields.io/badge/Opengl-FFFFFF?style=for-the-badge&logo=opengl&logoColor=Blue)
<br />
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Talwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
<br />
![GNU Bash](https://img.shields.io/badge/GNU%20Bash-4EAA25?style=for-the-badge&logo=GNU%20Bash&logoColor=white)
![Neovim](https://img.shields.io/badge/NeoVim-%2357A143.svg?&style=for-the-badge&logo=neovim&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)


</div>

<img src="https://slackmojis.com/emojis/7421-typingcat/download" width="50"> A little more about me...  

```c
#include <stdio.h>
#include <stdlib.h>

struct developer {
    char *name;
    char *education;
    char *skills;
    char *interests;
    char *misc;
};

void free_developer(struct developer *d);

int main() {
    struct developer jgnacio;

    jgnacio.name = malloc(16 * sizeof(char));
    if (jgnacio.name == NULL) {
        printf("Error: failed to allocate memory for name.\n");
        return 1;
    }
    strcpy(jgnacio.name, "Ignacio Gómez");

    jgnacio.education = malloc(58 * sizeof(char));
    if (jgnacio.education == NULL) {
        printf("Error: failed to allocate memory for education.\n");
        free_developer(&jgnacio);
        return 1;
    }
    strcpy(jgnacio.education, "I am a software engineering student at Holberton School.");

    jgnacio.skills = malloc(16 * sizeof(char));
    if (jgnacio.skills == NULL) {
        printf("Error: failed to allocate memory for skills.\n");
        free_developer(&jgnacio);
        return 1;
    }
    strcpy(jgnacio.skills, "C, Python, Lua");

    jgnacio.interests = malloc(102 * sizeof(char));
    if (jgnacio.interests == NULL) {
        printf("Error: failed to allocate memory for interests.\n");
        free_developer(&jgnacio);
        return 1;
    }
    strcpy(jgnacio.interests, "Keeping up with the latest trends in the technology industry and exploring new programming projects.");

    jgnacio.misc = malloc(43 * sizeof(char));
    if (jgnacio.misc == NULL) {
        printf("Error: failed to allocate memory for misc.\n");
        free_developer(&jgnacio);
        return 1;
    }
    strcpy(jgnacio.misc, "opengl, moderngl, nextjs, reactjs, prisma");

    printf("Hi, my name is %s and %s\n", jgnacio.name, jgnacio.education);
    printf("Most programming languages I use: %s\n", jgnacio.skills);
    printf("My interests include: %s\n", jgnacio.interests);
    printf("Miscellaneous skills: %s\n", jgnacio.misc);

    free_developer(&jgnacio);

    return 0;
}

void free_developer(struct developer *d) {
    free(d->name);
    free(d->education);
    free(d->skills);
    free(d->interests);
    free(d->misc);
}
```
<h2 align="center">  GitHub stats </h2>
 <br />
<p align="center">
 <img src="https://github-readme-stats.vercel.app/api?username=jgnacio&show_icons=true&count_private=true&theme=onedark&hide_border=true&hide=issues,contribs&bg_color=00000000"  alt="jgnacio" />
 <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jgnacio&layout=compact&hide_border=true&theme=onedark&bg_color=00000000&langs_count=6&hide=jupyter%20notebook,tex,css,php" alt="jgnacio" />
 <img src="https://github-readme-streak-stats.herokuapp.com?user=jgnacio&theme=onedark&hide_border=true&background=FFFFFF00" alt="jgnacio" />
</p>
