# Aleksei Kostarev 

## Contact Information
- **Location:** Russia, Saint Petersburg
- **Email:** \_BIOSS\_@mail.ru
- **GitHub:** [GitHub Profile](https://github.com/imBIOSS)
## About Me
I am a dedicated System Administrator with a passion for technology and problem-solving.
With a solid background in managing and maintaining IT infrastructure,
I ensure that systems run smoothly and efficiently.
I have also pursued studies in programming, which has sparked a keen interest in further developing my coding skills.
My goal is to expand my knowledge in programming to enhance my capabilities and drive my career growth in the tech industry.

## Skills
- **HTML** 
- **Go**
- **Python**
- **Basic Programming Knowledge**  

## Code Example
 ```
package main
import (
	"bufio"
	"fmt"
	"os"
	//"strings"
	"unicode"
)

func main() {

	text, _ := bufio.NewReader(os.Stdin).ReadString('\n')
	//text = strings.TrimSuffix(text, "\n")
	textRunes := []rune(text)

	if unicode.IsUpper(textRunes[0]) && string(textRunes[len(textRunes)-1]) == "." {
		fmt.Print("Right")
	} else {
		fmt.Print("Wrong")
	}

}
```
## Experience
- **System Administration**
- **Network Management**
- **Troubleshooting and Support**

## Education
**University:** Kuban State University,  Computer Science with Software Engineering

## Languages
- **Studying**
