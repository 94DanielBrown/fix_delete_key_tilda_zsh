# fix_delete_key_tilda_zsh
Fix delete key enters tilda zsh  
  

Get bindkeys with **sed -n 's/^/bindkey /; s/: / /p' /etc/inputrc**  
Find the bindke for delete and add to .zshrc
