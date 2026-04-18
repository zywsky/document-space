
https://opencode.ai/docs/keybinds/

"keybinds": {
  "leader": "ctrl+x",
  "app_exit": "ctrl+d, <leader>q"
}

**tui配置文件**：用文本编辑器打开 `~/.config/opencode/tui.json`。如果文件不存在，可以新建一个。
    ```json
   {
    "$schema": "https://opencode.ai/tui.json",
    "keybinds": {
      "app_exit": "<leader>q"
    }
  }
```
**opencode.json配置文件**：用文本编辑器打开 `~/.config/opencode/opencode.json`。如果文件不存在，可以新建一个。
    ```json
{
  "$schema": "https://opencode.ai/config.json",
  "permission": "allow",
  "keybinds": {
    "leader": "ctrl+i",
    "app_exit": "<leader>q",
     "command_list": "ctrl+m"
  },
  "provider": {
    "ghcp": {
      "name": "Copilot",
      "options": {
        "baseURL": "http://localhost:4141",
        "apiKey": "dummy"
      },
      "models": {
        "gpt-4.1": {
          "name":"gpt-4.1 Free"
        },
        "claude-sonnet-4-6": {
          "name":"claude-sonnet-4-6"
        }
      }
    }
  }
}
```
        
    




