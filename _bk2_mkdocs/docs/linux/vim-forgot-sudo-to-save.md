# vim forgot to sudo

Forgot to `sudo vim` before opening the file and now cannot save the file within vim.

Here is the solution:

`:w !sudo tee %`

- source <https://intelligentbee.com/2017/06/08/save-file-vim-forgetting-use-sudo/>