# kolya - 0.2.2

Kolya - React Daemon

Usage:  kolya [-vh] <filepath> [-css | -react] [-oek]

Options: -v - Show version info\n
         -h - Show help menu
         -o - Open file 
         -css | -react - Setup output syntax
         -d - Detect file syntax
         -e - Update file extension
         -k - Keep old file

Examples: kolya style.js -css -o
          kolya style.css -react -oek
          kolya -v
