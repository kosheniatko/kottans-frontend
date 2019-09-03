## Linux CLI, and HTTP

- [x] Learn the Command Line (Codeacademy)
- [x] HTTP: The Protocol Every Web Developer Must Know - Part 1
- [x] HTTP: The Protocol Every Web Developer Must Know - Part 2
- [x] Describe your impressions about learned materials.
- [x] Extra Materials
- [ ] Optional

**CLI** - Command Line Interface
**GUI** - Graphic User Interface

**HTTP** stands for Hypertext Transfer Protocol. 
In-depth coverage -> RFC.
HTTP communication takes place over *TCP/IP*. The default port: **80** (Other ports could be used).
Communication between a host and a client occurs, via a **request/response pair**.
**URL** - Uniform resource locator.
```
http://www.domain.com:1234/path/to/resource?a=b&x=y
  |             |       |         |            |
protocol       host    port    resource      query
```
- GET: fetch an existing resource. The URL contains all the necessary information the server needs to locate and return the resource.
- POST: create a new resource. POST requests usually carry a payload that specifies the data for the new resource.
- PUT: update an existing resource. The payload may contain the updated data for the resource.
- DELETE: delete an existing resource.
Request -> URL + VERB (GET, POST, etc.)
Response -> Status Code + Message Body.

Content of response or request:
```
message = <start-line>
          *(<message-header>)
          CRLF
          [<message-body>]

<start-line> = Request-Line | Status-Line 
<message-header> = Field-Name ':' Field-Value
```
### Configuring Linux Web Servers (Udacity course)

#### Intro to Linux

*etc* - directory with configuration files.
*var* - variable files, files that might grow in the future.
*bin* - executable binaries stored.
*sbin* - similar to bin directory, but commands only for root user.
*lib* - libraries.

#### Linux Security

The Rule of Least Privilege - the program should have permission only for doing it's job, not more.

`sudo adduser ...` - add new user.
`sudo passwd -e [USER]` - make user password expired.

**Octal permissions:**

`r = 4, w = 2, x = 1`

### Networking for Web Developers (Udacity course)



### (NEW!) Big amount of different codes.
- 1xx: Informational Messages
- 2xx: Successful
- 3xx: Redirection
- 4xx: Client Error
- 5xx: Server Error
### (SURPRISED!)
Custom headers can also be created and sent by the client; they will be treated as entity headers by the HTTP protocol.
*Everything is a file* describes one of the defining features of Unix.
`*nix` systems also contain:
**Hard Link** — additional name for existing file.
**Symbolic link** — something like label on Windows systems.
**Socket** — internal endpoint for sending or receiving data within a node on a computer network.

### (USE IN THE FUTURE!)
Tools for View HTTP Traffic:
- Chrome/Webkit inspector
- Fiddler (Windows)
- Charles Proxy (OSX)
Command line:
- curl 
- tshark
- tcpdump

ZHS is cool shell with many usefull features.

`take` - command for creating directory and diving into it.

*trash* plugin -> safer alternative to `rm`.

### Screenshots / Completed courses

![Command Line](img/CommandLine[Codeacademy].png)
![Command Line](img/CLI[Hexlet].png)