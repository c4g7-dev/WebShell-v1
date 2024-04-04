# [WebShell | Terminal Portfolio Website](https://www.c4g7.com/)

<div align="center">
  <img alt="banner" src="https://raw.githubusercontent.com/c4g7-dev/webshell-v1/main/res/banner.png">
</div>

![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

Create your own terminal styled website! Check out [term.nasan.dev](https://term.nasan.dev/) for an example.

## Features
* **[Tab]** for auto completion.
* **[Esc]** to clear the input line.
* **[↑][↓]** to scroll through your command history.

## ???
<div align="center">
  <img alt="banner" src="https://raw.githubusercontent.com/nasan016/webshell/main/res/secret.png">
</div>
How did we get here?

## Configuration

Most of the configuration is done in the `config.json` file.

```json
{
  "ascii": [
    "██████╗ ██╗   ██╗ ██████╗",
    "██╔══██╗██║   ██║██╔════╝",
    "██║  ██║██║   ██║██║  ███╗",
    "██║  ██║██║   ██║██║   ██║",
    "██████╔╝╚██████╔╝╚██████╔╝",
    "╚═════╝  ╚═════╝  ╚═════╝",
  ],
  "title": "c4g7's Terminal",
  "username": "guest",
  "hostname": "c4g7.com",
  "password": "squirrel",
  "repoLink": "https://github.com/c4g7-dev/webshell-v1",
  "social": {
    "email": "me@c4g7.com",
    "github": "c4g7-dev",
  },
  "aboutGreeting": "My name is c4g7. I have just met you.",
  "projects": [
    [
      "Project Name",
      "Project Description",
      "Project Link"
    ],
    [
      "Another Project Name",
      "Another Project Description",
      "Another Project Link"
    ]
  ],
  "colors": {
      ...
  }
}
```

## Run the Project Locally:

Clone the repository
```shell
git clone https://github.com/c4g7-dev/webshell-v1.git
```
Go to the project directory
```webshell-v1
cd webshell-v1
```
Install the dependencies
```webshell-v1
npm install
```
Start the server
```webshell-v1
npm run dev
```
