# RWD-Sass
Proyecto en RWD , utilizando el compilador live de VS


Configuracion del VS Code para la compilacion de Sass: 

{
    "editor.minimap.enabled": false,
    "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
    "liveSassCompile.settings.formats":[
    
        {
            "format": "expanded",
            "extensionName": ".css",
            "savePath": "~/../css/"
        },
       
       
        // More Complex
        {
            "format": "compressed",
            "extensionName": ".min.css",
            "savePath": "~/../css/"
        }
    ]
    ,
    "liveSassCompile.settings.generateMap": false,
    "liveServer.settings.donotShowInfoMsg": true,
    "editor.wordWrap": "on",
}
