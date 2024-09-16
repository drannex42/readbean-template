# Redbean Templates

Just a simple scaffolding and development cycle for Redbean. Currently only supports bash and taskfile, but will support others, eventually. 

Pretty simple: 

run `task` and it will: 
- create the project structure
- download all related redbean utilities
- copy all files from 'src' into the redbean project folder (rewriting from a fresh version everytime that is cached). 
- start the redbean server

other commands: download, add (adds all files from src), start, and clean (removes all created files and folders). 

Inspired by the [Makefile of @ProducerMatt](https://github.com/ProducerMatt/redbean-template). Created this one because I wanted a `/src/` folder and ability to start fresh quickly. 
