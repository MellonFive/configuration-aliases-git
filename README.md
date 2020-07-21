# Aliases no git que pode ser úteis

[alias]
  ci = commit
  <br>
  <br>
  co = checkout
  <br>
  <br>
  cm = checkout master(Para voltar a branch master)
  <br>
  <br>
  cb = checkout -b
  <br>
  <br>
  st = status -sb
  <br>
  <br>
  sf = show --name-only
  <br>
  <br>
  lg = log --pretty=format:'%Cred%h%Creset %C(bold)%cr%Creset %Cgreen<%an>%Creset %s' --max-count=30
  <br>
  <br>
  incoming = !(git fetch --quiet && git log --pretty=format:'%C(yellow)%h %C(white)- %C(red)%an %C(white)- %C(cyan)%d%Creset %s %C(white)- %ar%Creset' ..@{u})
  <br>
  <br>
  outgoing = !(git fetch --quiet && git log --pretty=format:'%C(yellow)%h %C(white)- %C(red)%an %C(white)- %C(cyan)%d%Creset %s %C(white)- %ar%Creset' @{u}..)
  <br>
  <br>
  unstage = reset HEAD --
  <br>
  <br>
  undo = checkout --
  <br>
  <br>
  rollback = reset --soft HEAD~1
