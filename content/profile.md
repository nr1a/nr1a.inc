+++
title = 'Profile'
date = 2023-09-12T01:39:15+09:00
draft = false
author = "milkland"
+++

```go
package main

import (
    "fmt"
    "time"
)

func main() {
    fmt.Println("Hello, I am nr1a/meru.")
    fmt.Println("I am", time.Now().Year() - 2006, "years old.")
    fmt.Println("I am a security engineer.")

    fmt.Println("My skills include:")
    skills := map[string]string{
        "Go":     "Go programming language",
        "C++":    "C++ programming language",
        "Assembly": "Assembly language",
        "Python":  "Python programming language",
    }
    for skill := range skills {
        fmt.Println("*", skill)
    }

    fmt.Println("I have the following certifications:")
    certifications := []string{
        "ITパスポート (Information Technology Passport)",
        "情報処理安全確保支援士 (Information Security Assurance Specialist)",
        "Cisco Certified Network Professional",
    }
    for _, certification := range certifications {
        fmt.Println("*", certification)
    }

    fmt.Println("I am passionate about finding and fixing security vulnerabilities.")
}
```
