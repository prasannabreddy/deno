# deno
A new project
package main

import (
	"github.com/ry/deno"
)

func main() {
	deno.Init()
	deno.Eval("deno_main.js", "denoMain()")
	deno.Loop()
}
