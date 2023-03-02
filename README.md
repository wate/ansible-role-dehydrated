dehydrated
=================

Setup dehydrated

OS Platform
-----------------

### Debian

- bullseye
- buster

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `dehydrated_cfg`

dehydratedの設定

### `dehydrated_with_lexicon`

lexiconもインストールするか否か

### `dehydrated_lexicon_packages`

インストールするlexicon関連パッケージ

### `dehydrated_domains`

dehydratedで管理するドメインの設定

### `dehydrated_auto_execute`

dehydratedインストール時に実行するか否か

### `dehydrated_cron`

自動更新処理の実行時間の設定

### `dehydrated_hook_initialize`

dehydrated実行時のフック設定(initialize)

### `dehydrated_hook_startup`

dehydrated実行時のフック設定(startup)

### `dehydrated_hook_deploy_challenge`

dehydrated実行時のフック設定(deploy challenge)

### `dehydrated_hook_clean_challenge`

dehydrated実行時のフック設定(clean challenge)

### `dehydrated_hook_sync_cert`

dehydrated実行時のフック設定(sync cert)

### `dehydrated_hook_deploy_cert`

dehydrated実行時のフック設定(deploy cert)

### `dehydrated_hook_deploy_ocsp`

dehydrated実行時のフック設定(deploy ocsp)

### `dehydrated_hook_unchanged_cert`

dehydrated実行時のフック設定(unchanged cert)

### `dehydrated_hook_invalid_challenge`

dehydrated実行時のフック設定(invalid challenge)

### `dehydrated_hook_request_failure`

dehydrated実行時のフック設定(request failure)

### `dehydrated_hook_generate_csr`

dehydrated実行時のフック設定(generate csr)

### `dehydrated_hook_exit`

dehydrated実行時のフック設定(exit)

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: dehydrated
```

License
--------------

Apache License 2.0
