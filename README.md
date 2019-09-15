# retdec-idaplugin-mac
retdec idaplugin compiled for macOS

Download retdec compiled from https://github.com/avast/retdec

## Install
Copy `*.dylib` files to `/Applications/IDA Pro XX/idabin/plugins`

Modify `retdec-config.json` file in `~/.idapro`

```
retdec-config.json
{
	"decompilerPyPath" : "/Users/XXXX/Downloads/retdec/bin/retdec-decompiler.py",
	"pythonInterpreterArgs" : "",
	"pythonInterpreterPath" : "/usr/local/bin/python3"
}
```
