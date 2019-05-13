# go-books
Workbook file reader that displays content in html<br>
To demonstrate my skills as a developer using Go language

### The Assignment Submission

<p> The implementaion strategy uses the file extension to determine which strategy to use for reading.<br>
Two(2) Line readers are created within the FilePage object to properly match columns in the input file
. Common functions for parsing, reading, matching and storing are implemented in the object wrapper
to enable proper testing.
</p>

### Running The Code
The codebase consists of 2 go files: **file_page.go** and **file_page_test.go**
* Keep the 2(.prn and .csv) files in the same directory as the file_page.go
* on the terminal, simple invoke:
```java
> go run file_page.go
```
An output.html file will be generated. Simply click on the file to view display in html
```java
> go test
```

For resolving missing package for text/encoding, please execute this command
```java
go get "golang.org/x/text/encoding"
```

### TODO - Improvement
 To improve on the software produced:
* I would provide a JSON config file as configuration to where files will be loaded from
* I wanted to make the config for the application as easy as possible, so I decided to use a JSON config file that would get read on program start up,
   and used throughout the lifecycle. 
   The ***config.json*** file that  has the following format:
   ```javascript
   {"directory":"", output:"", "stylesheets":""} 
   ```

* Provide more tests and data for performance measurement
