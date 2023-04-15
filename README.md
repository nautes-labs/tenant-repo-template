# Tenant Repo Template

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![version](https://img.shields.io/badge/version-v0.2.0-green)]()

Tenant Repo Template 提供了创建租户配置库时所需的一组模板文件，这些模板目前是在[安装程序](https://github.com/nautes-labs/installer)中被使用到。

## 功能简介

Tenant Repo Template 包含以下内容：

- argocd：包含 ArgoCD 的基础安装文件以及一些 Service 的补丁文件。
- argoevents：包含 ArgoEvents 的基础安装文件以及一个默认的 EventBus 资源文件。
- argorollouts：包含 ArgoRollouts 的基础安装文件。
- cert-manager：包含 Cert-Maganer 的基础安装文件以及挂载 SSL 证书公钥的补丁文件。
- dex：包含 Dex 的基础安装文件以及 Ingeress、挂载 SSL 证书公钥等的补丁文件。
- external-secrets：包含挂载 SSL 证书公钥的补丁文件。
- hnc：包含 HNC 的基础安装文件以及自定义命名空间过滤规则的补丁文件。 
- nautes：包含 Nautes 的所有管理组件和资源。
- reloader：包含 Reloader 的基础安装文件。
- tenant：包含租户管理集群自身需要安装的组件的 ArgoCD Application。
- traefik：包含一个默认的 ServersTransport 资源文件。
