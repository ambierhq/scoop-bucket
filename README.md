# ambierhq/scoop-bucket

[Scoop](https://scoop.sh) bucket for [Ambier](https://ambierhq.com) open-source tools. It currently holds one app,
[skigard](https://github.com/ambierhq/skigard), a lockfile and review gate for agent skills.

```powershell
scoop bucket add ambierhq https://github.com/ambierhq/scoop-bucket
scoop install skigard
```

The manifest is updated by the skigard release workflow. It has not been tested by hand on Windows yet (CI covers the Windows binary).
`skigard approve` needs a real console and refuses without one.
