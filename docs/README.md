## Why?
 
We are interested in your skills as a developer. As part of our assessment, we want to see your code.
 
## Instructions
 
In this archive, you'll find two files, Workbook2.csv and Workbook2.prn, which need to be displayed by the software you deliver in HTML format.
 
This repository is created specially for you, so you can push anything you like. Please update this README to provide instructions, notes and/or comments for us.
 
## The Constraints
 
The solution has to be implemented in Go and we expect this to be done within a week.
 
## Questions?
 
If you have any questions please ask DL-eCG-icas-comaas-assessment@ebay.com.
 
## Finished?
 
Please send an email to DL-eCG-icas-comaas-assessment@ebay.com to let us know you're done.
 
Have fun!

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
```javascript
> go run file_page.go
```
An output.html file will be generated. Simply click on the file to view display in html
```javascript
> go test
```

For resolving missing package for text/encoding, please execute this command
```javascript
go get "golang.org/x/text/encoding"
```

###  - Improvement
 To improve on the software produced:
* I would provide a JSON config file as configuration to where files will be loaded from
* I wanted to make the config for the application as easy as possible, so I decided to use a JSON config file that would get read on program start up,
   and used throughout the lifecycle. 
   The ***config.json*** file that  has the following format:
   ```javascript
   {"directory":"", output:"", "stylesheets":""} 
   ```

* Provide more tests and data for performance measurement
 
 
Copyright (C) 1995 - 2017 by eBay Inc. All rights reserved.
