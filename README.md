# K-Ansible

全てのノードのパッケージをアップデートする
```bash
uv run ansible-playbook -i hosts.yml update_allnode.yml
```

全てのノードにfail2banをインストールする
```bash
uv run ansible-playbook -i hosts.yml install-fail2ban.yml
```

全てのノードに.vimrcを配置する
```bash
uv run ansible-playbook -i hosts.yml config_vimrc.yml
```

```bash
uv run ansible-playbook -i hosts.yml config_ed25519.yml
```
