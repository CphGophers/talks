This repository holds various Copenhagen Gophers talks that may be viewed with the present tool.

To install the present tool, use go get:

	go get golang.org/x/tools/cmd/present

To deploy these talks to App Engine, copy the tools/cmd/present directory to
the root of this repository and run:

	appcfg.py update -A your-app-id -V your-app-version /path/to/talks

To submit changes to this repository, see http://golang.org/doc/contribute.html.

# LICENSE

The standard license is Creative Commons Attribution 4.0 [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
However individual talks may have a separate license. In that case a separate LICENSE file will be placed in
the content folder of the talk.