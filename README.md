### Hi there 👋

```kotlin 
   person("Alejandro Torres") {
      from = Spain
      education = education {
          master = "Computer Science"
          university = "Universidad Politecnica de Madrid, UPM"
      }
      occupation = occupation {
          role = SoftwareEngineer
          at = 47 Degrees
          focusOn = Tech("Back-end and DevOps){
                +"Kotlin" and "Scala" and "Functional Programming"
                +"Reactive architectures"
                +"Kubernetes"
                +"Apache Kafka" and "Event Driven Architectures"
          }
      }
      contact = contactMe {
        linkedIn = "www.linkedin.com/in/alejandro-torres-7670bb80"
        email = "atorresato@gmail.com"
      }
   }

```
