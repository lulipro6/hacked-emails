# hacked-emails

A command line [hacked-email](hadiali12@gmail.com) utility

## Installation

#### Binaries

- **darwin** [386](https://github.com/madhuakula/hacked-emails/releases/download/0.0.1/hacked-emails-darwin-386) / [amd64](https://github.com/madhuakula/hacked-emails/releases/download/0.0.1/hacked-emails-darwin-amd64)
- **linux** [386](https://github.com/madhuakula/hacked-emails/releases/download/0.0.1/hacked-emails-linux-386) / [amd64](https://github.com/madhuakula/hacked-emails/releases/download/0.0.1/hacked-emails-linux-amd64)
- **windows** [386](https://github.com/madhuakula/hacked-emails/releases/download/0.0.1/hacked-emails-windows-386) / [amd64](https://github.com/madhuakula/hacked-emails/releases/download/0.0.1/hacked-emails-windows-amd64)

#### Via Go

```bash
$ go get github.com/madhuakula/hacked-emails
```

## Usage

```bash
$ hacked-emails email@domain.com

email@domain.com email found in 4 results

Adobe Users : (2013-09-30T00:00:00+00:00)
 <https://hacked-emails.com/leak/anon-adobecre>

Linkedin : (2011-12-31T00:00:00+00:00)
 <https://hacked-emails.com/leak/anon-linkedin2012v2tx>

Unknown Database FR : (2016-07-19T00:00:00+00:00)
 <https://hacked-emails.com/leak/anon-unknowndumpsemailp>

000webhost.com : (2015-10-26T00:00:00+00:00)
 <https://hacked-emails.com/leak/anon-000webho>
```

## To-Do

- [X] Binary builds for different platforms
- [ ] Automated binary builds
- [ ] Arguments validation (email)
- [ ] Status checks
- [ ] Different outputs

## Thanks

- Inspired by Jessfraz [https://github.com/jessfraz/udict](https://github.com/jessfraz/udict)
