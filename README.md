<h1><a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&pause=500&multiline=true&repeat=false&width=435&lines=Shalom+%F0%9F%91%8B%2C;It's+BIEN+GLITCH" alt="Typing SVG" /></a></h1>

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

```php
<?php
namespace Bien\Glitch;

use Developer\Experience\Senior;

class Bio {
    private string $name = 'Bien Nwinate';
    private string $default_stack = 'LAMP';

    private ?string $bio;

    public function __construct (public string $init = 'Hello', public string $category = 'Full-Stack Web Dev') {
        $this->bio = "{$this->init}<br/>";
    }

    public function initName(?string $name = NULL):static {
        $this->bio .= "<br/>Name: {$name ?? $this->name}";
        return $this;
    }

    public function initCategory(?string $category = NULL):static {
        $this->bio .= "<br/>Category: {$category ?? $this->category}";
        return $this;
    }

    public function initStack(?string $stack = NULL):static {
        $this->bio .= "<br/>Stack: {$stack ?? $this->default_stack}";
        return $this;
    }

    public function write():string {
        return $this->bio;
    }
}

$bio = new Bio('Hello there 😊,');

echo $bio->initName()
    ->initCategory()
    ->initStack()
    ->write();
```
  
<h2>🚀 &nbsp;Languages</h2>

  ###### Original:
  <p align="left">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" width="45" height="45"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" width="45" height="45"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" width="45" height="45"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" width="45" height="45"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sass/sass-original.svg" width="45" height="45"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/php/php-original.svg" alt="php" width="45" height="45"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original-wordmark.svg" width="45" height="45"/>
  </p>

  ###### Framework:
  <p align="left">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jquery/jquery-plain-wordmark.svg" width="45" height="45"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/laravel/laravel-original.svg" width="45" height="45"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/codeigniter/codeigniter-plain-wordmark.svg" width="45" height="45"/>
  </p>
<br/>

<h2>⚙️ &nbsp;Tools</h2>
<p align="left">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/intellij/intellij-original.svg" alt="intellij" width="45" height="45"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/phpstorm/phpstorm-original.svg" alt="phpstorm" width="45" height="45"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" alt="vscode" width="45" height="45"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/composer/composer-original.svg" alt="composer" width="45" height="45"/>      
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/npm/npm-original-wordmark.svg" alt="npm" width="45" height="45"/>
</p>
<br/>

<p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bien-Glitch&theme=midnight-purple&langs_count=6&layout=donut" style="height:200px" align="center" /></a>
    <a href="https://github.com/anuraghazra/github-readme-stats"><img src="https://github-readme-stats.vercel.app/api?username=Bien-Glitch&theme=vision-friendly-dark&show_icons=true" style="height:200px" align="center" alt="GitHub Contributions"/></a>
</p>

<p align="center">
    <a href="https://git.io/streak-stats"><img src="https://streak-stats.demolab.com?user=Bien-Glitch&theme=highcontrast&border_radius=5&mode=weekly" style="height:200px" align="center" style="width:100%" alt="GitHub Streak" /></a>
</p>

<!--
**Bien-Glitch/Bien-Glitch** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
