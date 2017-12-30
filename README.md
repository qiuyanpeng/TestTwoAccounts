# TestTwoAccounts

## related links
- https://code.tutsplus.com/tutorials/quick-tip-how-to-work-with-github-and-multiple-accounts--net-22574
- https://help.github.com/articles/which-remote-url-should-i-use/
- https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/
- https://help.github.com/articles/working-with-ssh-key-passphrases/
- http://www.cnblogs.com/xjnotxj/p/5845574.html

## Notes

This repo belongs to my personal GitHub account (@qiuyanpeng).

If I clone the repo using HTTPS URL, I can `git push` with my corp account (@qypeng) too,
but I should use the 'access token' instead of password.
It's a little bit more work as I need to enter my username and password/token every time.

If I clone the repo using SSH URL, I need to set up the SSH keys to choose which account to use.

Global git username/email: ~/.gitconfig
Change local repo settings: 

```
git config user.name "one_name"
git config user.email "one_email"
```

