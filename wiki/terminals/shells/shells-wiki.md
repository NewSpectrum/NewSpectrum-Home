# `PS> Get-Help 'shells'`

__Fun Fact:__ I originally came up with that title on a whim as a joke, not expecting it to *actually* yield anything useful (if it yielded anything at all). Turns out it *actually* produces several __[Cmdlets] & [HelpFiles]__ that are perfect for __Getting Familiar with PowerShell__.

But to make the output a little more... helpful, you should enter this:

```powershell
Get-Help 'shells' |
Sort-Object -Property Category, Name |
Format-Table -AutoSize -Wrap -GroupBy Category -Property Name, Category, Synopsis
```

Don't worry, we'll break down that whole process in __[PowerShell Basics]__

<br />

---

<br />

# What *is* a Shell? :thinking:

<img id="Bash Icon"
	 src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Bash_Logo_Colored.svg"
	 alt="Bash: The 'Bourne Again Shell'"
	 width="15%" height="auto"/> 
<img id="PowerShell 7 Icon"
	 src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Bash_Logo_Colored.svg"
	 alt="Bash: The 'Bourne Again Shell'"
	 width="15%" height="auto"/> 