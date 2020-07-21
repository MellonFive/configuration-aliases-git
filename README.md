# Aliases no git que pode ser úteis

[alias]
  ci = commit
  <br>
  co = checkout
  <br>
  cm = checkout master(Para voltar a branch master)
  <br>
  cb = checkout -b
  <br>
  st = status -sb
  <br>
  sf = show --name-only
  <br>
  lg = log --pretty=format:'%Cred%h%Creset %C(bold)%cr%Creset %Cgreen<%an>%Creset %s' --max-count=30
  <br>
  incoming = !(git fetch --quiet && git log --pretty=format:'%C(yellow)%h %C(white)- %C(red)%an %C(white)- %C(cyan)%d%Creset %s %C(white)- %ar%Creset' ..@{u})
  <br>
  outgoing = !(git fetch --quiet && git log --pretty=format:'%C(yellow)%h %C(white)- %C(red)%an %C(white)- %C(cyan)%d%Creset %s %C(white)- %ar%Creset' @{u}..)
  <br>
  unstage = reset HEAD --
  <br>
  undo = checkout --
  <br>
  rollback = reset --soft HEAD~1
