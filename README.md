# ldap-auth-stack

## Overview
A comprehensive directory and authentication stack leveraging OpenLDAP and Authelia to centralize identity management across internal services. This stack provides secure single sign-on (SSO) and supports robust user provisioning, enabling simplified access control and enforcement of MFA policies.

## Features
- **OpenLDAP Directory**: Centralized user and group database with replication and backups.
- **Authelia Authentication & SSO**: Self-hosted two-factor authentication service integrated with OpenLDAP for SSO across web applications and APIs.
- **User Provisioning & Self-Service**: Tools for automatic user creation, password resets, and self-service account management.
- **MFA & Security Policies**: Enforce multi-factor authentication and granular access policies with Authelia's rule-based configuration.
- **Integration Examples**: Example configs for integrating services like Nextcloud, Gitea, and internal portals with the stack.
