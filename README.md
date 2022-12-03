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

### `dehydrated_cfg`

dehydratedの設定

### `dehydrated_with_lexicon`

lexiconのインストールの可否

### `dehydrated_lexicon_packages`

インストールするlexicon関連パッケージ

### `dehydrated_domains`

dehydratedのドメイン設定

### `dehydrated_auto_execute`

dehydratedインストール時に実行する

### `dehydrated_cron`

自動更新処理の実行時間の設定

### `dehydrated_hook_initialize`

フック設定(initialize)

### `dehydrated_hook_startup`

フック設定(startup)

### `dehydrated_hook_deploy_challenge`

フック設定(deploy challenge)

### `dehydrated_hook_clean_challenge`

フック設定(clean challenge)

### `dehydrated_hook_sync_cert`

フック設定(sync cert)

### `dehydrated_hook_deploy_cert`

フック設定(deploy cert)

### `dehydrated_hook_deploy_ocsp`

フック設定(deploy ocsp)

### `dehydrated_hook_unchanged_cert`

フック設定(unchanged cert)

### `dehydrated_hook_invalid_challenge`

フック設定(invalid challenge)

### `dehydrated_hook_request_failure`

フック設定(request failure)

### `dehydrated_hook_generate_csr`

フック設定(generate csr)

### `dehydrated_hook_exit`

フック設定(exit)

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
