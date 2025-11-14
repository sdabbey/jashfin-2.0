# JASHFIN Enterprise - 2.0

.vscode settings
- {
    "liveSassCompile.settings.formats": [
        {
            "format": "expanded",
            "extensionName": ".css",
            "savePath": "/assets/css"
        },
        {
            "format": "compressed",
            "extensionName": ".min.css",
            "savePath": "/assets/css"
        }
    ],
    "liveSassCompile.settings.generateMap": true,
    "liveSassCompile.settings.includeItems": [
        "/assets/scss/**/*.scss"
    ],
    "liveSassCompile.settings.excludeItems": [
        "**/node_modules/**",
        ".vscode/**"
    ]
}