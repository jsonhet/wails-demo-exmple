# README

## About

This is the official Wails Svelte template.
- Compile official templates into executable files for easy experience(将官方模板编译为可执行文件方便体验)：
`build/bin/myproject.exe`

## Live Development

To run in live development mode, run `wails dev` in the project directory. This will run a Vite development
server that will provide very fast hot reload of your frontend changes. If you want to develop in a browser
and have access to your Go methods, there is also a dev server that runs on http://localhost:34115. Connect
to this in your browser, and you can call your Go code from devtools.

## Building

To build a redistributable, production mode package, use `wails build`.
