# Ansible Role for ceph-common

## 3.2.0 - TBC

### Major Changes

  - Update LXD test profile for Kubernetes v1.15.0 support
  - Update molecule \>=2.22rc1 for Ansible 2.8.0 support

## 3.1.0 - 2019-06-13

### Major Changes

  - Always include default variables from `vars/main.yml`
  - Always use `become: true` with molecule, especially for vagrant
  - Simplify for openSUSE by `disable_gpg_check: true`
  - Better multinode test cases

## 3.0.0 - 2019-05-28

  - Initial release for Ansible 2.8 or higher
  - Support both Ubuntu 16.04/18.04 or RHEL/CentOS 7 or openSUSE Leap 15
