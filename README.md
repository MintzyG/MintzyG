
### Hi I'm Eric Hoffmann, welcome to my GitHub
<html lang="pt-br">
  <head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="style.css">
  </head>
  <body>

``` go
package main
    
import "fmt"

type Me struct {

    Name string
    PreferredName string
    Age int
    Pronouns string
    PreferredPronouns string
    Hobbies []string
    
}

func (m *Me) String() string {

    fmt.Sprintf("Hi, my name is %v and I am %v years old \n" + 
    "But please call me by %v and use %v if its not a problem", m.Name, m.Age, m.PreferredName, m.PreferredPronouns)
    
}

func main() {

    Sophia := Me{
        Name: "Eric"
        PreferredName: "Sophia"
        Age: 20
        Pronouns: "Any/All"
        PreferredPronouns: "She/Her"
    }
    
}
```

- 🌱 I’m currently learning: GOlang 

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img width="50%" align="center" src="https://github-readme-stats.vercel.app/api?username=MintzyG&show_icons=true&theme=midnight-purple&include_all_commits=true&count_private=true">
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img width="50%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MintzyG&layout=compact&langs_count=9&theme=midnight-purple">
</a>


<!--
**MintzyG/MintzyG** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
  </body>
</html>
