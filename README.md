---

## About Me

```go
package main

import "fmt"

type Developer struct {
    Name     string   `json:"name"`
    Title    string   `json:"title"`
    Location string   `json:"location"`
    Focus    []string `json:"focus"`
}

func main() {
    vaibhav := Developer{
        Name:     "Divya Vaibhav",
        Title:    "Full-Stack Developer & AI Enthusiast",
        Location: "India 🇮🇳",
        Focus:    []string{"Go", "TypeScript", "AI/ML", "Cloud"},
    }

    fmt.Printf("%s | %s | %s\n", vaibhav.Name, vaibhav.Title, vaibhav.Location)
}
```


## Tech Stack
<div align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,go,c,python" />
</div>

<div align="center">
  <img src="https://skillicons.dev/icons?i=svelte,nextjs,express,astro,nuxt" />
</div>

<div align="center">
  <img src="https://skillicons.dev/icons?i=sqlite,redis,postgres,mongodb,dynamodb" />
</div>

<div align="center">
  <img src="https://skillicons.dev/icons?i=docker,git,linux,aws,github" />
</div>

<div align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,bun" />
</div>
