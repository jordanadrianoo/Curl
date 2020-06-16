# CURL

CURL is a computer software project providing a library and command-line tool for transferring data using various network protocols.

## Requirements

- Git
- CURL tool installed

## Example Command

```
curl -L -X -G http://example_website/home/examples/download-this -O -u frank:password1
```
 
This command steps are:

- **-L** find the location of a file
- **-X** Request 
- **-G** Go get
- **URL** from the URL
- **-O** output data with the orginal file name
- **-u** use the credentials username:password

## CURL Commands

|                commands                      |                   Explanation                              |
|----------------------------------------------|------------------------------------------------------------|
| curl --help                                  |    Shows the curl help list                                |
| curl <**URL**>                               |    This will return the HTML of the URL choosen.           |
| curl -i <**URL**>                            |    This will return the HTML with header content           |
| curl -I <**URL**>                            |    This will return only the header content                |

## CURL Tools
|                Tool Shortcut                 |                   Explanation                              |
|----------------------------------------------|------------------------------------------------------------|
| -i                                           |    To include the header and body of the URL               |
| -I                                           |    To only include the Header and the Body                 |
| -G                                           |    To go get data from the URL provided                    |
| -X                                           |    To make a request from the URL                          |
| -u <**usr:password**>                        |    To enter the username and password                      |
| -o <**example.file**>                        |    To output the downloaded data into a new file           |
| -O                                           |    To output the data with the files orginial name         |
| -L                                           |    To find the location of the file                        |

## Sources  

[CURL How to Guide](https://curl.haxx.se/)

[CURL Doccumentation](https://www.mit.edu/afs.new/sipb/user/ssen/src/curl-7.11.1/docs/curl.html)
