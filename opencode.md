
https://opencode.ai/docs/keybinds/

"keybinds": {
  "leader": "ctrl+x",
  "app_exit": "ctrl+d, <leader>q"
}

### 🎯 核心解决方案：修改正确的配置文件

1.  **检查配置文件**：用文本编辑器打开 `~/.config/opencode/tui.json`。如果文件不存在，可以新建一个。
2.  **修改 `app_exit` 快捷键**：在文件中找到或添加 `keybinds` 部分，将 `app_exit` 的值修改为你期望的快捷键。以下是移除了 `ctrl+c` 的配置示例：
    ```json
    {
      "$schema": "https://opencode.ai/config.json",
      "keybinds": {
        "app_exit": "ctrl+d, <leader>q"
      }
    }
    ```
    > 注意：`<leader>` 键默认是 `ctrl+x`，所以 `ctrl+x q` 也是一个有效的退出快捷键。




