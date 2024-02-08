## Step 1 : Run the Windows Terminal as Administrator and Run following Command

```
code $profile
```

### Now Close and Reopen the Windows Terminal, if You Face any error then run following command and reopen it :

```
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
```

## Step 2 : Visual Studio Code Will Open, Now Paste the Below Command in it

```
oh-my-posh.exe init pwsh --config | Invoke-Expression
```
