# Icons Installation

## Step 1 : Go to Below Website for Icon Installation Command

```
https://www.hanselman.com/blog/take-your-windows-terminal-and-powershell-to-the-next-level-with-terminal-icons
```

## Step 2 : Open Windows Terminal as Administrator and run the following command

```
Install-Module -Name Terminal-Icons -Repository PSGallery
```

## Step 3 : Go to Yes to All Option in Windows Terminal

```
A
```

## Step 4 : Then add one line to PowerShell Command Profile (edit with "code $profile")

```
Import-Module -Name Terminal-Icons
```
