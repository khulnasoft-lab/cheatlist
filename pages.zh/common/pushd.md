# pushd

> 将目录放在堆栈上，以便以后访问。
> 另请参阅 `popd` 命令说明，以切换回原始目录。
> 更多信息：<https://www.gnu.org/software/bash/manual/html_node/Directory-Stack-Builtins.html>.

- 切换到目录并将其添加到堆栈上：

`pushd {{directory}}`

- 切换堆栈上的第一个和第二个目录：

`pushd`

- 通过使第 5 个元素成为堆栈的顶部来旋转堆栈：

`pushd +4`
