## Simple Android Service to send clipboard content from your device to Server

This will register a clipboardChange `ClipboardListener` and post any change to 
preconfigured url endpoint (defaults to `http://192.168.0.100/api/v2/clipboard/share`)