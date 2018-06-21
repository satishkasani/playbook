- host: all
  tasks:
  - name: to update
    apt: name=apache2 state=latest
