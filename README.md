
 <h1>poware-cli</h1>

It is command line interface that can compile **.ps1** ( powershell script ). you are allowed to develop malware's using this program. use this program by your risk.

This project was created for educational purposes and should not be used in environments without legal authorization.

**support platform**
> windows

<h5>version 1</h5>

> compiling PSscript mode
<h6>command :</h6>

    --scriptfile or -sf     = (required) .ps1 file to build executable file
    --icon or -ico          = (not required) use this icon for this output
    --output or -o          = (not required) specify output file name {default: base name of file}
    --target or -t          = build console or windows application {default: console}

<h6>example :</h6>

    poware-cli -sf <file path> -o <new file directory> -ico <.ico path> -t <con-api or win-api> mode:compiler
    poware-cli mode:compiler -sf c:\file.ps1 -ico c:\photo.ico -t con-api
    poware-cli -sf c:\file.ps1 mode:compiler 

<h6>poware-cli built function</h6>

    print hello world -nnl 
    output: hello world
    -- (-nnl) is nonewline
    
    print hello world -b64enc (base 64 encoded)
    print hello world -b64dec (base 64 decoded)
    
    input ">" or input
    
    -- new ps environment

    $_ARGS -- for executable arguments, the $_ARGS[0] is current program path.



----------

 
    
         
